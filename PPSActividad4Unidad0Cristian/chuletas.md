# Título Principal

Este es un ejemplo de **Markdown** para que lo uses y modifiques según tus necesidades. Markdown es fácil de aprender y muy útil para escribir documentos que se pueden ver en texto plano y formato HTML.

---

## Sección 1: Listas

### Lista Desordenada
- Elemento 1
- Elemento 2
  - Subelemento 2.1
  - Subelemento 2.2
- Elemento 3

### Lista Ordenada
1. Primer elemento
2. Segundo elemento
3. Tercer elemento


### Ejemplo de un índice
1. [Introducción](#introducción)
2. [Instalación y configuración de Git y PHP](./Install.md#instalacion-y-configuracion-de-git-y-php)
   - [Instalación de Git](./Install.md#1-instalación-de-git)
   - [Instalación de PHP](./Install.md#2-instalación-de-php)
   - [Configuración inicial de Git](./Install.md#3-configuración-inicial-de-git)
   - [Resultados, Ejemplos y Capturas de pantalla](./Install.md#4-resultados-ejemplos-y-capturas-de-pantalla)
  
3. [Comandos principales de Git](./UsoGit.md#Comandos-principales-de-Git)
   - [Funciones y comandos básicos de GitHub](./UsoGit.md#Funciones-Básicas-de-GitHub)
      - [Crear un Repositorio](./UsoGit.md#)
      - [Clonar un Repositorio](./UsoGit.md#-1)
      - [Subir Archivos a un Repositorio](./UsoGit.md#-2)
      - [Crear y Gestionar Issues](./UsoGit.md#-3)
      - [Crear un Pull Request](./UsoGit.md#-4)
      - [Revisar y Aceptar Pull Requests](./UsoGit.md#-5)
   - [Ejemplos prácticos y capturas](./UsoGit.md#resultados,-ejemplos-y-capturas-de-pantalla)

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
----------------------------------------------------------------------------------------

## Sección 2: Enlaces e Imágenes

Puedes agregar enlaces usando este formato:

`[Enlace a OpenAI](https://www.openai.com)`

Para imágenes, usa una sintaxis similar:

`![Ejemplo de Imagen](https://via.placeholder.com/150)`

Para imagenes con estilo centrado y tener una leyenda de imagen centrada y en cursiva:
```
<p align="center">
  <img src="./images/Realizar%20cambios%20en%20repositorio%20local%20y%20actualizarlo.png" alt="Realizar cambios en repositorio local, actualizarlo y realizar pull requests">
</p>
<p align="center"><em>Imagen 1: Clonar repositorio</em></p>
```

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
----------------------------------------------------------------------------------------

## Sección 3: Código

### Código en Línea
Para resaltar código en una línea, usa backticks, por ejemplo: `print("Hola, Mundo!")`.

### Bloque de Código

Para bloques de código más largos, utiliza tres backticks y el nombre del lenguaje:

```python
def saludo():
    nombre = input("¿Cómo te llamas? ")
    print(f"Hola, {nombre}!")

saludo()
```

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
----------------------------------------------------------------------------------------

## Sección 4: Citas y Tablas

### Cita
> Esto es un bloque de cita. Úsalo para resaltar alguna información importante.

### Tabla
Puedes crear tablas para organizar información de manera clara:

Tabla simple con alineación de texto

| Nombre     | Edad | Ciudad          |
|:-----------|:----:|----------------:|
| Ana        |  25  | Madrid          |
| José       |  30  | Buenos Aires    |
| Luisa      |  28  | Ciudad de México|
---
Tabla con múltiples líneas (Markdown extendido)

| Nombre     | Detalles                   |
|------------|----------------------------|
| Ana        | Edad: 25  
|            | Ciudad: Madrid  
| José       | Edad: 30  
|            | Ciudad: Buenos Aires  
| Luisa      | Edad: 28  
|            | Ciudad: Ciudad de México  
---
Tablas sin bordes (usando Markdown y HTML):
<table>
  <tr>
    <td><strong>Nombre</strong></td>
    <td><strong>Edad</strong></td>
    <td><strong>Ciudad</strong></td>
  </tr>
  <tr>
    <td>Ana</td>
    <td>25</td>
    <td>Madrid</td>
  </tr>
  <tr>
    <td>José</td>
    <td>30</td>
    <td>Buenos Aires</td>
  </tr>
  <tr>
    <td>Luisa</td>
    <td>28</td>
    <td>Ciudad de México</td>
  </tr>
</table>

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
----------------------------------------------------------------------------------------

## Sección 5: Tareas

- [x] Elemento completado
- [ ] Elemento pendiente
- [ ] Otro elemento pendiente

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
----------------------------------------------------------------------------------------

## Sección 6: Formas de Crear Notas y Destacar Texto

    Bloques de cita para notas

    Markdown no tiene un bloque de "nota" dedicado, pero puedes usar bloques de citas (>) para emularlo.

> **Nota**: Este es un bloque de nota para destacar información importante.

Etiquetas de advertencia, información o éxito

Algunas implementaciones (como GitHub) permiten un estilo específico de citas con emojis para resaltar notas. Ejemplos:

> ⚠️ **Advertencia**: Esta es una advertencia sobre un posible problema.
> 
> 💡 **Información**: Aquí tienes información adicional que puede ser útil.
> 
> ✅ **Éxito**: Este paso se completó correctamente.

Notas con HTML y estilos personalizados

Puedes utilizar HTML para lograr una apariencia específica. Esto es especialmente útil si necesitas notas de diferentes colores.

<div style="background-color:#FFEB3B; padding:10px; border-radius:5px;">
<strong>Nota:</strong> Este es un bloque de nota con fondo amarillo.
</div>

Divisores de sección para notas con separación

Otra técnica simple es usar líneas divisorias para hacer una sección especial para notas:

---
**Nota importante**: Recuerda guardar tu trabajo frecuentemente.
---

Uso de HTML para notas con iconos y estilos avanzados

En entornos que lo permitan, puedes incluir un icono al inicio de la nota:

    <p><strong>📝 Nota:</strong> Este es un bloque de nota con un icono de anotación.</p>
<p><strong>📝 Nota:</strong> Este es un bloque de nota con un icono de anotación.</p>

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
----------------------------------------------------------------------------------------

## Sección 7: Esquema de ejemplo de estructura de un repositorio
  ```bash
   PPSActividad3Unidad0TuNombre/
   │
   ├── README.md                  # Archivo principal con introducción y enlaces a secciones y archivos relevantes.
   │
   ├── install.md                 # Documento explicando la instalación y configuración de Git y PHP.
   │
   ├── UsoGit.md                  # Archivo que describe los comandos principales utilizados en Git.
   │
   ├── GitHub.md                  # Explicación sobre la creación de una cuenta, login y uso básico de GitHub.
   │
   ├── images/                    # Carpeta que contiene todas las imágenes utilizadas en los archivos .md.
   │   ├── DescargarGit.png
   │   ├── DescargarPHP.png
   │   ├── ClonarRepositorio.png
   │   └── ... (otras imágenes)
