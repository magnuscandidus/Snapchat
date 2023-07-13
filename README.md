# Snapchat
# cook your dish here
t=int(input())
while t:
    n=int(input())
    a=list(map(int,input().split()))
    b=list(map(int,input().split()))
    c=0
    for i in range((len(a)) and (len(b))):
        if(a[i]!=0 and b[i]!=0):
            c+=1
    print(c)
    t-=1
