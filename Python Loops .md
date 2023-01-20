# Loops 



![2022-08-21 (6)](E:\محاضرات مايسترو\2022-08-21 (6).png)

we have condition  >> True >>loop cod >>> true  >> loop code >>> false  >>>stop  going to the another code >>>>>

------------

## while loop :

```python
x = 0 # definition one variable
while x < 10 : طالما 
    print (x)
    x +=1
```



[^]: !image-20220821025018412(C:\Users\49157\AppData\Roaming\Typora\typora-user-images\image-20220821025018412.png)

-------------------

## infinite  loop :  >> No Stop 

```python
x = 0 #infinite loop 
while x < 10 : طالما 
    print (x)
  #0+0+0+0+0+0+0...................
```

------------

We can else with while  :

```python
x = 0
while x < 10 :
    print (x)
    x +=1
else :
    print ("stop")
```



---------------------

single statement while :

```python
x = 0
while x < 10 : print (x) ; x +=1 # dont forgot the (;)
else : print ("stop")
    
 
    
    

    
```

 

----------------------

## Nested While loop : 

very important  !!!!!

```py
x = 0
while x < 5 :
    y = 0
    while y < 10 :
        print (x , y)
        y = y+1
    x = x+1
        
```

-------------------

## For loop : لكل جزء من كل 

```python
for a in (1,2,3,4,5,6):
    print (a)
    1
    2
    3
    4
    5
    6
for x in ("Ahmad,Alakash"):
    print (x)

```

---------------

For have function  very important she is range : 

```python
range (end , start=0 ,step = 1)
range (10) # 0 1 2 3 4 5 6 7 8 9
range (3,10) #start with 3 end with 10 step default 1
range (3,10,2) #start with 3 end with 10 step 2
#ex for range using we need convert the values in range to list or tuple >>
range (10)
range(0, 10) # just object from range function
list (range (10)) # no forgot just to 9 when we 10 we need to 11 
[0, 1, 2, 3, 4, 5, 6, 7, 8, 9]
list (range (11))# 
[0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10]
# To the reverse walking we need start end step -():
list (range (11 ,1 , -1))
[11, 10, 9, 8, 7, 6, 5, 4, 3, 2]


```

-------------

Nested For :

```python
for x in range (10):
    for y in range (15):
        print (x,y)

```

----------

### Loop With Lists :

```python
numbers = [[1,2,3,4,5],[6,7,8,9,10],["Hdil","Alma","Ahmad"],[True , False]] # list of lists
for x in  numbers : 
    print (x)
    for y in x :
        print (y)
    print ("---------------------") # father loop

```

--------------

## For  VS  While    

We make the first with For when we can not this with for use we while 

For loop : when we know what how match we loop ex :  with lists with tuple and another type from this data ..........

While loop : when we don't know how match we loop  >> true loop >>true loop ???? >>> False  don't loop and going to another code  

------------

## Loop Control Statements :

### The First Statement is Break  ex :

```python
# break with condition
x = 0
while x < 10 :
    if x == 5: # Condition
        break
    print (x)
    x +=1
1
2
3
4

```

------------

The Second  Statement is Continue ex :

```python
for x in range (10) :
    if x == 6 :
        continue
    print (x)
    x +=1

```

------------------

### Pass statement : 

```python
def mysum (name):
    for x in range (10):
        pass                  # placeholder حجز مكان 

    print (x)

```

### EX :

------------------



```python
#1
print ("Numbers" "\t""\t" "Square")
print ("---------------------------")
for x in range (11) :
    print (x ,"\t""\t" ,x*x)

```

-------------------------

```python
#2
print ("This code prints a list of numbers and their squares")
Start = int(input ("Enter Start Number : "))
End = int(input ("Enter End Number : "))

print ("Numbers" "\t""\t" "Square")
print ("---------------------------")
for x in range (Start ,End+1) :
    print (x ,"\t""\t" ,x*x)

```

---------------

```python
#3
Start = int(input("Enter the starting number : ")) # rows
End = int(input("How high should i go : ")) # cols
for x in range (Start):
    for y in range (End):
        print ("x",end ="")  # print= what we have write + new line =\n
        
       
   
    print ()


```

--------------

```python
#4
base = 10
for x in range (base):
    for y in range (x+1):
        print ("x", end ="")
    print ()

-------------

when i will print list with while loop : 

ex : 

thislist = ["apple", "banana", "cherry"]
i = 0
while i < len(thislist):
  print(thislist[i])
  i = i + 1 

