# Mi-formulario
es un formulario para acceder a una cuenta y puedas  agregar tus datos personales


    <!DOCTYPE html>
<head>
    
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Formulario</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.8/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-sRIl4kxILFvY47J16cr9ZwB07vP4J8+LH7qKQnuqkuIAvNWLzeN8tE5YBujZqJLB" crossorigin="anonymous">
</head>
<body>
    <main class="container">
        <section>
            <form action="#">
                  <h1 class="text-center">Crea una cuenta</h1>
            </form>
        </section>
    </main>

    <div class="col-6 mb-3">
                    <label for="nombre" class="form-label">Nombre</label>
                    <input type="text" class="form-control" id="nombre" placeholder="escribe tu nombre">
                </div>

    <div class=" col-6 mb-3">
                    <label for="apllido" class="form-label">Apellido</label>
                    <input type="text" class="form-control" id="apellido" placeholder="escribe tu apellido">
                </div>

    <div class="col-4 mb-3">
                    <label for="fecha" class="form-label">Dia de nacimiento</label>
                    <input type="number" class="form-control" id="fecha" placeholder="dia">
                </div>

    <div class="col-4 mb-3">
                    <label for="mes" class="form-label">Mes de nacimiento</label>
                    <input type="text" class="form-control" id="mes" placeholder="mes">
                </div>

    <div class="col-4 mb-3">
                    <label for="año" class="form-label">Año de nacimiento</label>
                    <input type="number" class="form-control" id="fecha" placeholder="año">
                </div>
    <div class="col-4 mb-3">
                    <label for="genero" class="form-label">Genero</label>
                    <input type="text" class="form-control" id="Genero" placeholder="indique su genero">
                </div>

    <div class="col-4 mb-3">
                <label for="email" class="form-label">correo electronico</label>
                <input type="email-number" class="form-control" id="email"
                    placeholder="introdusca su correo elctronico o numero de telefono">
            </div>

    <div class="col-4 mb-3">
                <label for="password" class="form-label">Contraseña</label>
                <input type="password-number-tex" class="form-control" id="contraseña"
                    placeholder="introdusca su contraseña">
            </div>

        


    
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.8/dist/js/bootstrap.bundle.min.js" integrity="sha384-FKyoEForCGlyvwx9Hj09JcYn3nv7wiPVlz7YYwJrWVcXK/BmnVDxM+D2scQbITxI" crossorigin="anonymous"></script>
</body>
</html>
