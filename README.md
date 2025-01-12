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
- Arithmatic Operator
