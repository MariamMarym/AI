```python
#Read 1st number

num1 = input ('pls enter the 1st number : ')

#Read 2nd number
num2= input ('pls enter the 2nd number : ')

#Read operations
op= input ('pls enter the operation : ')

#convert operations to number
num1=float(num1)
num2=float(num2)
if op == '+' :
    res = num1 + num2
    print ("sum =" , res)

elif op == "-" :
    res = num1 - num2
    print ("sub =" , res)
    
elif op == '*' or op == 'x' or op == 'X'  :
    res= num1*num2 
    print ("mul=" ,res)
    
elif op == '/'    :
    res= num1/num2
    print ("div=" , res)
    

```

    pls enter the 1st number : 10
    pls enter the 2nd number : 20
    pls enter the operation : *
    mul= 200.0
    


```python

```
