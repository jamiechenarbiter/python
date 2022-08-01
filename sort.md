## sort a list

```python
a=[1,4,3,2,6,9]
c=[]

while len(a)>0:
    b=a[0]
    for i in range(len(a)):
        if b>a[i]:
            b=a[i]
    c.append(b)
    a.remove(b)
    
print(c)
```
