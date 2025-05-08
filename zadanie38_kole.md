<!DOCTYPE html>
<html lang="PL-pl">
    <meta charset="UTF-8">
    <html> 
        <body> 
        <div style="color:red;font-size:50px;"> 
            <script language="JavaScript">    

        var imi_kol=prompt("Podaj imię=",""); 

        var naz_kol=prompt("Podaj nazwisko=",""); 

        document.write('<font color="green" style="font-size: 45px;">Moje imię i nazwisko to: ' + imi_kol + ' ' + naz_kol + '<br></font>');


        var dlugosc_imi = imi_kol.length;
        var dlugosc_naz = naz_kol.length;

        document.write('<font color="green" style="font-size: 45px;">liczba1 = ' + dlugosc_imi + '</font><br>');

        l2_kol = dlugosc_imi + 7;

        document.write('<font color="green" style="font-size: 45px;">liczba2 = ' + dlugosc_imi +" + " +  7 +" = " +  l2_kol + '</font><br>');

        document.write('<font color="green" style="font-size: 45px;">liczba3 = ' + dlugosc_naz + '</font><br>');

        l4_kol = dlugosc_naz + 4;

        document.write('<font color="green" style="font-size: 45px;">liczba4 = ' + dlugosc_naz +" + " +  4 +" = " +  l4_kol + '</font><br><br><br><br>');

                



        document.write('<button onclick="menu_kol()">Wybierz opcję z menu</button><br><br>');
        
        document.write("<font color=red>----------MENU----------</font>" + "<br>");

        document.write("<font color=red>" + dlugosc_imi + " - wyświetlenie teorii o operatorach</font><br>");

        l5_kol = dlugosc_naz + 20;

        document.write("<font color=red>" + l5_kol + " - czy liczba należy do przedziału ( " + dlugosc_imi + " ; " + l2_kol + "]" + "</font><br>");

        uro_kol = 1 + 50;

        document.write("<font color=red>" + uro_kol + " - czy liczba należy do przedziału (-∞ ; " + dlugosc_naz + ") lub [" + l4_kol + " ; +∞)" + "</font><br>");


        function menu_kol() 
        {

            var opcje_kol = prompt("Podaj opcję= ");

            if (opcje_kol==dlugosc_imi)     
            {
                document.write("<font color=blue size=7>Jesteś w opcji " + dlugosc_imi + "--> teoria </font>"+"<br>"); 
                document.write("<font color=green size=7>&& i x=3 y=4 (x < 9 && y > 2 ) wynik-->prawda <br>|| lub x = 3 Y = 4 (x=8 || y=6) wynik-->fałsz <br>! zaprzeczenie x = 3 Y = 4 !(xy) wynik-->prawda</font>");
            }
            
            else if (opcje_kol==l5_kol)     
            {
                var l6_kol = parseFloat(prompt("Podaj liczbę= "));

                document.write("<font color=blue size=7>Jesteś w opcji " + l5_kol + " --> przedział </font>"+"<br>"); 
                
                if (l6_kol > dlugosc_imi && l6_kol <= l2_kol) 
                {
                    document.write("<font color=green>Liczba nalezy do przedziału</font><br>");
                } 
                else 
                {
                    document.write("<font color=green> Liczba nie nalezy do przedziału</font><br>");
                }
            }  
            
            else if(opcje_kol==uro_kol)
            {
                var l7_kol = parseFloat(prompt("Podaj liczbę= "));

                document.write("<font color=blue size=7>Jesteś w opcji " + uro_kol + " --> przedział </font>"+"<br>"); 

                if (l7_kol < dlugosc_naz || l7_kol >= l4_kol) 
                {
                    document.write("<font color=green>liczba należy do przedziału</font><br>");
                } else 
                {
                    document.write("<font color=green>liczba nie należy do przedziału</font><br>");
                }
            }

        }
            </script> 
        </div> 
        </body> 
       </html>
</html>