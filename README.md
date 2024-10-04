# coffe-shop
code will be bale to print a receipt for a coffee shop order
code will fisrt ask what the how many of the items on the menu the user would like
then it will calculate the order and give a proce to the user


print('********************************************')
print('Coffe shop order')
coffee = float(input('Number of coffees bought?: '))
print(coffee)
muffin = float(input('Number of muffins bought?: '))
print(muffin)
sandwich = float(input('Number of sandwiches bought?: '))
print(sandwich)
smoothie = float(input('Number of smoothies bought?: '))
print(smoothie)
print('********************************************')
print('')
print('')
print('********************************************')
print('My Coffee and Muffin Shop Receipt')
coffPrice = coffee * 5
muffPrice = muffin * 4
sandPrice = sandwich * 6
smoothPrice = smoothie * 3
print(coffee ,'Coffee at $5 each: $', coffPrice)
print(muffin ,'Muffins at $4 each: $', muffPrice)
print(sandwich ,'Muffins at $6 each: $', sandPrice)
print(smoothie ,'Muffins at $3 each: $', smoothPrice)
Total = coffPrice + muffPrice + sandPrice + smoothPrice
tax = Total * .06
print('6% tax: $', tax)
print('------------')
newTotal = Total + tax
print('Total: $', newTotal)
print('********************************************')
print('Thank you for your purchase, have a great day until next time')
