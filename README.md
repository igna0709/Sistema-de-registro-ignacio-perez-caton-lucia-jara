<!DOCTYPE html>
<html lang="es">
<head>
 <meta charset="UTF-8">
 <title>Registro de Socios</title>
</head>
<body bgcolor="#f4f6f9">

 <br><br>

 <center>
  <table width="420" bgcolor="#ffffff" border="1" bordercolor="#cccccc" cellpadding="20" cellspacing="0">
   <tr>
    <td>
     <center>
      <h2><font face="Arial, sans-serif" color="#2c3e50">📋 Registro de Socios</font></h2>
      <p><font face="Arial, sans-serif" size="2" color="#7f8c8d">Complete los datos para dar de alta un nuevo socio</font></p>
     </center>

     <hr color="#eeeeee">
     <br>

     <form id="formulario">
      <fieldset>
       <legend><font face="Arial, sans-serif" size="2" color="#34495e"><b>Datos Personales</b></font></legend>
       <br>

       <table width="100%" border="0" cellpadding="6">
        <tr>
         <td align="right"><label for="nombre"><font face="Arial, sans-serif" size="2"><b>Nombre:</b></font></label></td>
         <td><input type="text" id="nombre" size="25" placeholder="Ej. Juan" required></td>
        </tr>

        <tr>
         <td align="right"><label for="apellido"><font face="Arial, sans-serif" size="2"><b>Apellido:</b></font></label></td>
         <td><input type="text" id="apellido" size="25" placeholder="Ej. Pérez" required></td>
        </tr>

        <tr>
         <td align="right"><label for="documento"><font face="Arial, sans-serif" size="2"><b>Documento:</b></font></label></td>
         <td><input type="text" id="documento" size="25" placeholder="Ej. 12345678" required></td>
        </tr>

        <tr>
         <td align="right"><label for="email"><font face="Arial, sans-serif" size="2"><b>Email:</b></font></label></td>
         <td><input type="email" id="email" size="25" placeholder="correo@ejemplo.com" required></td>
        </tr>

        <tr>
         <td align="right"><label for="telefono"><font face="Arial, sans-serif" size="2"><b>Teléfono:</b></font></label></td>
         <td><input type="tel" id="telefono" size="25" placeholder="Ej. 1123456789" required></td>
        </tr>
       </table>

       <br>
       <center>
        <button type="submit">💾 Guardar Socio</button>
        &nbsp;&nbsp;
        <button type="reset">Limpiar</button>
       </center>
       <br>
      </fieldset>
     </form>

     <center>
      <p><b><font face="Arial, sans-serif" color="#27ae60" id="mensaje"></font></b></p>
     </center>
    </td>
   </tr>
  </table>
 </center>

 <script src="script.js"></script>

</body>
</html>
