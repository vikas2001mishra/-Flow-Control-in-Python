# -Flow-Control-in-Python



# If statements:
        Python supports the usual logical conditions from mathematics:
        Equals: a == b
        Not Equals: a != b
        Less than: a < b
        Less than or equal to: a <= b
        Greater than: a > b
        Greater than or equal to: a >= b


a = 33
b = 200
if b > a:
  print("b is greater than a")



# .

  a = 20
if a>0:
  print("Its Positive")


# .

n = 10
if n % 2 == 0:
   print("n is an even number")



# else statements:



a = 20
b = 10
c = 15
if a > b:
   if a > c:
      print("a value is big")
   else:
       print("c value is big")
elif b > c:
    print("b value is big")
else:
     print("c is big")




# Elif:
     The elif keyword is Python's way of saying "if the previous conditions were not true, then try this condition".



a = 33
b = 33
if b > a:
  print("b is greater than a")
elif a == b:
  print("a and b are equal")




# .

a = 200
b = 33
if b > a:
  print("b is greater than a")
elif a == b:
  print("a and b are equal")
else:
  print("a is greater than b")

  

