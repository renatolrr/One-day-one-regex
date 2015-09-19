#Día 1
  
## Patron para reconocer fechas  

ciudad = "\w+[\s\w+]*"  
mes = "(Ene|Feb|Mar|Abr|May|Jun|Jul|Ago|Sep|Oct|Nov|Dic)"  
fecha = "\d?\d\/"+mes+"\/2\d\d\d"  
hora = "\d?\d:\d?\d"  
am = "(A|P)M"  
patron = "^"+ciudad+"\s"+fecha+"\s"+hora+"\s"+am+"$"  
  
Fuente: Pyhton Avanzado Osl  

#Día 2  
  
##Número de teléfono.  
  
^[0-9]{3}-?[0-9]{3}-?[0-9]{3}$   
  
#Día 3 
  
##Email  

(\W|^)[\w.+\-]{0,25}@(yahoo|hotmail|gmail)\.com(\W|$)  

#Día 4 
  
##Validar un email  
  
^[a-zA-Z0-9_\-\.~]{2,}@[a-zA-Z0-9_\-\.~]{2,}\.[a-zA-Z]{2,4}$  
  
#Día 5

##Buscar números de tres digitos en un párrafo.  
  
^[:dígito:]{3}$  

#Día 6. 
  
##Buscar una ip en un rango. 

192\.168\.1\.\d{1,3}   
  
#Día 7

##Fecha en formato dd/mm/yyyy (dí­as < 32 y meses < 13) 
  
/^([0][1-9]|[12][0-9]|3[01])(\/|-)([0][1-9]|[1][0-2])\2(\d{4})$/  
  
#Día 8  
  
## Validar una URL
  
/^(https?:\/\/)?([\da-z\.-]+)\.([a-z\.]{2,6})([\/\w \?=.-]*)*\/?$/  
  
#Día 9  
  
##Validar código postal  
  
^([1-9]{2}|[0-9][1-9]|[1-9][0-9])[0-9]{3}$  
  
#Día 10. 
##Validar número de tarjeta de crédito
  
^((67\d{2})|(4\d{3})|(5[1-5]\d{2})|(6011))(-?\s?\d{4}){3}|(3[4,7])\ d{2}-?\s?\d{6}-?\s?\d{5}$  
  
#Día 11
## Validar un nombre de usuario minimo 4 caracteres maximo 10  
  
/^[a-z\d_]{4,10}$/i  
  
#Día 12. 
   
#Comprobar la seguridad de una contraseña
  
(?=^.{8,}$)((?=.*\d)|(?=.*\W+))(?![.\n])(?=.*[A-Z])(?=.*[a-z]).*$  
