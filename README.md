# odd-number-from-1-to-N in python
how to find odd number from 1 to N
n= int(input())
for i in range(1,n+1):
    if (i%2==1):
        print(i,end=" ")
        i=i+2
