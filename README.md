# my_main.py
Assignment to Non_Academy
#Step:2 
# টাস্ক ১: ভ্যারিয়েবল ও ডাটা টাইপ
my_name = "Foisol Arif" 
my_age = 33           
is_student = False     


print(my_name)
print(my_age)
print(is_student)



print(type(my_name))
print(type(my_age))
print(type(is_student))
print("="*30 + "\n")


#টাস্ক ২: অ্যারিথমেটিক অপারেটর 
# টাস্ক ১: ভেরিয়েবল ডিক্লেয়ারেশন (Task 1: Variable Declaration - Added for context)
my_age = 22
is_student = True 
number_to_operate = 5

# Print initial values
print(f"Initial values: my_age = {my_age}, number_to_operate = {number_to_operate}")
print("="*30 + "\n")

# টাস্ক ২: অ্যারিথমেটিক অপারেটর (Task 2: Arithmetic Operators - Added for context)

# গুণ (Multiplication)
multiplication_result = my_age * number_to_operate
print(f"{my_age} * {number_to_operate} = {multiplication_result}")

# যোগ (Addition)
addition_result = my_age + number_to_operate
print(f"{my_age} + {number_to_operate} = {addition_result}")

# ভাগ (Division)
if number_to_operate != 0:
    division_result = my_age / number_to_operate
    print(f"{my_age} / {number_to_operate} = {division_result}")


# বিয়োগ (Subtraction)
subtraction_result = my_age - number_to_operate
print(f"{my_age} - {number_to_operate} = {subtraction_result}")
print("="*30 + "\n")

# টাস্ক ৩: কম্পারিজন অপারেটর (Task 3: Comparison Operators)
is_adult = my_age > 18
print(f"Is adult? ({my_age} > 18): {is_adult}")

print(f"Is age == 22? ({my_age} == 22): {my_age == 22}")
print(f"Is age != 30? ({my_age} != 30): {my_age != 30}")
print(f"Is age < 20? ({my_age} < 20): {my_age < 20}")
print(f"Is age >= 25? ({my_age} >= 25): {my_age >= 25}")
print("="*30 + "\n")


# টাস্ক ৪: লজিক্যাল অপারেটর (Task 4: Logical Operators)
condition1 = my_age > 20      # Is age greater than 20?
condition2 = is_student       # Is the person a student?

print(f"Condition 1 (age > 20): {condition1}")
print(f"Condition 2 (is_student): {condition2}")

# Logical AND
print(f"Condition 1 AND Condition 2: {condition1 and condition2}")

# Logical OR
print(f"Condition 1 OR Condition 2: {condition1 or condition2}")

# Logical NOT
print(f"NOT Condition 1: {not condition1}")
print(f"NOT Condition 2: {not condition2}")
print("="*30 + "\n")

# টাস্ক ৫: অ্যাসাইনমেন্ট অপারেটর (Task 5: Assignment Operators - Added for context)
num = 10
print(f"Initial num: {num}")

# +=
num += 5

print(f"After num += 5: {num}")

# -=
num -= 3

print(f"After num -= 3: {num}")

# *=
num *= 2

print(f"After num *= 2: {num}")

# /=
# Added a check to prevent division by zero if num was 0 before this step
if num != 0:
    num /= 4
    
    print(f"After num /= 4: {num}")
else:
    print("Cannot perform num /= 4 because num is currently 0")
print("="*30 + "\n")

# টাস্ক ৬: আইডেন্টিটি অপারেটর (Task 6: Identity Operators - Added for context)
list_a = [1, 2, 3]
list_b = [1, 2, 3] # Same content, different object in memory
list_c = list_a   # Same object in memory as list_a

print(f"list_a: {list_a}")
print(f"list_b: {list_b}")
print(f"list_c: {list_c}")

# 'is' checks if they are the same object in memory
print(f"list_a is list_b: {list_a is list_b}")  # False (different objects)
print(f"list_a is list_c: {list_a is list_c}")  # True (same object)

# 'is not' checks if they are different objects in memory
print(f"list_a is not list_b: {list_a is not list_b}") # True
print(f"list_a is not list_c: {list_a is not list_c}") # False

# '==' checks if the contents are equal
print(f"list_a == list_b: {list_a == list_b}") # True (contents are the same)
print("="*30 + "\n")

# টাস্ক ৭: মেম্বারশিপ অপারেটর (Task 7: Membership Operators - Added for context)
fruits = ["apple", "banana", "cherry", "date"]
print(f"Fruits list: {fruits}")

# 'in' checks if an item exists within a sequence
check_fruit_1 = "banana"
print(f"Is '{check_fruit_1}' in fruits? ({check_fruit_1} in fruits): {check_fruit_1 in fruits}") # True

check_fruit_2 = "mango"
print(f"Is '{check_fruit_2}' in fruits? ({check_fruit_2} in fruits): {check_fruit_2 in fruits}") # False

# 'not in' checks if an item does not exist within a sequence
print(f"Is '{check_fruit_1}' not in fruits? ({check_fruit_1} not in fruits): {check_fruit_1 not in fruits}") # False
print(f"Is '{check_fruit_2}' not in fruits? ({check_fruit_2} not in fruits): {check_fruit_2 not in fruits}") # True
print("="*30 + "\n")
