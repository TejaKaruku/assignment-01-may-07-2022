# assignment-01-may-07-2022
n=int(input("enter the number"))
l=[]
d={}
for i in range(n):
    x=int(input())
    l.append(x)
for i in l:
    if i%2==0:
        d[i]='yes'
    else:
        d[i]='no'
print(d)
