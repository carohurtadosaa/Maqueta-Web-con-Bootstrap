# 🧩 Desafío Maqueta Web con Bootstrap (Versión Cliente Exigente)

## 📌 Instrucciones Generales

Tu equipo ha sido asignado para construir una **sección específica** de una maqueta web. Esta maqueta **NO FUNCIONARÁ** si no respetas al pie de la letra los siguientes puntos:

1. **NO CAMBIES LOS NOMBRES DE LOS ARCHIVOS**: Si tu sección se llama `login.html`, ese es el nombre exacto que debes usar.
2. **NO MODIFIQUES EL NAVBAR NI EL FOOTER**: Solo debes preocuparte del **contenido central de tu sección**, como si fueras un diseñador contratado por un cliente con requerimientos estrictos.
3. **NO USES JS PERSONALIZADO**: Usa solamente el JavaScript incorporado en Bootstrap si lo necesitas.
4. Todo se ensamblará en un archivo `index.html`, el cual ya tiene definidos el **navbar**, el **footer**, y el **espacio central** para insertar cada una de las secciones.

---

## 🧱 Estructura base (la ve el grupo 1 y se replica en todos los archivos)

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Grupo X - Sección</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.7/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>

  <!-- AQUI VA EL CONTENIDO DE TU SECCIÓN -->

</body>
</html>
```

---

## 🔗 Navbar (NO MODIFICABLE)

Todos los archivos usan el mismo `navbar`. Debe tener los siguientes enlaces en este orden y con **estos nombres exactos**:

```html
<nav class="navbar navbar-expand-lg navbar-dark bg-dark">
  <div class="container">
    <a class="navbar-brand" href="#">MaquetaWeb</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav ms-auto">
        <li class="nav-item"><a class="nav-link" href="login.html">Login</a></li>
        <li class="nav-item"><a class="nav-link" href="register.html">Register</a></li>
        <li class="nav-item"><a class="nav-link" href="sesion1.html">Sesión 1</a></li>
        <li class="nav-item"><a class="nav-link" href="sesion2.html">Sesión 2</a></li>
        <li class="nav-item"><a class="nav-link" href="sesion3.html">Sesión 3</a></li>
        <li class="nav-item"><a class="nav-link" href="sesion4.html">Sesión 4</a></li>
      </ul>
    </div>
  </div>
</nav>
```

---

## 📥 Footer (NO MODIFICABLE)

```html
<footer class="bg-dark text-white text-center py-3">
  Todos los derechos reservados - 2025
</footer>
```

---

## ✅ Requerimientos por Grupo

### 👥 Grupo 1 – `index.html` (Página principal)

- Sección principal con bienvenida.
- Encabezado con título grande y subtítulo.
- Imagen de fondo o decorativa estilo “landing”.
- Tema de colores: **Primario (`bg-primary`), blanco y gris claro (`bg-light`)**.
- Solo deben insertar los contenidos del resto de los grupos dentro del `body`.


### 👥 Grupo 2 – `login.html`

- Formulario de inicio de sesión con campos:
  - Email
  - Contraseña
  - Checkbox "Recordarme"
- Fondo con clase `bg-light`, borde redondeado y sombra (`shadow`).
- Tema de colores: **gris claro (`bg-light`) y azul (`btn-primary`)**.
- Incluir ícono decorativo relacionado al acceso.

#### Email:

<div class="mb-3">
  <label for="inputEmail" class="form-label">Correo electrónico</label>
  <input type="email" class="form-control" id="inputEmail" placeholder="nombre@ejemplo.com" required>
</div>


#### Contraseña:

<div class="mb-3">
  <label for="inputPassword" class="form-label">Contraseña</label>
  <input type="password" class="form-control" id="inputPassword" placeholder="••••••••" required>
</div>


#### Checkbox "Recodarme":

<div class="form-check mb-3">
  <input class="form-check-input" type="checkbox" id="rememberMe">
  <label class="form-check-label" for="rememberMe">
    Recordarme
  </label>
</div>

#### Fondo con clase `bg-light`, borde redondeado y sombra (`shadow`):

<div class="bg-light p-5 rounded shadow" style="width: 100%; max-width: 400px;">

#### Tema de colores: **gris claro (`bg-light`) y azul (`btn-primary`)**:

<button type="submit" class="btn btn-primary">Ingresar</button>

#### Incluir ícono decorativo relacionado al acceso:

<i class="bi bi-person-circle fs-1 text-primary"></i>

---

### 👥 Grupo 3 – `register.html`

- Formulario de registro:
  - Nombre completo
  - Email
  - Contraseña
  - Repetir contraseña
  - Checkbox de aceptación de términos
- Estilo profesional: usa `card`, `mb-3`, `form-control`.
- Tema de colores: **verde (`btn-success`) y blanco**.
- Puedes agregar íconos relacionados a creación de cuenta.

---

### 👥 Grupo 4 – `sesion1.html` (Introducción)

- Contenido educativo dividido en 3 tarjetas:
  - ¿Qué es HTML?
  - ¿Qué es CSS?
  - ¿Qué es Bootstrap?
- Cada tarjeta debe tener botón “Leer más”.
- Tema de colores: **azul (`btn-outline-primary`) y blanco**.

---

### 👥 Grupo 5 – `sesion2.html` (Galería de proyectos)

- Tres tarjetas con imagen, título y descripción.
- Imágenes libres de proyectos ficticios.
- Cada tarjeta en columna (`col-12 col-md-4`) y dentro de `container`.
- Tema de colores: **neutro con acento en azul**.

---

### 👥 Grupo 6 – `sesion3.html` (Tabla de participantes)

- Tabla con tres columnas:
  - Nombre
  - Correo
  - Rol
- Usa clases `table table-striped`.
- Fondo blanco y container con márgenes (`mt-4`).
- Tema de colores: **gris (`table-secondary`) y blanco**.

---

### 👥 Grupo 7 – `sesion4.html` (Formulario de contacto)

- Formulario con:
  - Nombre
  - Correo
  - Mensaje (textarea)
- Fondo gris claro (`bg-light`), bordes redondeados.
- Botón principal (`btn-primary`).
- Tema visual: **formal, con layout centrado y balanceado**.

---

## ⚠️ Advertencia Final

**Si cambias los nombres de los archivos o enlaces del navbar, el proyecto no funcionará.**  
Estas instrucciones simulan una entrega real para un cliente que **no acepta cambios arbitrarios**.

Tu misión es cumplir exactamente con lo solicitado. ¡Buena suerte! 💼