# Food-bill-System
I have to create a simple python code based on the food bill. in this we have to order any item it will show the current bill and if you want any additional items like pepper, salt,minus...etc. it will show additional bill if you want. 
pizza=input('Do you want Pizza: y/n: ')
if pizza=='y' or pizza=='Y':
    size=input('Enter what size do you want:S/M/L: ')
    if size=='s' or size=='S':
        bill=50
        print('Total bill is 50 rs.')
    elif size=='m' or size=='M':
        bill=100
        print('Total bill is 100 rs.')
    elif size=='l' or size=='L':
        bill=200
        print('Total bill is 200 rs.')
    want_pepperoni=input('Do you want pepperoni:Y/N: ')
    if want_pepperoni=='y' or want_pepperoni=='Y':
        if size=='s' or size=='S':
            bill+=30
            print(f'Total bill is {bill}')
        elif size=='m' or size=='M':
            bill+=50
            print(f'Total bill is {bill}.')
        elif size=='l' or size=='L':
            bill=bill+50
            print(f'Total bill is {bill}')
    extra_cheese=input('do you want extra cheese Y/N: ')
    if extra_cheese=='y' or extra_cheese=="Y":
        bill=bill+20
        print(f'Total bill is:{bill}. ')
    else:
        print('Visit Again..')

else:
    print('Come Again... Thank You.')

print( )
print('Thanking You..... Visit Again')




