<html>
<body bgcolor="#D3D3D3">
<div style="color:green;font-size:31px;">
<script language="JavaScript">

var liczba1=prompt("Dzien1=","");
var liczba2=prompt("Dzien2=","");
var ile_sekund_kol;

var D1_kol=parseFloat(liczba1);
var D2_kol=parseFloat(liczba2);

ile_sekund_kol=(D1_kol-D2_kol)*24*3600;

document.write("Dzien1=" +D1_kol+"<br>");
document.write("Dzien2=" +D2_kol+"<br>");
document.write("Sekund=" +ile_sekund_kol+" sek"+"<br>");

</script>
</div>
</body>
</html>
