Anotaciones:

**1.Esta versión de northwind en PG, es de Pascal Thomet https://github.com/pthom/northwind_psql**

**2.Para conectarte a la BD:**
psql -h $(hostname -I | awk '{print $1}') -p 5432 -U admin -d pruebadb
