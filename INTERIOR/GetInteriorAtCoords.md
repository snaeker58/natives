---
ns: INTERIOR
---
## GET_INTERIOR_AT_COORDS

```c
// 0xB0F7F8663821D9C3 0xA17FBF37
int GET_INTERIOR_AT_COORDS(float x, float y, float z);
```

```
Returns interior ID from specified coordinates. If coordinates are outside, then it returns 0.  
Example for VB.NET  
Dim interiorID As Integer = Native.Function.Call(Of Integer)(Hash.GET_INTERIOR_AT_COORDS, X, Y, Z)
Not very precise (returns interior in front of stores for example) use GetInteriorFromEntity if precision is needed!
```

## Parameters
* **x**: 
* **y**: 
* **z**: 

## Return value
