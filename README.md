# Flow-Control-in-Python:-



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

  


# .

x = 3
if x == 4:
	print("Yes")
else:
	print("No")







# if..else chain statement


letter = "A"

if letter == "B":
	print("letter is B")

else:

	if letter == "C":
		print("letter is C")

	else:

		if letter == "A":
			print("letter is A")

		else:
			print("letter isn't A, B and C")






# Nested if statement example


num = 10

if num > 5:
	print("Bigger than 5")

	if num <= 15:
		print("Between 5 and 15")






# if-elif statement example
letter = "A"

if letter == "B":
	print("letter is B")

elif letter == "C":
	print("letter is C")

elif letter == "A":
	print("letter is A")

else:
	print("letter isn't A, B or C")








 # FOR LOOP:
         . A "For loop" is used to repeat a specific block of code a Known no. of Times.



# Reverse Counting:-

for rc in range(100,0,-1):
   print(rc)


# OR

n = int(input("Enter the number:"))
for rc in range(n,0,-1):
   print(rc)


# Print each fruit in a fruit list:



fruits = ["apple", "banana", "cherry"]
for x in fruits:
  print(x)




# Loop through the letters in the word "banana":

for x in "banana":
  print(x)



# Exit the loop when x is "banana":

fruits = ["apple", "banana", "cherry"]
for x in fruits:
  print(x)
  if x == "banana":
    break




 # Exit the loop when x is "banana", but this time the break comes before the print:




fruits = ["apple", "banana", "cherry"]
for x in fruits:
  if x == "banana":
    break
  print(x)



# .


languages = ['Swift', 'Python', 'Go']

# access elements of the list one by one
for i in languages:
    print(i)



# iterate from i = 0 to i = 3

for i in range(4):
    print(i)





# While loop ---
          • while loop will run a Piece of code while a condition is True.
          • it is based on a boolean condition.




# Count 1 to 100:


x = 1
while x<101:
    print(x)
    x = x+1



# .

while False:
    print('Hii')
print('Hello')



# .


while 1==2:
    print('Hii')
print('Hello')



# if the user enters 5, the program will calculate and print the sum of the first 5 natural numbers:

n = int(input("Enter the number:"))
sum = 0
i = 1
while i<=n:
  sum = sum+i
  i = i+1
print(sum)



# the user to enter a name until the entered name is "Dhoni". Once "Dhoni" is entered, the loop exits, and "Coool" is printed:


n = input("Enter the Name:")
while n!= "Dhoni":
    n = input("Enter the Name:")
print("Coool")






# logged in ........


n = input("Enter The User Name:")
p = input("Enter The Password:")
while (n!="Rupesh kumar") or (p!= "Rupesh@1234"):
    n = input("Enter The Name:")
    p = input("Enter The Password:")
print("Logged in Successfully")




#  using nested loops to iterate over all combinations of i and j values from 0 to 3:


for i in range(4):
    for j in range(4):
        print('i={} and j={}'.format(i,j))




# Calculate the sum of numbers until user enters 0


number = int(input('Enter a number: '))

total = 0

# iterate until the user enters 0
while number != 0:
    total += number
    number = int(input('Enter a number: '))

print('The sum is', total)





# infinite while loop:


age = 32

# the test condition is always True
while age > 18:
    print('You can vote')





# Transfer Statement:-

# Break - (A break Statement, when used inside the loop, Terminate the loop & exits.)
# Continue - (continue keyword is used to end of the current loop, and continues to the next.)
# Pass - (The pass Keyword represents a null operations in Python.), (it is generally used for the purpose of Filling empty blocks of code.)




# Break - 

cart = [10,20,30,40,500,60,70]
for item in cart:
    if item>400:
        print("Sorry you can not process this order")
        break
    print("processing item",item)


# Continuec - 

cart = [10,20,30,40,500,60,70]
for item in cart:
    if item>400:
        print("Sorry you can not process this order")
        continue
    print("processing item",item)



'''for i in range(10):
    if i%2==0:
        continue
    print(i)'''



'''numbers = [10,20,0,5,70,0,2]
for n in numbers:
    if n==0:
        print("can't divide with 0")
        continue
    print('100/{} = {}'.format(n,100/n))'''



# Pass - 

cart = [10,20,30,40,500,60,70]
for item in cart:
    if item>400:
        print("Sorry you can not process this order")
        pass
    print("processing item",item)



