import random
password=[]
n=int(input("enter how many alphabets u need"))
l=[]
for i in range(ord('a'),ord('z')):
    l.append(chr(i))
for i in range(n):
    a=random.choice(l)
    password.append(a)
num=int(input("enter no of digits needed"))
for i in range(num):
    digit=random.randint(0,9)
    password.append(digit)
ch=int(input("enter the no of characters"))
cl=['!','@','#','$','%','^','&','*']
for i in range(ch):
    char=random.choice(cl)
    password.append(char)
random.shuffle(password)
for i in password:
    print(i,end='')
