n=int(input())
a=b=n
c=n
d=n
e=2
f=(2*n)-2
g=2
h=(2*n)-2
for i in range(1,3*n-1):
    for j in range(1,2*n):
        if (j==a or j==b)or ((i>=n and i<2*n) and (j==c or j==d))or((j==e or j==f)and (i>n and i<2*n))or(i>2*n-1 and(j==g or j==h)):
            print('#',end="")
        else:
            print(" ",end="")
    if(i>=n and i<2*n):#upper2
        c=c-1
        d=d+1
    if i<=n:#upper1
        a=a-1
        b=b+1
    if (i>n and i<2*n):#lower1
        e=e+1
        f=f-1
    if i>2*n-1:#lower2
        g=g+1
        h=h-1
    print()

