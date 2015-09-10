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
 
 
 
