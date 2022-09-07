

<h1 align = center>Math - New Comers</h1>

 # Constnants

$$\Huge \pi \quad$$ `#define PI acos(-1)` used mostly in **Geomtry**</br>
$$\Huge \epsilon \quad$$`#define EPS 1e-9`  used in comparing **Doubles**</br>
$$\large MOD \quad$$ `#define Mod 1'000'000'007` used as common **Modulus** for big numbers </br>


---
# Functions
## Rounding 
1.  **Floor** $$\large floor(x)=\lfloor x \rfloor$$
**floor()** function **returns the largest integer less than or equal to a given number**.


<div align = center>
<table>
<thead>
<tr>
<th style="text-align:center">1</th>
<th style="text-align:center">1</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:center">0</td>
<td style="text-align:center">0</td>
</tr>
<tr>
<td style="text-align:center">1.1</td>
<td style="text-align:center">1</td>
</tr>
<tr>
<td style="text-align:center">1.7</td>
<td style="text-align:center">1</td>
</tr>
<tr>
<td style="text-align:center">-1.7</td>
<td style="text-align:center">-2</td>
</tr>
<tr>
<td style="text-align:center">-1.1</td>
<td style="text-align:center">-2</td>
</tr>
</tbody>
</table>
</div>

```cpp
#include <cmath>
floor(1.1); // 1
flooe(1.7); // 1
```

2. **ceil** $$\large ceil(x)=\lceil x \rceil$$
**ceil()** function **computes the smallest integer that is greater than or equal to x.**
<div align = center>
<table>
<thead>
<tr>
<th style="text-align:center">1</th>
<th style="text-align:center">1</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:center">0</td>
<td style="text-align:center">0</td>
</tr>
<tr>
<td style="text-align:center">1.1</td>
<td style="text-align:center">2</td>
</tr>
<tr>
<td style="text-align:center">1.7</td>
<td style="text-align:center">2</td>
</tr>
<tr>
<td style="text-align:center">-1.7</td>
<td style="text-align:center">-1</td>
</tr>
<tr>
<td style="text-align:center">-1.1</td>
<td style="text-align:center">-1</td>
</tr>
</tbody>
</table>
</div>

```cpp
#include <cmath>
ceil(1.1); // 2
ceil(1.7); // 2
```
 
3. **Round** $$\large round(x)=\lfloor x \rceil$$
**round()** function **returns the integral value that is nearest to the argument, with halfway cases rounded away from zero**.


<div align = center>
<table>
<thead>
<tr>
<th style="text-align:center">1</th>
<th style="text-align:center">1</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:center">0</td>
<td style="text-align:center">0</td>
</tr>
<tr>
<td style="text-align:center">1.1</td>
<td style="text-align:center">1</td>
</tr>
<tr>
<td style="text-align:center">1.7</td>
<td style="text-align:center">2</td>
</tr>
<tr>
<td style="text-align:center">-1.7</td>
<td style="text-align:center">-2</td>
</tr>
<tr>
<td style="text-align:center">-1.1</td>
<td style="text-align:center">-1</td>
</tr>
</tbody>
</table>
</div>

```cpp
#include <cmath>
round(1.1); // 1
round(1.7); // 2
```
4. **Truncate** <br> **trunc()** function **removes the decimal part from a number.**
<div align = center>
<table>
<thead>
<tr>
<th style="text-align:center">1</th>
<th style="text-align:center">1</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:center">0</td>
<td style="text-align:center">0</td>
</tr>
<tr>
<td style="text-align:center">1.1</td>
<td style="text-align:center">1</td>
</tr>
<tr>
<td style="text-align:center">1.7</td>
<td style="text-align:center">1</td>
</tr>
<tr>
<td style="text-align:center">-1.7</td>
<td style="text-align:center">-1</td>
</tr>
<tr>
<td style="text-align:center">-1.1</td>
<td style="text-align:center">-1</td>
</tr>
</tbody>
</table>
</div>

```cpp
#include <cmath>
trunc(1.1); // 1
trunc(1.7); // 2
```


### resources
#### articles
[Floor](https://www.programiz.com/cpp-programming/library-function/cmath/floor)
[Ceil](https://www.programiz.com/cpp-programming/library-function/cmath/ceil)
[round](https://www.programiz.com/cpp-programming/library-function/cmath/round)
[trunc](https://www.programiz.com/cpp-programming/library-function/cmath/trunc)
#### Videos
[YT -   Portfolio Courses](https://www.youtube.com/watch?v=FixR9aiVsy4)
[YT - Mostafa saad](https://youtu.be/Syx2qDjj7TE?list=PLPt2dINI2MIY7l5zyFd1W28rei3b-AXaJ&t=702)

---

## GCD - Greatest Common Divisor

