# daily-javascript-q2

You are reviewing another developer's code. The body of the page contains the following: 

``` javascript
<div id="result" class="format-output"></div>
  	<script> 
       	var x = 3; 
       	var y = '3'; 
       	var t = x + y; 
       	var a = 7, b = 29; 
       	var result = document.getElementById("result"); 
       	var result1 = result2 = ' '; 

       	if (x == y) 
            	result1 = "x == y"; 
       	else if (x === y) 
            	result1 = "x === y"; 

       	if (t == 33) 
            	result2 = "t == 33"; 
       	else if (b%a == 1) 
            	result2 = "t === 33"; 

       	result.innerHTML = result1 + ";" + result2; 
  	</script> 
```

What will be displayed when the page is previewed in the browser?

A) x == y;t === 33

B) x === y;t === 33

C) x == y;t == 33

D) x === y;t == 33
