<!DOCTYPE html>
<html lang="PL-pl">
    <meta charset="UTF-8">
    <html> 
        <body> 
        <div style="color:red;font-size:50px;"> 
            <script language="JavaScript"> 
        var x_kol=prompt("podaj liczbę x=",""); 
        var a_kol=parseFloat(x_kol); 
        document.write("czytana liczba x="+a_kol+"<br>");     
            if(a_kol>0) 
            {
                document.write("czytana liczba jest większa od 0"+"<br>");
            } 

            if(a_kol==0) 
            {
                document.write("czytana liczba jest równa 0."+"<br>");
            }

            if(a_kol<0) 
            {
                document.write("czytana liczba jest mniejsza od 0"+"<br>");
            }
            </script> 
        </div> 
        </body> 
       </html>
</html>