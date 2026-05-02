Anotaciones:

**1.Esta versión de northwind en PG, es de Pascal Thomet https://github.com/pthom/northwind_psql**

**2.Para conectarte a la BD:**
psql -h $(hostname -I | awk '{print $1}') -p 5432 -U admin -d pruebadb

**3. Bajar el archivo de INEGI, de esta forma :**  
wget https://www.inegi.org.mx/contenidos/programas/ccpv/2020/datosabiertos/iter/iter_00_cpv2020_csv.zip

**4. Descomprime el archivo :**
unzip itter_00_cpv2020_csv.zip

