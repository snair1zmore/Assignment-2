# Assignment-2
Task 1: Check if a Number is Even or Odd 
num = int(input("Enter a number: "))
if num % 2 == 0:    
  print(f"The number entered {num} is even.")
else:    
  print(f"The number entered {num} is odd.")
print("Thank you!")

Task 2: Sum of Integers from 1 to 50 Using a Loop
sum = 0
for num in range(1, 51):    
  sum = sum + num
print(f"The sum of numbers from 1 to 50 is: {sum} ")
