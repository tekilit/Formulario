<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Formulario tercera edad</title>
</head>
<style></style>
<body>
    <h1>Club Viejuner (formulario)</h1>
    <h2>Tú:</h2>
    <label for="first-name">Nombre</label><br />
    <input type="text" name="first-name" id="first-name" placeholder="Pepe" required/>
​<br />
​
    <label for="surname">¿Cuál es tu apellido?</label><br />
    <input type="text" name="surname" id="surname" placeholder="Botella" required/>
​<br />

    <label for="Edad">¿Qué edad tienes?</label> <br>
    <input type="number" name="edad" id="Edad" required>

    <br>

    <legend>¿De que sexo eres?</legend>
        <input type="radio" id="Mujer" name="sexo" value="Mujer">
        <label for="Mujer">Soy Mujer </label>
 <br>
        <input type="radio" id="Hombre" name="sexo" value="Hombre">
        <label for="Hombre">Soy Hombre </label>
        <br>

        <p>¿Te sientes Viejuner?</p>
        <input type=checkbox id="Viejuner" name="Viejuner"></input>
        <br>
        <label for="description">Escribe algo sobre ti</label><br />
      <textarea
        name="description"
        id="description"
        rows="10"
        cols="50"
      ></textarea>
​
    <h2>Tus circunstacias:</h2>

    <form action="/action_page.php" autocomplete="on"></form>
       
        <label for="email">Email:</label>
        <input type="text" id="email" name="email"><br><br>
        <label for="Telefono">Telefono:</label>
        <input type="tel" id="telefono" name="telefono"><br><br>
        <input type="submit">
      </form>
      <br />

    
    
</body>
</html># formulario
