# Python_Trans
Customized python syntax with [LangTrans](https://github.com/LangTrans/LangTrans)
## Customized Syntax
```js
p"Hello World"
inc = (x) => x+1
add(x,y)=>x+y
print(![inc => 1..6])
print|inc|inc(1)
try inc("1") Exception print("Error:",err)
test ="test"
=test.replace("test","")
x = True
print((x||False)?"Done":"Failed")
print('x is not defined') if !x
1 -> inc -> print
```
## Orginal Syntax
```python
print("Hello World")
inc = lambda x: x+1
add = lambda x,y:x+y
print(list(map(inc,range(1,6+1))))
print(inc(inc(1)))
try:
  inc("1")
except Exception as err:
  print("Error:",err)
test ="test"
test=test.replace("test","")
x = True
print("Done" if (x if 'x' in locals() else False) else "Failed")
if 'x' not in locals():
  print('x is not defined')
print(inc(1))  
```

If you find this more complicated than original or more syntax should be added to it, feel free to edit YAML files with your preference
