##########
name = input('0i,what is your name?')
print ('hi', name, '?')

age = int(input('what is yor age?'))
if age >=18:
    print ('sorry bro')
else:
    print('you are a kidS') 

######


import time
import pyautogui
count = 5
for i in range(5):
    print(count)
    time.sleep(1)
    count = count - 1
for i in range(100):
    pyautogui.typewrite('Allah')
    pyautogui.press('enter')


#############variable

a = 4
b = 4
x = (a == b)
print(x)

a = 4
b = 4
x = (a != b)
print(x)

a = 4
b = 3
x = (a > b)
print(x)

###########statement 

tshirt = 100
if tshirt < 120:
    print('i can buy')
else:
    print('i cant buy')


tshirt = 120
if tshirt < 120:
    print('i can buy')

elif tshirt == 120:
    print( 'i can buy')
else:
    print('i cant buy')
    

    
