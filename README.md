# python-program-9
import math
a=int(input("Enter a"))
b=int(input("Enter b"))
c=int(input("Enter c"))
d=(b*b)-(4*a*a*c)
if d>0:
print("roots are:")
x1=-b+math.sqrt(d)/(2*a)
x2=-b-math.sqrt(d)/(2*a)
print("x1==",x1)
print("x2==",x2)
else:
print("roots are imaginarey.")
output
Enter a5
Enter b7
Enter c9
roots are imaginary.
