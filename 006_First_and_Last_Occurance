#User function Template for python3


def find(arr,n,x):
    ele=[]
    count=0
    total=0
    for i in range(0,n):
        if (arr[i]==x):
            ele.append(i)
            count+=1
            total+=1
    if (total>0):
        return ele[0],ele[total-1]
    else:
        return -1,-1



#{ 
 # Driver Code Starts
t=int(input())
for _ in range(0,t):
    l=list(map(int,input().split()))
    n=l[0]
    x=l[1]
    arr=list(map(int,input().split()))
    ans=find(arr,n,x)
    print(*ans)
# } Driver Code Ends
