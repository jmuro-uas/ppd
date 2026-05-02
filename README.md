Anotaciones:  
En el directorio ppd:  


**1. Bajar el archivo de INEGI, de esta forma :**  
wget https://www.inegi.org.mx/contenidos/programas/ccpv/2020/datosabiertos/iter/iter_00_cpv2020_csv.zip

**2. Descomprime el archivo :**  
unzip itter_00_cpv2020_csv.zip  

**3.Para conectarte a la BD:**
psql -h $(hostname -I | awk '{print $1}') -p 5432 -U admin -d pruebadb

**4.Ejecuta el archivo censo.sql**  

\i censo.sql



