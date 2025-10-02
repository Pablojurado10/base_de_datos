# Actividad 1. Ejercicios de unidad – 

## 1. Funciones del administrador de la base de datos  
El administrador se encarga de cuidar la base de datos: crearla, darle permisos a los usuarios, hacer copias de seguridad y arreglarla si se rompe.  

---

## 2. Diferencias entre manipulación y descripción  
- **Manipulación**: trabajar con los datos (añadir, borrar, cambiar).  
- **Descripción**: crear y cambiar las tablas o estructuras.  

---

## 3. Tipos de usuarios  
- Los que usan la base de datos con programas (usuarios normales).  
- Los que crean programas que la usan.  
- El administrador (DBA).  

---

## 4. Lenguaje huésped y anfitrión  
- **Anfitrión**: el lenguaje principal (ej: Java).  
- **Huésped**: el que se mete dentro (ej: SQL).  

---

## 5. Gestión del almacenamiento y arquitectura ANSI/SPARC  
- La gestión del almacenamiento es del **nivel interno**.  
- La arquitectura ANSI/SPARC es un modelo de 3 niveles: externo (lo que ve el usuario), conceptual (cómo se organizan los datos) e interno (cómo se guardan).  

---

## 6. Diagrama ANSI/SPARC  



---

## 7. Funciones del SGBD  
- Guardar datos.  
- Consultar datos.  
- Evitar problemas si varios usan la base a la vez.  
- Seguridad (quién puede entrar).  
- Recuperar datos si pasa algo malo.  

---

## 8. Independencia física y lógica  
- **Física**: si cambias cómo se guarda, los usuarios no lo notan.  
- **Lógica**: si cambias las tablas, los programas pueden seguir funcionando igual.  

---

## 9. Diccionario de datos  
Es como un “manual” donde el sistema guarda información sobre las tablas, columnas, usuarios, etc.  

---

## 10. LDD y LMD  
- **LDD**: para crear y modificar tablas.  
- **LMD**: para meter y cambiar datos dentro de las tablas.  

---

## 11. Componentes de un SGBD  
- Motor de base de datos.  
- Procesador de consultas.  
- Seguridad.  
- Transacciones.  
- Diccionario de datos.  

---

## 12. Modelo de datos  
Es una forma de organizar los datos, por ejemplo en tablas (relacional).  

---

## 13. Lenguajes de cuarta generación  
Son lenguajes que hacen las cosas más fáciles y rápidas, como SQL.  

---

## 14. Ventajas y desventajas  
**Ventajas:** menos datos repetidos, más seguridad, más control.  
**Desventajas:** son caros y más difíciles de manejar que archivos normales.  

---

## 15. Clasificación ficheros vs BBDD  
- **Ficheros:** CSV, texto plano.  
- **BBDD:** Oracle, MongoDB, MySQL.  

---

## 16. Tipos de bases de datos  
- **Clave-valor:** pares clave y valor (como un diccionario).  
- **Relacional:** en tablas.  
- **Grafos:** en nodos y relaciones.  
- **Documental:** en documentos JSON o parecidos.  

---

## 17. Centralizadas vs distribuidas  
### Centralizada
- **Ventajas:** fácil administración, coherencia de datos.  
- **Desventajas:** un único punto de fallo, baja escalabilidad.  

### Distribuida
- **Ventajas:** mayor disponibilidad, escalabilidad.  
- **Desventajas:** complejidad de sincronización.  

---

## 18. Cinco funciones del SGBD  
1. Guardar datos.  
2. Consultar datos.  
3. Seguridad.  
4. Evitar errores si muchos acceden a la vez.  
5. Copias de seguridad.  

---

## 19. Clasificación SGBD  
- **MySQL:** Relacional – Open Source.  
- **Oracle Database:** Relacional – Comercial.  
- **MongoDB:** Documental – Open Source.  
- **Redis:** Clave-valor – Open Source.  
- **PostgreSQL:** Relacional – Open Source.  
- **Neo4j:** Grafos – Comercial (aunque tiene versión gratuita limitada).  

---

## 20. Caso práctico base de datos distribuida  
Sería útil en una empresa grande con tiendas en todo el país.  
- Ventaja 1: Si un servidor falla, los demás siguen funcionando.  
- Ventaja 2: Es más rápido porque los datos están cerca de donde se usan.  
- Ventaja 3: Se puede ampliar fácilmente añadiendo más servidores.  

---

## 21. Teorema CAP  
- **C** = Consistencia (todos ven los mismos datos).  
- **A** = Disponibilidad (siempre funciona).  
- **P** = Tolerancia a particiones (aunque haya cortes en la red).  

En las bases distribuidas no se pueden tener las 3 a la vez, normalmente eligen **Disponibilidad + Tolerancia a particiones**.  

---

## 22. Fragmentaciones de la tabla EMPLEADOS  
a) **Horizontal:** separar por departamentos (ventas, informática, etc.).  
b) **Vertical:** separar datos personales (nombre, apellido) de los salariales (salario, fecha).  
c) **Mixta:** primero por departamento y dentro de cada uno dividir en personales y salariales.  

---

## 23. Tabla comparativa  

| Característica          | Sistema de Ficheros | Sistema de Bases de Datos |
|-------------------------|----------------------|----------------------------|
| Redundancia de datos    | Alta                 | Baja                       |
| Control de concurrencia | No                   | Sí                         |
| Independencia de datos  | No                   | Sí                         |
| Seguridad               | Baja                 | Alta                       |
