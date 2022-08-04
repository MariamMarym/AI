```python
#Comparision
```


```python
5>4
```




    True




```python
5<4
```




    False




```python
5==4
```




    False




```python
5!=4
```




    True




```python
5  is not  4
```

    <>:1: SyntaxWarning: "is not" with a literal. Did you mean "!="?
    <>:1: SyntaxWarning: "is not" with a literal. Did you mean "!="?
    C:\Users\ALFORS~1\AppData\Local\Temp/ipykernel_18896/167638253.py:1: SyntaxWarning: "is not" with a literal. Did you mean "!="?
      5  is not  4
    




    True




```python
5 is 4 
```

    <>:1: SyntaxWarning: "is" with a literal. Did you mean "=="?
    <>:1: SyntaxWarning: "is" with a literal. Did you mean "=="?
    C:\Users\ALFORS~1\AppData\Local\Temp/ipykernel_11288/519160097.py:1: SyntaxWarning: "is" with a literal. Did you mean "=="?
      5 is 4
    




    False




```python
5>4 and 6>4
```




    True




```python
5<4 and 6>4
```




    False




```python
5>=4
```




    True




```python
5<=4 or 6>=5
```




    True




```python
#Read ege 

age = input ('pls enter your age : ')
 
gender = input ('pls enter your gender : ')

#Convert age

age = float(age)



# Compare age

if age >= 18 and (gender == 'male' or gender == 'm' ) :
    print ('male ok')
elif age < 18 and (gender == 'male' or gender == 'm') :
       print ('male no')
elif age >= 20 and (gender == 'female' or gender == 'f') :
        print ('female ok')
elif age < 20 and (gender == 'female' or gender == 'f') :
      print ('female no')
else :
    print ('undefined gender')
```

    pls enter your age : 24
    pls enter your gender : female
    female ok
    


```python

```
