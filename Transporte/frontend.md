<!DOCTYPE html>
<html>
<body>

<h3>Nuevo Pedido</h3>
<form onsubmit="return false">
  <input type="text"  placeholder="DNI Cliente"><br>
  <input type="text"  placeholder="Descripcion"><br>
  <select>
    <option value="" disabled selected>Origen</option>
    <option value="">1. Rio Segundo</option>
    <option value="">2. Rio Tercero</option>
    <option value="">3. Rio Cuarto</option>
    <option value="">4. Cordoba Capital</option>
  </select><br>
   <select>
    <option value="" disabled selected>Destino</option>
    <option value="">1. Rio Segundo</option>
    <option value="">2. Rio Tercero</option>
    <option value="">3. Rio Cuarto</option>
    <option value="">4. Cordoba Capital</option>
  </select><br>
  <select>
    <option value="" disabled selected>Rutas Disponibles</option>
    <option value="">Rio Segundo 07:00 dd/mm/aa - Rio Tercero 19:00 dd/mm/aa</option>
     <option value="">Rio Segundo 07:15 dd/mm/aa - Rio Tercero 09:00 dd/mm/aa</option>
  </select>
  <input type="submit" value="Actualizar"><br>
  <input type="submit" value="Cargar Pedido">
</form> 

<h3>Nuevo Cliente</h3>
<form onsubmit="return false">
  <input type="text"  placeholder="Nombre Cliente"><br>
  <input type="text"  placeholder="DNI"><br>
  <input type="text"  placeholder="Telefono"><br>
  <input type="submit" value="Cargar">
</form> 

<h3>Cancelar Pedido</h3>
<form onsubmit="return false">
  <input type="text"  placeholder="ID Pedido"><br>
  <input type="text"  placeholder="DNI Cliente"><br>
  <input type="submit" value="Cancelar">
</form> 

<hr>
<h3>Nueva Localidad</h3>
<form onsubmit="return false">
  <input type="text"  placeholder="Nombre de Localidad"><br>
  <input type="text"  placeholder="Provincia"><br>
  <input type="menu"  placeholder="Pais"><br>
  <input type="text"  placeholder="Codigo Postal"><br>
  <input type="submit" value="Cargar">
</form> 

<h3>Nueva Ruta</h3>
<form onsubmit="return false">
  <select>
    <option value="" disabled selected>Localidad 1</option>
    <option value="">1. Rio Segundo</option>
    <option value="">2. Rio Tercero</option>
    <option value="">3. Rio Cuarto</option>
    <option value="">4. Cordoba Capital</option>
  </select><br>
    <select>
    <option value="" disabled selected>Localidad 2</option>
    <option value="">1. Rio Segundo</option>
    <option value="">2. Rio Tercero</option>
    <option value="">3. Rio Cuarto</option>
    <option value="">4. Cordoba Capital</option>
  </select><br>
    <select>
    <option value="" disabled selected>Localidad 3</option>
    <option value="">1. Rio Segundo</option>
    <option value="">2. Rio Tercero</option>
    <option value="">3. Rio Cuarto</option>
    <option value="">4. Cordoba Capital</option>
  </select><br>
    <select>
    <option value="" disabled selected>Localidad 4</option>
    <option value="">1. Rio Segundo</option>
    <option value="">2. Rio Tercero</option>
    <option value="">3. Rio Cuarto</option>
    <option value="">4. Cordoba Capital</option>
  </select><br>
  <input type="submit" value="Cargar ruta">
</form> 

<h3>Nuevo Vehiculo</h3>
<form onsubmit="return false">
  <input type="text"  placeholder="Nombre de Localidad"><br>
  <input type="text"  placeholder="Provincia"><br>
  <input type="menu"  placeholder="Pais"><br>
  <input type="text"  placeholder="Codigo Postal"><br>
  <input type="submit" value="Cargar">
</form> 

<h3>Nuevo Chofer</h3>
<form onsubmit="return false">
  <input type="text"  placeholder="Nombre de Localidad"><br>
  <input type="text"  placeholder="Provincia"><br>
  <input type="menu"  placeholder="Pais"><br>
  <input type="text"  placeholder="Codigo Postal"><br>
  <input type="submit" value="Cargar">
</form> 



</body>
</html>