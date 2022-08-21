#  Python with Mystro :

------------------------------------

## Variables

المتغيرات هي عبارة عن فيم لها اسم

نستطيع مناداتها بكتابة اسمها 

ومعرفة نوعها ايضا باستخدام دالة ال 

type ex: 



~~~python
#1 int>>>> for  integer numbers ex:
x = 1

x

type (1)

```

```

(1)

<class 'int'
~~~

-----------------------

```python
#2 str >>>>>>> for strings : "" '' ''' '''
x = "1"
   
x
   
'1'
type ("1")
   
<class 'str'>
x = "ahmad"
   
x
   
'ahmad'
type ("ahmad")
   
<class 'str'>


```

----------------------------------------

```python

#3 float>>>>> for float numbers ex :
x = 2.5
   
x
   
2.5
type (x)
   
<class 'float'>

```

```python
#4 bool [ True/False] ex :
x = 10
   
x
   
10
x > 10
   
False
x >=10
   
True
x<=10
   
True

```

```python
#5 list >>>>>> list of values and  we can edit ex : # []
[1,"ahmad",2.5,True] # []
   
[1, 'ahmad', 2.5, True]
type ([1,"ahmad",2.5,True])
   
<class 'list'>


```

```python
#6 tuple >>>>list of values and we can not edit ex : #()
(1, 'ahmad', 2.5, True)#()
   
(1, 'ahmad', 2.5, True)
type ((1, 'ahmad', 2.5, True)
)
   
<class 'tuple'>

```

```python
#7 dict >>>>>> for dict of values and one values have two parts ex :>> {}
{1:"ahmad",2:"Hadil",3:"Alma"}
   
{1: 'ahmad', 2: 'Hadil', 3: 'Alma'}
type({1:"ahmad",2:"Hadil",3:"Alma"})
   
<class 'dict'>


```



```python
#sigle Assignment :
x = 5
s = "Welcome"

# Multiple Assignment :
x , y , f = 4 ,"ahmad", 2.5
x
   
4
type (x)
   
<class 'int'>
y
   
'ahmad'
type (y)
   
<class 'str'>
f
   
2.5
type (f)
   
<class 'float'>
#############
a = s = f = 1
   
a
   
1
s
   
1
f
   
1


```

# ### when we will   the value cahnge from ex : >>>> string  to integer >> we can this just with >>>> قيم تقبل هذا الامر 

```python
# ex :
x = "5"
x
'5'
type (x)
<class 'str'>
int (x)
5
type (int (x))
<class 'int'>
##############################
float ("5")
5.0
type (float ("5"))
<class 'float'>


```

 

```python
###
my_name ="Ahmad"
age = 28
print ("my_name is my_name and i am age years old")
my_name is my_name and i am age years old # not was we will look at the (my_name)  and the (age)we have not what we will >>>> we need add {}  and (f) for formating
print (f"my_name is {my_name} and i am {age} years old")
my_name is Ahmad and i am 28 years old

```

---------------------------------

python start with __(0)

when we will one or more from ex one value  

```python
#indexing
f = "Ahmad"
f[0]
"A"
f[4]
"d"
# we can from right to lift >>
f[-1]
"d"
f[-3]
"m"
```

---------------------------------------------------------------------------------------

```python
#تقطيع الكلمات لقطع اصغر 
#string
d = "ahmad"
d
'ahmad'
d[0 :3]
'ahm'
d[:3]
"ahm"
d[-2]
"a"
```

-----------------------------

### #######list تقطيع

```python
# we can add value or deleted 
f = [1,2,3,4,True,"ahmad"]

f
[1, 2, 3, 4, True, 'ahmad']
f[0]
1
f[:5]
[1, 2, 3, 4, True]
f[5]
'ahmad'
f[-2]
True

```

---------------------

## tuple تقطيع

```python
t =(1, 2, 3, 4, True, 'ahmad')
t
(1, 2, 3, 4, True, 'ahmad')
t[0],t[-1]
(1, 'ahmad')
# we can not add info , value   or deleted with tuple 
```

------------------

## dict تقطيع

```python
# we can add or deleted value or info from him 

di ={'Ahmad': 100, 'Hadil': 100, 'Alma': 100, 'Lareen': 500}
di
{'Ahmad': 100, 'Hadil': 100, 'Alma': 100, 'Lareen': 500}

di ["Lareen"]
500
di ["Lareen"]=1234
di[]
SyntaxError: invalid syntax
di["Lareen"]
1234
di
{'Ahmad': 100, 'Hadil': 100, 'Alma': 100, 'Lareen': 1234}


```











# intro  30 .07 >>>>>>> 33:34
