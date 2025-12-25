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
    
######################Loop

a = ('apple')
for i in a:
    print('my name is farid')
    
for i in range(100):
    print('my name is farid')




########### import time , payautogui
import time
a = 5
for i in range(5):
    print(a)
    time.sleep(1)
    a = a - 1


###large message
    import pyautogui
for i in range(100):
    pyautogui.typewrite('my name is farid')
    pyautogui.press('enter')
    time.sleep(.1)


import time
import pyautogui
a = 5
for i in range(5):
    print(a)
    time.sleep(1)
    a = a - 1
for i in range(100):
    pyautogui.typewrite('my name is farid')
    pyautogui.press('enter')   
    time.sleep(.1)


########### input fanction

name = input('what is your name?')
print ('hi', name, '?')

age = int(input('what is yor age?'))
if age >=18:
    print ('sorry brother')
else:
    print('you are a kid')

    
