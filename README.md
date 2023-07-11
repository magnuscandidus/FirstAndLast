# FirstAndLast
# cook your dish here
for i in range(int(input())):
    n=int(input())
    a=list(map(int,input().split()))
    st=0
    for i in range(len(a)):
        s=a[i]+a[i-1]
        if(s>st):
            st=s
    print(st)
