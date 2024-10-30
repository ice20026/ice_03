# web-003

<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Formulario de Datos</title>
    <style>
        body {
            background-color: #333; /* Fondo oscuro para contrastar */
            font-family: Arial, sans-serif;
            color: white; /* Color del texto */
        }
        form {
            max-width: 500px;
            margin: auto;
            padding: 20px;
            border: 1px solid #ccc;
            border-radius: 10px;
            background-color: #444; /* Fondo del formulario */
        }
        label, input, textarea {
            display: block;
            width: 100%;
            font-size: 18px; /* Tamaño de letra */
            margin-bottom: 10px;
        }
        input, textarea {
            padding: 10px;
            border: 1px solid #ccc;
            border-radius: 5px;
            background-color: #555; /* Fondo de los campos */
            color: white; /* Color del texto en los campos */
        }
        button {
            font-size: 18px;
            padding: 10px 20px;
            color: white;
            background-color: #007BFF; /* Color del botón */
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        button:hover {
            background-color: #0056b3;
        }
    </style>
</head>
<body>
    <form>
        <label for="name">Nombre:</label>
        <input type="text" id="name" name="name" required>
        <label for="email">Correo Electrónico:</label>
        <input type="email" id="email" name="email" required>
        <label for="message">Mensaje:</label>
        <textarea id="message" name="message" required></textarea>
        <button href="https://ice20026.github.io/web-004/">Enviar</button>
    </form>
</body>
</html>


<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Imagen de Fondo</title>
    <style>
        body {
            background-image: url('fondo n1.jpg'); /* Imagen de fondo */
            background-size: cover; /* Ajusta la imagen para cubrir toda la pantalla */
            background-position: center; /* Centra la imagen */
            background-repeat: no-repeat; /* Evita que la imagen se repita */
            margin: 0;
            font-family: Arial, sans-serif;
        }
    </style>
</head>
<body>
    <h1>¡Hola Mundo!</h1>
    <p>Este es un ejemplo de una página con una imagen de fondo.</p>
</body>
</html>




<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Botón con Hipervínculo</title>
    <style>
        .btn {
            display: inline-block; /* Para que el enlace se comporte como botón */
            font-size: 16px; /* Tamaño del texto */
            padding: 10px 20px; /* Espaciado interno del botón */
            color: white; /* Color del texto */
            background-color: #007BFF; /* Color de fondo */
            border: none; /* Sin borde */
            border-radius: 5px; /* Bordes redondeados */
            cursor: pointer; /* Cambia el cursor al pasar sobre el botón */
            text-align: center; /* Centra el texto */
            text-decoration: none; /* Quita el subrayado del enlace */
            margin: 10px; /* Espacio entre botones */
        }
        .btn:hover {
            background-color: #0056b3; /* Color de fondo al pasar el ratón */
        }
    </style>
</head>
<body>
    <a href="https://ice20026.github.io/web-002/" class="btn">atras</a>
</body>
</html>



