@@ -0,0 +1,74 @@
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Formulario</title>
</head>
<body>
    <form action="" method="POST" name="" id="">
        <label for="Nombre ubicacion">Nombre de ubicacion</label>
        <input type="text" name="nombre ubicacion"id="nombre ubicacion"
        placeholder="          "
        maxlength=""
        minlength=""
        pattern="[A-Za-z]{1-20}"
        required>
        <br>
        <br>
        <br>
        <br>
        <form action="" method="POST" name="" id="">
            <label for="Nombre">Nombre de la persona</label>
            <input type="text" name="nombre"id="nombre"
            placeholder="          "
            maxlength=""
            minlength=""
            pattern="[A-Za-z]{1-20}"
            required>
            <br>
            <br>
            <br>
            <br>
            <label for="telefono">numero de telefono</label>
                <input type="tel" name="telefono"id="telefono"
                placeholder="0000-0000"
                maxlength="9"
                minlength="9"
                pattern="[0-9]{4}-[0-9]{4}"
                required>
                <br>
                <br>
                <br>
                <br> 
                <label for="email">Correo electronico:<label>
                    <input type="email" name="email" id="email"
                    pattern="[a-z0-9._%+-]+@[a-z0-9.-]+\.[a-z]{2,4}$"
                required>
                <br>
                <br>
                <br>
                <br>
                <br>
                <label for="Fecha">Fecha de recepcion</label>
                <input type="date" name="Fecha"id="Fecha"
                 value="2020-01-01"
                 min="1970-01-01"
                max="2025-01-01"
                required>
                    <br>
                    <br>
                    <br>
                    <br>
    <input type="submit" value="Enviar">
<br>
<br>
<br>
<br>


        <h2>Ubicacion de recepcion</h2> 
        <iframe src="https://www.google.com/maps/embed?pb=!1m14!1m12!1m3!1d2778.371803394531!2d-84.1254482101497!3d9.999415245277726!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!5e0!3m2!1ses!2scr!4v1665103019927!5m2!1ses!2scr" width="400" height="300" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>       
</body>
</html>
