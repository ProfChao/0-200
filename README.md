
# Python program to print Even Numbers from 0-200
  
start, end = 0, 200
  
# iterating each number in list
for num in range(start, end + 1):
      
    # checking condition
    if num % 2 == 0:
        print(num, end = " ")
