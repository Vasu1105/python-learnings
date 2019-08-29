# Python Learnings

Starting Python Interactive Mode

```
$ python3
Python 3.7.3 (default, Apr  3 2019, 19:16:38) 
[GCC 8.0.1 20180414 (experimental) [trunk revision 259383]] on linux
Type "help", "copyright", "credits" or "license" for more information.
>>> 

```

# Source Code Encoding 

To declare an encoding other than the default one, a special comment line should be added as the first line of the file. The syntax is as follows:

```
# -*- coding: encoding -*-

```

One exception to the first line rule is when the source code starts with a UNIX “shebang” line. In this case, the encoding declaration should be added as the second line of the file. For example:

```
#!/usr/bin/env python3
# -*- coding: cp1252 -*-
```
# Notes

The keyword argument end can be used to avoid the newline after the output, or end the output with a different string:
```
>>>
>>> a, b = 0, 1
>>> while a < 1000:
...     print(a, end=',')
...     a, b = b, a+b
...
0,1,1,2,3,5,8,13,21,34,55,89,144,233,377,610,987,
```
https://docs.python.org/3/tutorial/controlflow.html
