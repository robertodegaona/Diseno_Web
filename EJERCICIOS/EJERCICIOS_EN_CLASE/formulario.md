![image](https://user-images.githubusercontent.com/91554777/170103427-2b681a6e-05b6-49f3-834b-c188ebf12fbb.png)





    <!DOCTYPE html>
    <html lang="en">
    <head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>formulario</title>
    </head>
    <body>
       <h3>Formato de registro</h3>
       <form action="" >
        <fieldset style="width: 500px;">
        <legend>Informacion personal del usuario </legend>
        <p> Introduce tu nombre completo <br>
            <input type="text" name="nombre"></p>
        <p> Introduce tu email <br>
            <input type="email" name="email"></p>
        <p> Introduce tu contraseña <br>
            <input type="password" name="password"></p>
        <p> Confirma tu contraseña <br>
            <input type="password" name="password"></p>
        <p> Género <br>
            <input type="radio" name="genero" value="male">Masculino<br>
            <input type="radio" name="genero" value="female">Femenino<br>
            <input type="radio" name="genero" value="other">Otro </p>
        <p> Introduce tu dirección <br>
            <textarea rows="4" cols="30"></textarea><br>
            <input type="submit" value="Registrarse">


        </p>    
    </fieldset>
    </form>
    </body>
    </html>
