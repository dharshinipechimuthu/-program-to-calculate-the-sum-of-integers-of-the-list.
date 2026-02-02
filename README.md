# -program-to-calculate-the-sum-of-integers-of-the-list.
L=[1,2,"tWO",3,4,"fOUR",5]
s=0
for x in L:
    if type(x)==int:
        s=s+x
print("The sum of integers is:",s)

OUTPUT:

The sum of integers is: 15

