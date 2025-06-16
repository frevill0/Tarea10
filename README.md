# Informe: Uso de Git y GitHub en Proyecto Web

## 📌 Introducción

El control de versiones con Git y su integración con GitHub permiten gestionar eficientemente el desarrollo de proyectos, especialmente cuando se trabaja en equipo. Este informe documenta el proceso paso a paso de creación de un repositorio local, manejo de ramas, confirmación de cambios, y sincronización con GitHub en el contexto de un proyecto web sencillo.

## 🎯 Objetivo

Explicar y documentar el proceso completo de creación y gestión de un repositorio Git desde cero, incluyendo la creación de un archivo HTML básico, la gestión de ramas y la publicación en GitHub, promoviendo la organización del código y la colaboración.

## ⚙️ Desarrollo

### 1. Crear un nuevo directorio en su ordenador

Se crea un directorio donde se almacenarán los archivos del proyecto:

```bash
mkdir mi_pagina_web
cd mi_pagina_web
```

### 2. Inicializar un repositorio local en el directorio

Se inicializa Git en el directorio:

```bash
git init
```

### 3. Crear un archivo básico `index.html`

Se crea el archivo con el siguiente contenido:

```html
<!DOCTYPE html>
<html>
<head>
    <title>Mi Página Web</title>
</head>
<body>
    <h1>Bienvenido a mi sitio</h1>
</body>
</html>
```

### 4. Agregar el documento y hacer commit

```bash
git add index.html
git commit -m "Inicialización del proyecto con index.html"
```

### 5. Crear una rama llamada `NuevaSeccion`

```bash
git branch NuevaSeccion
git switch NuevaSeccion
```

### 6. Agregar sección "Sobre Nosotros" a `index.html`

```html
<section>
    <h2>Sobre Nosotros</h2>
    <p>Somos un equipo apasionado por la tecnología.</p>
</section>
```

### 7. Guardar y confirmar cambios

```bash
git add index.html
git commit -m "Agregada sección Sobre Nosotros"
```

### 8. Subir repositorio a GitHub

1. Crear repositorio **público** en GitHub.
2. Agregar origen remoto:

```bash
git remote add origin https://github.com/usuario/mi_pagina_web.git
git push -u origin NuevaSeccion
```

### 9. Invitar a un colaborador

En GitHub:
- Ir a **Settings > Collaborators**
- Añadir el nombre de usuario del compañero
- Enviar la invitación

### 10. Incluir URL del repositorio

📎 [https://github.com/usuario/mi_pagina_web](https://github.com/usuario/mi_pagina_web)  
*(Reemplazar con tu URL real)*

## ✅ Conclusión y Recomendación

El uso de Git y GitHub facilita significativamente el control de versiones, la organización del código y el trabajo colaborativo en proyectos de desarrollo. A través de este ejercicio práctico se aprendió a inicializar un repositorio, gestionar ramas, realizar commits y publicar el trabajo en un entorno remoto. Se recomienda aplicar esta metodología en todos los proyectos, manteniendo buenas prácticas como el uso de ramas para nuevas funcionalidades, commits descriptivos y respaldo constante en GitHub para asegurar la trazabilidad y la colaboración efectiva.

---

## 📄 README del Proyecto

# Proyecto: Mi Página Web

Este repositorio contiene un proyecto básico de una página web desarrollado como práctica para aprender a usar Git y GitHub de manera estructurada, aplicando control de versiones, ramas y colaboración remota.

## 📁 Paso 1: Crear un nuevo directorio

```bash
mkdir mi_pagina_web
cd mi_pagina_web
```

## 🧱 Paso 2: Inicializar un repositorio Git

```bash
git init
```

## 📝 Paso 3: Crear archivo index.html

```html
<!DOCTYPE html>
<html>
<head>
    <title>Mi Página Web</title>
</head>
<body>
    <h1>Bienvenido a mi sitio</h1>
</body>
</html>
```

## 📌 Paso 4: Agregar archivo al repositorio y hacer commit

```bash
git add index.html
git commit -m "Inicialización del proyecto con index.html"
```

## 🌿 Paso 5: Crear una nueva rama llamada `NuevaSeccion`

```bash
git branch NuevaSeccion
git switch NuevaSeccion
```

## 🧩 Paso 6: Agregar sección “Sobre Nosotros”

```html
<section>
    <h2>Sobre Nosotros</h2>
    <p>Somos un equipo apasionado por la tecnología.</p>
</section>
```

## 💾 Paso 7: Guardar los cambios y hacer commit

```bash
git add index.html
git commit -m "Agregada sección Sobre Nosotros"
```

## 🌐 Paso 8: Subir el repositorio a GitHub

```bash
git remote add origin https://github.com/usuario/mi_pagina_web.git
git push -u origin NuevaSeccion
```

## 👥 Paso 9: Agregar colaborador

Desde GitHub: Settings > Collaborators > Añadir usuario > Enviar invitación

## 🔗 Paso 10: URL del repositorio

[https://github.com/usuario/mi_pagina_web](https://github.com/usuario/mi_pagina_web)
