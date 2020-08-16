# IPYTHON BASIC 



## 内省 

```Ipython

[IN] b = [1, 2 ,3]
     b?

[IN] print?

[In] def add_numbers(a,b):
        return a + b

# print function description 
[In] add_numbers?
# print function source
[In] add_numbers??

```


## `%run` and `%load`

1. `%run`

```Ipython 
%run hello.py
```

it's like run shell command

```bash
python hello.py 
```

2. `%load`

```Ipython
%load hello.py

def f(x,y,z):
    return (x+y)/z
    a = 5
    b = 6
    c =7.5
    result = f(a, b, c)
```

It load some code on a python file 

## `%paste` and  `%cpaste`

run paste code 


## magic function list 

- `%quickref`
- `%magic`
- `%debug`
- `%hist`
- `%pdb`
- `%paste`
- `%cpaste`
- `%reset`
- `%page OBJECT`
- `%run scripy.py`
- `%prun statement`
- `%time statement`
- `%timeit statement`
- `%who, %who_ls, %whos`
- `%xdel variable`


## integrated `matplotlib`

`%matplotlib`