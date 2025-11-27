1. Printing "Hello, World!"
Python

print("Hello, World!")
2. Variables and Basic Arithmetic
Python

name = "Alice"
age = 30
print(f"My name is {name} and I am {age} years old.")

num1 = 10
num2 = 5
sum_result = num1 + num2
print(f"The sum of {num1} and {num2} is: {sum_result}")
3. Conditional Statements (if-elif-else)
Python

temperature = 25

if temperature > 30:
    print("It's a hot day!")
elif temperature > 20:
    print("It's a pleasant day.")
else:
    print("It's a bit chilly.")
4. Loops (for and while)
Python

# For loop
fruits = ["apple", "banana", "cherry"]
for fruit in fruits:
    print(fruit)

# While loop
count = 0
while count < 5:
    print(count)
    count += 1
5. Functions
Python

def greet(name):
    return f"Hello, {name}!"

message = greet("Bob")
print(message)
6. Lists
Python

my_list = [1, 2, 3, 4, 5]
print(my_list[0])  # Accessing elements by index
my_list.append(6)  # Adding an element
print(my_list)
7. Dictionaries
Python

person = {"name": "Charlie", "age": 40, "city": "New York"}
print(person["name"])
person["occupation"] = "Engineer"
print(person)
