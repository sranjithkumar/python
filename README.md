python
======
contwork = 1
while contwork == 1:
 x,y,z = input("enter the three no:")
 d=x+y+z
 if d % 3 == 0:
   avg = d / 3
   print "avg is:",avg
 
 else:
   avg = d / 3.0
   print "avg is:",avg
 
 contwork = input("Enter 1 to continue and 0 to quit: ")
