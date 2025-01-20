# Learn-python

Hello world in python

print("Hello world!")

#python comments 

#I am single line comments

'''
i
 am
   multiline
 comments
'''

## Python block of code simple:
```
if 10>5:
     print("this is true")
    print("i am tab identation")

 print("i have no identation")
```

## single variable
```
 s = "Bob"
 print(s)
```

## Multiple variable 
- s = "Alice"
- age = 25
- city = "new yourk"
- print(s, age, city)

## Output formatting
```
amount = 150.75
print("Amount : ${:.2f}".format(amount))
```


## Python input
```
name = input("Enter your name:")
print("Hello", name, "Welcome!")
```


## Rules of variable
- variable names can only contain letters, digit and underscors(_)
- a variable name cannot start with a digit.
- variable names are case-sensitive (myVar and myvar are different)
- avoid using python kewords

## Two type declare a variable
- local 
- global

## Local variable 
```
def f():
  a = "I am local"
  print(a)
f()

```

## Global variable
```
def f():
  global a 
  a = "modifed global"
  print(a)

f()
print(a)
```

## Types operator in python
- Arithmatic Operator ( +, -, *, /, %)
- Comparison Operator ( <, >, ==, != )
- Logical Operator (AND, NOT, OR)
- Bitwise Operator (&, |, <<, >> )
- Assignment Operator (=, +=, -=, *=, %=)

## Nested if..else condition statement
```
age = 70
is_number = True

if age >= 60:
  if is_number:
    print('30% senior discount')
  else:
      print('20% senior discount')
else:
  print('Not eligible for a senior discount.')
```

## range loop

```
for i in range(0,10,2):
  print(i)
```

## while loop

```
count = 0
while (count < 3):
  count = count + 1
  print("Hello world!")
```

## Recursion function

```
def factorial(n):
  if n== 1:
    return 1
  else:
    return n * factorial(n-1)

print(factorial(5))

```
## Python usages self as argument

```
class Car:
  def __init__(self, brand, model):
    self.brand = brand
    self.model = model
  
  def display(self):
    return self.brand, self.model

car1 = Car("Toyota", "abc1")

print(car1.display())

```

## python oop concept

```
# single inheritance

class Dog:
  def __init__(self, name):
    self.name = name

  def display_name(self):
    print(f"Dog's name {self.name}")
  
  #single inheritance
class Labrador(Dog):
  def Sound(self):
    print("Labrador woof")

 #multilevel inheritance

class GuideDog(Labrador):
  def guide(self):
    print(f"{self.name} Guides the way!")

# multiple inheritance

class Friendly:
  def greet(self):
    print("Friendly!")
  
class GoldenRetriver(Dog, Friendly):
  def sound(self):
    print("Golden Retrirver Barks")

  #single inheritance
  lab = Labrador("Buddy")
  lab.display_name()
  lab.Sound()


# multilevel inheritance
  guide_dog = GuideDog("Max")
  guide_dog.display_name()
  guide_dog.guide()

# multiple inheritance
retriver = GoldenRetriver("Charlier")
retriver.display_name()
retriver.greet()
retriver.sound()
```



