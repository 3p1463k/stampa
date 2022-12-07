# Stampa
### Simple date time stamp in for of string


```python
from Stampa import Stamp

stamp = Stamp("stamp")
print(stamp)
```
######  20221207105819060212


```python
from Stampa import Stamp


stamp = Stamp("year")
print(stamp)
```
###### 2022

```python
from Stampa import Stamp

stamp = Stamp("month")
print(stamp)
```
###### 202212

```python
from Stampa import Stamp

stamp = Stamp("day")
print(stamp)
```
######  20221207

```python
from Stampa import Stamp

stamp = Stamp("hour")
print(stamp)
```
######  2022120717

```python
from Stampa import Stamp

stamp = Stamp("min")
print(stamp)
```
######  202212071743


```python
from Stampa import Stamp

stamp = Stamp("sec")
print(stamp)
```
######  20221207174413


```python
help(Stampa)
```
```
Help on class Stampa in module __main__:

class Stampa(builtins.object)
 |  Gets string date time without spaces
 |  
 |  Data descriptors defined here:
 |  
 |  __dict__
 |      dictionary for instance variables (if defined)
 |  
 |  __weakref__
 |      list of weak references to the object (if defined)
 |  
 |  ----------------------------------------------------------------------
 |  Data and other attributes defined here:
 |  
 |  stamp = '20221130120356396799'
 |  
 |  stampday = '20221130'
 |  
 |  stamphour = '2022113012'
 |  
 |  stampmin = '202211301203'
 |  
 |  stampmonth = '202211'
 |  
 |  stampsec = '20221130120356'
 |  
 |  stampyear = '2022'
```
