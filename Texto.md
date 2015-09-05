#Día 1
  
## Patron para reconocer fechas  

ciudad = "\w+[\s\w+]*"  
mes = "(Ene|Feb|Mar|Abr|May|Jun|Jul|Ago|Sep|Oct|Nov|Dic)"  
fecha = "\d?\d\/"+mes+"\/2\d\d\d"  
hora = "\d?\d:\d?\d"  
am = "(A|P)M"  
patron = "^"+ciudad+"\s"+fecha+"\s"+hora+"\s"+am+"$"  
  

