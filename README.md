# study

this repository about my steps in  IT

day 1:
Python Variable Name Rules

A variable name must start with a letter or the underscore character  

A variable name cannot start with a number

A variable name can only contain alpha-numeric characters and underscores (A-z, 0-9, and _ )

Variable names are case-sensitive (firstname, Firstname, FirstName and FIRSTNAME) are different variables)

Getting user input using the input() built-in function.

print(type('Asabeneh'))          # str
print(type(first_name))          # str
print(type(10))                  # int
print(type(3.14))                # float
print(type(1 + 1j))              # complex
print(type(True))                # bool
print(type([1, 2, 3, 4]))        # list
print(type({'name':'Asabeneh'})) # dict
print(type((1,2)))               # tuple
print(type(zip([1,2],[3,4])))    # zip

# int to float
num_int = 10
num_float = float(num_int)

# float to int
gravity = 9.81
print(int(gravity))

# int to str
num_int = 10
num_str = str(num_int)

# str to int or float
num_str = '10.6'
num_float = float(num_str)  # Convert the string to a float first
num_int = int(num_float)    # Then convert the float to an integer
print('num_int', int(num_str))      # 10
print('num_float', float(num_str))  # 10.6
num_int = int(num_float)
print('num_int', int(num_int)

# str to list
first_name = 'Asabeneh'
print(first_name)               # 'Asabeneh'
first_name_to_list = list(first_name)
print(first_name_to_list)
