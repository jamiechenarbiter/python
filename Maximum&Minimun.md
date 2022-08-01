## Maximum
```python
a=[1,4,3,2,6,9]
b=0
for i in range(len(a)):
    if b<a[i]:
        b=a[i]
print(b)
```

## Minimum
```python
a=[1,4,3,2,6,9]
b=a[0]
for i in range(len(a)):
    if b>a[i]:
        b=a[i]
print(b)
```
