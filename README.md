<!DOCTYPE html>
<html>
<head>
 <title>Registro de Socios</title>
</head>
<body>

 <div align="center">
  <h2>Registro de Socios</h2>

  <form id="formulario">
   <label>Nombre:</label><br>
   <input type="text" id="nombre" required><br><br>

   <label>Apellido:</label><br>
   <input type="text" id="apellido" required><br><br>

   <label>Documento:</label><br>
   <input type="text" id="documento" required><br><br>

   <label>Email:</label><br>
   <input type="email" id="email" required><br><br>

   <label>Teléfono:</label><br>
   <input type="text" id="telefono" required><br><br>

   <button type="submit">Guardar Socio</button>
  </form>

  <p id="mensaje"></p>
 </div>

 <script src="script.js"></script>

</body>
</html>

