def encryption(a):
    for i in a:
        q=ord(i)
        ew=chr(q+n)
        eword.append(ew)
    print("encoded message=",end='')
    print(*eword)
def decode(eword):
    for i in eword:
        j=ord(i)
        dw=chr(j-n)
        dword.append(dw)
    print("decoded message=",end='')
    print(*dword)
eword=[]
dword=[]
a=str(input("enter a word"))
n=int(input("enter no of shifts"))
encryption(a)
decode(eword)
