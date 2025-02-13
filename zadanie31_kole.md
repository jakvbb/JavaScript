<html> 
     <head> 
           <script type="text/javascript"> 
                 var telefon = { 
   marka: 'Nokia', 
   model: '3310', 
   cena: '1250', 
   kolor: 'szary',
   wejście: 'USB-C',
   wyswietl_kolendo: function () 
     { 
        document.write(this.marka + ' ' + this.model) 
     } 
  } 
  telefon.wyswietl_kolendo(); 
  telefon.data_wydania=2000;
  telefon.wypisz=function(){alert(this.marka + " została wydana w " + this.data_wydania + " roku")}
  telefon.wypisz();
            </script> 
     </head> 
<body> 
 <br> 
   Programowanie obiektowe. <br> 
     Obiekt  to  telefon<br> 
     Pola:<br> 
     Marka<br> 
     Model<br> 
     Cena<br>
     Kolor<br>
     Wejście<br> 
     metoda:  telefon_wyswietl_kolendo<br> 
     Nowe pole to data_wydania <br>
     Nowa metoda to wypisz(); <br>
</body> 
</html> 