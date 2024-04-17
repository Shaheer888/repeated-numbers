# repeated-numbers
The code is used to eliminate any repeated numbers 

a=[1,2,4,4,1,4,2,6,2,9]
i=0

for i in range(len(a)-1):
    x=i+1
    while x< len(a):

        if (a[i]==a[x]):
            a.pop(x)
        else:
            x=x+1

   

print(a)


    
