# ass-2-18-02-22
sum of n factorial numbers
def factorial(num):
    fact=1
    while(num>0):
        fact=fact*num
        num=num-1
    return(fact)
n=int(input("Enter Value of n : "))
sum=0
for a in range(1,n+1):
    sum=sum+factorial(a)
print("Sum of Factorials : ",sum)
output:
enter value of n:45
Sum of Factorials :  122342346998826717539665299944651784048588130840420940313
> 
