# study

this repository about my steps in  IT

day 1:
Python Variable Name Rules
A variable name must start with a letter or the underscore character<br>  
A variable name cannot start with a number<br>
A variable name can only contain alpha-numeric characters and underscores (A-z, 0-9, and _ )<br>
Variable names are case-sensitive (firstname, Firstname, FirstName and FIRSTNAME) are different variables)<br>

Getting user input using the input() built-in function.

print(type('Asabeneh'))          # str<br>
print(type(first_name))          # str<br>
print(type(10))                  # int<br>
print(type(3.14))                # float<br>
print(type(1 + 1j))              # complex<br>
print(type(True))                # bool<br>
print(type([1, 2, 3, 4]))        # list<br>
print(type({'name':'Asabeneh'})) # dict<br>
print(type((1,2)))               # tuple<br>
print(type(zip([1,2],[3,4])))    # zip<br>

# int to float<br>
num_int = 10<br>
num_float = float(num_int)<br>

# float to int<br>
gravity = 9.81<br>
print(int(gravity))<br>

# int to str<br>
num_int = 10<br>
num_str = str(num_int)<br>

# str to int or float<br>
num_str = '10.6'<br>
num_float = float(num_str)  # Convert the string to a float first<br>
num_int = int(num_float)    # Then convert the float to an integer<br>
print('num_int', int(num_str))      # 10<br>
print('num_float', float(num_str))  # 10.6<br>
num_int = int(num_float)<br>
print('num_int', int(num_int)<br>

# str to list<br>
first_name = 'Asabeneh'<br>
print(first_name)               # 'Asabeneh'<br>
first_name_to_list = list(first_name)<br>
print(first_name_to_list)<br>
