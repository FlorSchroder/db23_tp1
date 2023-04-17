### Enunciado

Se trata de modelar una fábrica de piezas mecánicas. 
Cada pieza se puede encontrar formada por otras **piezas**. 
Cada una tiene un número identificatorio. 
Las piezas reciben distintos **tratamientos**, Se necesita almacenar como se compone cada pieza (los pasos de **ensamblado**) y los tratamientos que debe recibir. De las piezas se registra una *fecha de ensamblado* y *fecha y hora que reciben un tratamiento* y *quien lo realiza*.
Modelar los **empleados** y el organigrama de la empresa (opt)

#### 1. Analizar el enunciado detectando los sustantivos y sus interrelaciones, los sustantivos son candidatos a entidades

- Entidad:
    - Pieza
    - Tratamiento
    - Ensamblado
    - Plano
- Relaciones


- NOTA:
    - Trampa dos significados para Pieza.
    - Entidad Plano (profe)
### 2. Formar la matriz de entidades

<TABLE>
	<TR>
		<TD>E\E</TD>
        <TD>Pieza</TD>
        <TD>Tratamiento</TD>
        <TD>Ensamblado</TD>
        <TD>Empleado</TD>
        <TD>Plano</TD>
	</TR>
	<TR>
		<TD>Pieza</TD> 
        <TD>Tiene</TD> 
        <TD>Tiene</TD>
        <TD>Recibe</TD>
        <TD>Ensamblado por</TD>
        <TD>Tiene</TD>
	</TR>
    <TR>
		<TD>Tratamiento</TD> 
        <TD>Realizado a</TD> 
        <TD>X</TD>
        <TD>-</TD>
        <TD>Es realizado por</TD>
        <TD>Esta especificado</TD>
	</TR>
    <TR>
		<TD>Ensamblado</TD> 
        <TD>De</TD> 
        <TD>-</TD>
        <TD>X</TD>
        <TD>Es realizado por</TD>
        <TD>Esta especificado</TD>
	</TR>
    <TR>
		<TD>Empleado</TD> 
        <TD>Ensambla</TD> 
        <TD>Realiza</TD>
        <TD>Hace</TD>
        <TD>X</TD>
        <TD>Lee</TD>
	</TR>
    <TR>
		<TD>Plano</TD> 
        <TD>Especifica</TD> 
        <TD>Especifica</TD> 
        <TD>Especifica</TD> 
        <TD>Es leido</TD> 
        <TD>X</TD>
	</TR>
</TABLE>

Supuesto:

- El plano da informacion sobre el tratamiento

### 3. Construir un primer DER
### 4. Análisis de cardinalidades
### 5. Detectar e eliminar redundancias
### 6. Convertir el DER en entidades relacionales (o tablas)
### 7. Implementar en el motor usando DDL


### Obsevaciones de Clase by Algorry
- No hay entidad fabrica porque hay solo una
- Hay pieza fisica y modelo de pieza.
- N a M se MODELA COMO TABLA INTERMEDIA