# launchCode-projects
#Here are my collection of projects I completed for my class.


#This is a project that uses a function to calculate the area of a circle when given a radius.

import math

def areaOfCircle(r):
#Takes the radius and returns the area of the circle
    area = (r * r) * math.pi
    return area

toRadius = 5
result = areaOfCircle(toRadius)
print("The area of a square with a radius of", toRadius, "is", result)



#This is a project that determines whether or not a year is a leap year using a boolean function and chained conditionals.

def isLeap(year):
  if year % 10 == 0 and year % 400 == 0:    #centuries that are divisible by 400 are leap years
    result = True
  elif year % 10 != 0 and year % 4 == 0:    #years that aren't centuries but are divisible by 4 are leap years
    result = True
  else:      #all other years are not leap years
    result = False
  return result
print(isLeap(1900))





