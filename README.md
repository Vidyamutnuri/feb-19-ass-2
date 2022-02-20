# feb-19-ass-2
Assignment-2
def prime(n):
    for i in range (2,n):
        if n%i==0:
            return False
    return True
t=int(input())
for i in range(t):
    n=int(input ())
    c=0
    for i in range(2,n+1):
        if prime(i):
            c=c+1
    print(c)
