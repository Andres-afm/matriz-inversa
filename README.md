Este programa recibe datos de una matriz 2x2 y invierte dicha matriz:<BR><BR>
 <title>MATRIZ 2x2</title>
 <script >
function Invertir(i,j)
 {
j.reverse();
 { 
i.reverse();
 { 
 //a[i][j]=parseInt(document.matriz[].value)
 }
 }
function Matriz()
 {
var myArray=new Array(2)(2)
 for(i=1;i<=2;i++)
 { 
 for(j=1;j<=2;j++)
 { 
 a[i][j]=parseInt(document.matriz[].value)
 }
 }
 </script> 
</head>
<body text=black bgcolor=#1AA7F9>
Captura de una matriz 2x2<BR><BR>
<form name="matriz">
 <input type="text" size="3">
 <input type="text" size="3"><BR>
 <input type="text" size="3">
 <input type="text" size="3"><BR>
 <input type="button" value="Invertir Matriz" ondblclick="Invertir"><BR><BR>
</form>
</body>
</html>
