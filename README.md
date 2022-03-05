# 4-3-2022-Assignment-02
l=[]

n=int(input())

for i in range(n):

    x=int(input())

    l.append(x)

print(l)

c={}

for i in l:

     c[i]=l.count(i)

print(c)
