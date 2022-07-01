import math
def PerfectSquare(x):
    root=math.sqrt(x)
    if int(root+0.5)**2==x:
        print("YES")
    else:
        print("NO")
    return root
n=int(input())
PerfectSquare(n)
