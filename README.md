# python-linear-search

# Python program to implement linear search

numbers = [4, 2, 7, 1, 8, 3, 6]

# Flag to check if element is found
found = False

# Input element to search
x = int(input("Enter the number to be found: "))

# Linear search
for i in range(len(numbers)):
    if x == numbers[i]:
        print("Successful search, the element is found at position", i)
        found = True
        break

if not found:
    print("Oops! Search unsuccessful")


OUTPUT:

Enter the number to be found: 7
Successful search, the element is found at position 2
