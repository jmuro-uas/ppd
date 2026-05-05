Anotaciones:   
Trabaja en el directorio ppd: 
Para sincronizar : git stash y git pull
 
**1.Ejecutar postgresql en un contenedor :**  
sudo docker compose up -d

**2. Bajar el archivo de INEGI, de esta forma :**  
wget https://www.inegi.org.mx/contenidos/programas/ccpv/2020/datosabiertos/iter/iter_00_cpv2020_csv.zip

**3. Descomprime el archivo :**  
unzip iter_00_cpv2020_csv.zip  

**5.Para conectarte a la BD (admin:admin):**  
psql -h $(hostname -I | awk '{print $1}') -p 5432 -U admin -d pruebadb

**6.Ejecuta el archivo censo.sql**  
\i censo.sql


**Nota: Esta versión de northwind en PG, es de Pascal Thomet https://github.com/pthom/northwind_psql**
