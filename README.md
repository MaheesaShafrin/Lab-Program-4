# Lab-Program-4
Program to demonstrate Tuple and its built-in functions
numbers=(10,20,30,40,50,20)
print("Original Tuple:",numbers)
print("First Element:",numbers[0])
print("Last Element:",numbers[-1])
print("Tuple slice(index 1 to 4):",numbers[1:5])
print("Count of 20:",numbers.count(20))
print("Index of 40:",numbers.index(40))
print("Length of Tuple:",len(numbers))
print("Maximum value:",max(numbers))
print("Minimum value:",min(numbers))
print("Sujm of Tuple elements:",sum(numbers))
new_tuple=numbers+(60,70,80)
print("After concatination:",new_tuple)
repeat_tuple=numbers*2
print("Repeated Tuple:",repeat_tuple)

Output
Original Tuple: (10, 20, 30, 40, 50, 20)
First Element: 10
Last Element: 20
Tuple slice(index 1 to 4): (20, 30, 40, 50)
Count of 20: 2
Index of 40: 3
Length of Tuple: 6
Maximum value: 50
Minimum value: 10
Sujm of Tuple elements: 170
After concatination: (10, 20, 30, 40, 50, 20, 60, 70, 80)
Repeated Tuple: (10, 20, 30, 40, 50, 20, 10, 20, 30, 40, 50, 20)

31.Write a Python program that accepts a string and calculate the number of digits and
letters.
s=input("Input a string")
d=l=0
for c in s:
    if c.isdigit():
        d=d+1
    elif c.isalpha():
        l=l+1
    else:
        pass
    print("Letters",l)
    print("Digit",d)
Output
Input a stringAloof
Letters 1
Digit 0
Letters 2
Digit 0
Letters 3
Digit 0
Letters 4
Digit 0
Letters 5
Digit 0

