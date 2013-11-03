IDL is a particular programming langugage which has its quirks:


* case insensitive



Globals are declared like this:

```idl
common block_name, x, y
```

you cannot initialize on the same line as declaring a global

```idl
x=1
print , x
```


Notice that when you are printing the "," is there to separate print and x.  This syntax you'll find all the time in this langauge.
