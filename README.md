# -1_-_-_-_-183.
<!DOCTYPEhtml>
 <html> 
<head> 
<title> 
лаб раб 1 </title>
 <!имя страницы> 
<link rel="stylesheet" type="text/css" href="style.css"> 
<script language="javascript">
 </script>
 </head>
 <body> 
<form name="forma1">
 Введите натуральное число n <input type="text" name="n" size="10" />
<br /><br />
 Введите целое число р <input type="text" name="p" size="10" />
<br /><br /> 
Введите целые числа а1, ... ,аn <input type="text" name="an" size="10" />
<br /><br /> 
<input type="button" value="вычислить" onclick="otvet();" />
<br /><br />
 ответ<input type="text" name="res" size="20" /> <br /><br /> </form> <script> function otvet() 
{ var n = document.forma1.n.value; var p = document.forma1.p.value; var o = 0; var f = 1; arr = document.forma1.an.value.split(' '); for(var s = 0; s<n;s++) 
{ o = parseFloat(arr[s]) / parseFloat(p); alert(o); if (parseInt(o) == o)
{ f = f * o; } } document.forma1.res.value = f; } 


</script> 
</body>
 </html>
