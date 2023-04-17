Somos fedex o andreani.
Nos llama un cliente nuevo y nos solicita enviar un paquete

REgistramos elcliente
#### Cliente

<table>
  <tr>
    <td>id_cliente</td>
    <td>nombre</td>
    <td>telefono</td>
  </tr>
  <tr>
    <td>1</td>
    <td>Bancor SA</td>
    <td>111111</td>
  </tr>
</table>


#### Viaje

<table>
  <tr>
    <td>id_viaje</td>
    <td>id_set_chof</td>
    <td>id_ruta</td>
    <td>h_partida</td>
    <td>h_llegada</td>
    <td>Vehiculos?</td>
  </tr>
    <td>1</td>
    <td>1</td>
  </tr>
</table>

Elejimos alguna de las rutas (recordemos que son fijas)
#### Rutas

<table>
  <tr>
    <td>id_ruta</td>
    <td>id_set_loc</td>
    <td>durac_est</td>
    <td>id_set_cl</td>
    <td></td>
  </tr>
  <tr>
    <td>1</td>
    <td>1</td>
    <td>3.5</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>2</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
</table>





#### Localidad

<table>
  <tr>
    <td>id_loc</td>
    <td>nombe</td>
    <td>provincia</td>
    <td>pais</td>
    <td>codigo_postal</td>
  </tr>
  <tr>
    <td>1</td>
    <td>Rio Segundo</td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
   <tr>
    <td>2</td>
    <td>Rio Tercero</td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
   <tr>
    <td>3</td>
    <td>Rio Cuarto</td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
</table>


#### Chofer

<table>
  <tr>
    <td>id_chofer</td>
    <td>nombe</td>
    <td>apellido</td>
    <td>dni</td>
    <td>telef</td>
  </tr>
  <tr>
    <td>1</td>
    <td>Juan</td>
    <td>Fernandez</td>
    <td>12345789</td>
    <td>98765432</td>
    
</tr>
</table>



#### Tablas de Nombre Pendiente

<table>
  <tr>
    <td>id_set_loc</td>
    <td>id_loc</td>
    <td>orden</td>
  </tr>
  <tr>
    <td>1</td>
    <td>1</td>
    <td>1</td>
  </tr>
  <tr>
    <td>1</td>
    <td>2</td>
    <td>2</td>
  </tr>
  <tr>
    <td>1</td>
    <td>3</td>
    <td>3</td>
  </tr>
    <tr>
    <td>2</td>
    <td>1</td>
    <td>3</td>
  </tr>
  <tr>
    <td>2</td>
    <td>2</td>
    <td>2</td>
  </tr>
  <tr>
    <td>2</td>
    <td>3</td>
    <td>1</td>
  </tr>
</table>


<table>
  <tr>
    <td>id_set_chof</td>
    <td>id_chof</td>
  </tr>
  <tr>
    <td>1</td>
    <td>1</td>
  </tr>
  <tr>
    <td>1</td>
    <td>2</td>

  </tr>
  <tr>
    <td>1</td>
    <td>3</td>
  </tr>
    <tr>
    <td>2</td>
    <td>4</td>
  </tr>
  <tr>
    <td>2</td>
    <td>5</td>
  </tr>
  <tr>
    <td>2</td>
    <td>6</td>
  </tr>

</table>

<table>
  <tr>
    <td>id_set_chof</td>
    <td>id_chof</td>
  </tr>
  <tr>
    <td>1</td>
    <td>1</td>
  </tr>
  <tr>
    <td>1</td>
    <td>2</td>

  </tr>
  <tr>
    <td>1</td>
    <td>3</td>
  </tr>
    <tr>
    <td>2</td>
    <td>4</td>
  </tr>
  <tr>
    <td>2</td>
    <td>5</td>
  </tr>
  <tr>
    <td>2</td>
    <td>6</td>
  </tr>

</table>