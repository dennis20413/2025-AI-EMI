
![image](https://github.com/user-attachments/assets/38d6d6c4-a95b-4dd8-ada6-be0e830e95ca)
![image](https://github.com/user-attachments/assets/7b5d5e57-650e-4fd1-a3cf-ba00f20ec114)
![image](https://github.com/user-attachments/assets/c76ca496-01ad-410d-bfa1-76bda7fa0bbf)
![image](https://github.com/user-attachments/assets/6c56f683-1d6c-43f2-9ae8-a17afb34c715)
![image](https://github.com/user-attachments/assets/8f1f782a-c8d5-4a16-add1-274996405e00)
![image](https://github.com/user-attachments/assets/361eccf8-4f80-47a0-9645-46c264c27cc2)
![image](https://github.com/user-attachments/assets/df00bff8-7482-498e-8eb6-b2cf7cc9e508)
![image](https://github.com/user-attachments/assets/85434f2e-ca50-4ddc-b22e-21c70aed864a)
![image](https://github.com/user-attachments/assets/e5589c3b-c710-449e-b38a-7b3669b4ece9)

![image](https://github.com/user-attachments/assets/9bb3bd77-b64e-4ca8-9926-98d1f38cbf52)
![image](https://github.com/user-attachments/assets/fe2dfe2f-94a5-40b4-8eb4-9c1959e4d50b)
![image](https://github.com/user-attachments/assets/880a6907-4e26-422a-9daf-07b96830d9d8)
![image](https://github.com/user-attachments/assets/cf67af19-a864-4070-b0d0-1b9bfe14bf5c)
![image](https://github.com/user-attachments/assets/f2f6c1e4-09fb-4d0a-902e-99fe05dc4ea3)
![image](https://github.com/user-attachments/assets/be4283be-397e-4ec1-ae79-cbca1bddd138)

![image](https://github.com/user-attachments/assets/67e9cbe7-c6ef-4c13-99cc-ee97e0848fc4)
----------------------------------------------------------------------------------

for i in range(10, 0, -2):
    print("test:", i)
    
----------------------------------------------------------------------------------

sum = 0
for i in range(1, 11):
    sum += i
print('1+2+3+...+10 = 55, and your result?', sum)

----------------------------------------------------------------------------------
![image](https://github.com/user-attachments/assets/61069887-8e8d-4001-895d-49b7e71fdb41)
----------------------------------------------------------------------------------

for i in range(1,10):
  print(i,'T'*i)
for i in range(10,0,-1):
  print(i,'+'*i)
  
----------------------------------------------------------------------------------
![image](https://github.com/user-attachments/assets/ce07b950-cfb5-400e-8d14-b13d1e1ce573)
----------------------------------------------------------------------------------

stage=input('input stage number:')
ss= int(stage)
for i in range(1,ss+1,+1):
  print(i,'T'*i)
for i in range(ss,0,-1):
  print(i,'+'*i)
  
----------------------------------------------------------------------------------
![image](https://github.com/user-attachments/assets/7345d432-72e5-4b33-9ab4-17172d97bedd)
----------------------------------------------------------------------------------

for i in range(1,10):
  print("%d X %d= %d" % (9,i,9*i))
  
----------------------------------------------------------------------------------

for i in range(1,4):
  for j in range(1,4):
    print("%d X %d= %d" % (9,j,9*j))
    
----------------------------------------------------------------------------------
![image](https://github.com/user-attachments/assets/97fa52e4-3831-4f75-8c5e-2cf2e621c13b)
----------------------------------------------------------------------------------

YourName='Grace'
CheckName=input("input your name pls")
if CheckName==YourName:
  print("you are the right user")
else:
  print("you are not the right user")
  
----------------------------------------------------------------------------------

YourPassword='dennis20413'
CheckPassword=input('input your password:')
if YourPassword==CheckPassword:
  print('Correct password')
else:
  print('Wrong password')
  
----------------------------------------------------------------------------------
![image](https://github.com/user-attachments/assets/536eb4fb-1a5a-4460-8136-6f1629488334)
![image](https://github.com/user-attachments/assets/41b42b2e-e0e6-4223-901f-5d8973f40a05)

## Create a list of odd numbers between 10 and 30, inclusive

----------------------------------------------------------------------------------
![image](https://github.com/user-attachments/assets/3f31092b-8dc2-456c-93ee-4a067a1d63be)


----------------------------------------------------------------------------------

## Please input a number and sum from 1 to the input number. (e.g., input 100 then the output result should be 1050)

----------------------------------------------------------------------------------
![image](https://github.com/user-attachments/assets/372178f4-7c5c-4ad6-9aeb-8f748f8f640d)

----------------------------------------------------------------------------------

![image](https://github.com/user-attachments/assets/07f225a1-e7a2-4816-b09f-d18d5c7c73f8)

----------------------------------------------------------------------------------
import calendar
import datetime

birth_str = input("Enter your birth date (YYYY-MM-DD): ").strip()

try:
    year, month, day = map(int, birth_str.split('-'))
    datetime.date(year, month, day)
except ValueError:
    print("Invalid date format or out-of-range values. Please use YYYY-MM-DD and valid month/day.")
    exit(1)

day_index = calendar.weekday(year, month, day)
days = ['Monday', 'Tuesday', 'Wednesday', 'Thursday', 'Friday', 'Saturday', 'Sunday']
print(f"\nYou were born on a {days[day_index]}.")

print(f"\nFull calendar of the year {year}:")
print(calendar.calendar(year))

----------------------------------------------------------------------------------

![image](https://github.com/user-attachments/assets/54f6d412-c65a-4c23-b41c-2fb9baa5202e)

----------------------------------------------------------------------------------
import calendar
import datetime

birth_str = input("Enter your birth date (YYYY-MM-DD): ").strip()

try:
    year, month, day = map(int, birth_str.split('-'))
    datetime.date(year, month, day)
except ValueError:
    print("Invalid date format or out-of-range values. Please use YYYY-MM-DD and valid month/day.")
    exit(1)

day_index = calendar.weekday(year, month, day)
days = ['Monday', 'Tuesday', 'Wednesday', 'Thursday', 'Friday', 'Saturday', 'Sunday']
print(f"\nYou were born on a {days[day_index]}.")

print(f"\nFull calendar of the year {year}:")
print(calendar.calendar(year))
----------------------------------------------------------------------------------
![image](https://github.com/user-attachments/assets/f96104d3-c230-49e4-86f4-5e4551a68dd4)


----------------------------------------------------------------------------------

![image](https://github.com/user-attachments/assets/68a3b26a-ea2d-4cd6-86a9-2144e825fc97)
----------------------------------------------------------------------------------
c = float(input("Enter temperature in Celsius: "))


f = c * 9/5 + 32


if f < 50:
    tag = "Cold"
elif f < 80:
    tag = "Warm"
else:
    tag = "Hot"


print(f"{c:.1f}°C is {f:.1f}°F → {tag}")
----------------------------------------------------------------------------------
![image](https://github.com/user-attachments/assets/d66acfd3-a2e1-4136-a09b-ce9f084a9370)
----------------------------------------------------------------------------------
![image](https://github.com/user-attachments/assets/4f99c4cc-1e99-4b96-aa9e-d24a0e89e09f)
----------------------------------------------------------------------------------

email = input("Enter your email: ").strip()

if email.count("@") == 1 and "." in email.split("@")[1]:
    username, domain = email.split("@", 1)

    if username and not domain.startswith(".") and not domain.endswith("."):
        print("Valid email!")
        print("Username:", username)
        print("Domain  :", domain)
    else:
        print("Invalid email format.")
else:
    print("Invalid email format.")
----------------------------------------------------------------------------------
![image](https://github.com/user-attachments/assets/f0b4ef7d-2eb9-47ed-ac04-64cdede95544)
----------------------------------------------------------------------------------
![image](https://github.com/user-attachments/assets/dc1797ae-8d45-432e-a222-2fc4942eed2d)

----------------------------------------------------------------------------------
import random

a = random.randint(1, 100)
b = random.randint(1, 100)


print(f"What is {a} + {b}?")


correct = a + b


user_input = input("Your answer: ")


try:
    ans = int(user_input)
    if ans == correct:
        print("Correct!")
    else:
        print("Try again.")
except ValueError:
    print("Please enter a valid number.")

----------------------------------------------------------------------------------
![image](https://github.com/user-attachments/assets/cb05c7cb-9340-4b89-9ab5-7bccb834fb43)

----------------------------------------------------------------------------------
![image](https://github.com/user-attachments/assets/d766e2ec-5119-4f47-9e49-b1fa63aad59e)
----------------------------------------------------------------------------------




text = input("Enter a sentence: ")


vowels = [c for c in text.lower() if c in "aeiou"]
print("Vowel count:", len(vowels))

words = text.split()
reversed_sentence = " ".join(words[::-1])
print("Reversed sentence:", reversed_sentence)

----------------------------------------------------------------------------------
![image](https://github.com/user-attachments/assets/88604670-8b90-4fd1-904d-93b923620f8b)
