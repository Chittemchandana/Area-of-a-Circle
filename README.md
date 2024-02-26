# Area-of-a-Circle
# approach1
# Python program to find Area of a circle

def findArea(r):
	PI = 3.142
	return PI * (r*r);

# Driver method
print("Area is %.6f" % findArea(5));

# approach2
# Python Program to Find Area of a Circle With Math library
# Python program to find Area of a circle
# using inbuild library

import math
def area(r):
area = math.pi* pow(r,2)
return print('Area of circle is:' ,area)
area(4)

# approach3
import math as M  
Radius = float (input ("Please enter the radius of the given circle: "))  
area_of_the_circle = M.pi* Radius * Radius  
print (" The area of the given circle is: ", area_of_the_circle)  

# approach4
import math  
  
def area_of_the_circle (Radius):   
    area = Radius** 2 * math.pi  
    return area  
  
Radius = float (input ("Please enter the radius of the given circle: "))  
print (" The area of the given circle is: ", area_of_the_circle (Radius))  
