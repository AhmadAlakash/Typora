# Python Conditions & Functions .



## Conditions : شرط

## ex :

```python
#1
name = "Ahmad"
if name == "Ahmad":
    print (name)
#2 
x = 10
if x > 9 : print (True)
if x ==10 :
    print (x)
if x >= 12:
    print (True)

```



```python
# multi conditions
name = input("Enter your name :")



if name == "Ahmad" or "ahmad":
    print("You are welcom")
    

elif name == "Hadil" or "hadil":
        print ("Hello My Love")

elif name == "Alma" or "alma":
    print ("Hello Almasa")

   


else :
    print("Welocom but your name is not found")

```

--------------------

### when we have any true with multi conditions python make stop with him but when is false she going to another  ......

-------------------

## Nested if Condition : 

she is a multi conditions  ex :

```python
x = 100
if x > 50 :
    print ("true ")

    if x > 60 :
        print ("true 2")

    if x > 101 :

        print ("true")

    else :
            print ("false")
# بعد ان ينتهي من تنفيذ الشروط يكمل البرتامج غمله >>>>>>>
print ("Hello world")

```

---------------

## if with  boolean operators :

we can use AND & OR with if when we have more than one condition :

```python
## ex :
name = input("Enter your name :")
age = int(input("Enter your age :"))


if name == "Ahmad" or "ahmad" and age == 28:
    print("You are welcom")
    


elif name == "Hadil" or "hadil" and age == 26:
        print ("Hello My Love")

elif name == "Alma" or "alma" and age == 6 :
    print ("Hello Almasa")


else :
    print(f" Heloo {name}"" you are Welocom but your name is not found")
    

```

-------------------------

```py
# ex 2 :  this is what we have with face or twiter or any app
name = input("Enter Your Name :")
age = int(input("Enter your age :"))
password =int(input("Enter your password"))
if name  ==  "Ahmad"or"ahmad" and age == 29  :
    if  password !=123123   :
        
       print ("you forgot your passowrd , reset your passowrd please")
    else :
           print (f"{name} you are Welcom with facebook")
elif name  ==  "Hadil"or"hadil" and age == 26  :
    if  password !=123   :
        
       print ("you forgot your passowrd , reset your passowrd please")
    else :
           print (f"{name} you are Welcom with facebook")
elif name  ==  "Alma"or"alma" and age == 6  :
    if  password !=123123123   :
        
       print ("you forgot your passowrd , reset your passowrd please")
    else :
           print (f"{name} you are Welcom with facebook")
else :
    print (f" Hello {name} we have not account with this name , create new account please")

```

------------------------------

## single if  statement : 

```py
x = 100 # normal
if x > 99 :
    print ("done")
else :
    print ("false")
  #######################
#2 single if statement
x = 100
if x > 99 : print ("done")##
else :
    print ("false")
    #########################
    #3
    #true condition false>>>>
     #### ternary  operator : ( True  Condition   False) #### #### ex :
x = 100
print ("done")   if x > 99 else print ("false")
    


    
  
```

----------

## Conditions best practices : ex :1

using condition with dictionary elements (in  - not in )

### 

```python
## ex :
numbers =[2,3,4,5,6,7]
if 2 in numbers :
    print ("true")
    if 15 not in numbers :
        print ("not in ")
    if 5 not in numbers :
        print ("true")

```

------------------

### Conditions best practices : Ex 2

using (all   -  any ) with more than one condition :

```python
x = 5
y = 10
z = 15                  ## the first type with [and]& [or] 
if x == 5 and y == 10 and z == 15 : # we need all options true
    print ("true")
if x == 5 or y == 10 or z == 15 : # we need at least  one option true
    print ("true in or ")

# we can all using instead and and and 
# we can any using instead or or or
#ex :
if all ([x == 5,y ==10,z ==15]): # we need all options true
    print ("true in all")

if any ([x == 5,y ==10,z ==5]):  #we need at least one option true
    print ("true in any")

```



--------------------------------------------------------------------------------------------------------

--------------------------

-------------------------------

--------------------------------

# Python Functions: 

she is more cods in one   [دالة ]

when we  will this function to used need just write  the name this function (Call##)

```python
#ex :
  sum x,y # function take two values and return the sum  
### Definition تعريف
def sum2 (x,y): # (x,y) arguments ,parameters
    result = x+y
    return result 

# 
t = sum2 (10,6)
print (t)
    

```

-------------------

```python
##
def name (name):
    result = "welcome  " +name
    return result


n = name("Hadil")
print (n)


a = name ("Alma ")
print (a)

```



------------------------

```python
###### 

def mylen (name):
    result = len(name)
    return result


s = mylen ("Alakash")
print (s)
f = mylen ("Alshikh")
print (f)


```

----------------

------------

## Function Arguments :

<<>> You can call a function by using the following types of formal arguments :

-  required arguments

- ```python
  ###### 
  
  def mylen (name):
      result = len(name)
      return result
  
  
  s = mylen ("Alakash")
  print (s)
  f = mylen ()  # no argument 
  print (f)
  # error - missing -1 required positional argument ("name")
  ```

  

- keyword arguments

- ```python
  def sum2 (x,y): # (x,y) arguments ,parameters
      result = x+y
      return result 
  
  # 
  t = sum2 (10,6)
  print (t)
  16
  
   t = sum2 (10)## we need two arguments and python give the first argument what we write first ex 
  print (t)
  ##error missing one argument y 
  
  t = sum2 ( y=10)
  print (t)
  #error missing one argument x
  
  
  
  ```

  

- default arguments

- ```python
  def sum2 (x,y): 
      result = x+y
      return result 
  
  
  t = sum2 (10,6)
  print (t)
  16
  #def sum2 (x = 0 , y = 0): 
     # result = x+y
      #return result 
  
  t = sum2 ()  # !!!no argument  we have default argument (0)
  print (t) 
  0
  
  ```

  

- variable - length arguments

----------------------------

---------------------------

## Anonymus Function (الدالة المجهولة):

```python
# 1
 #default the  lambda return 
myname = lambda name : "welcome " + name
t = myname ("ahmad")
print (t)

welcome ahmad

# 2
myname2 = (lambda name : "welcome 2 " + name)("ahmad")
print (myname2)

welcome 2 ahmad

#1
mysum2 = lambda x,y : x/y
z = mysum2 (100,50)
print (z)

2.0
#2
mysum3 = (lambda x,y : x/y)(150,3)
print (mysum3)
50.0
```

++++++++++++++

