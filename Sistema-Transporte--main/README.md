# Sistema de transporte

Proyecto de **Análisis y Diseño de Sistemas**: análisis y diseño de un sistema de información para la gestión de rutas, vehículos, choferes y venta de boletos, con el paradigma Estructurado y el Orientado a Objetos (UML).

Sitio publicado: `https://TU-USUARIO.github.io/NOMBRE-DEL-REPOSITORIO/` (completar cuando se active GitHub Pages).

## ¿Quién edita qué?

Cada página es un archivo distinto, así que cada integrante puede trabajar en el suyo sin pisar a los demás. Completen la columna **Responsable**.

| Archivo | Contenido | Responsable |
|---|---|---|
| `index.html` | Inicio y tabla de avance | |
| `marco-teorico.html` | Parte I: introducción, planteamiento, objetivos, método, cronograma | |
| `analisis-estructurado.html` | Modelo ambiental, DFD nivel 0 y explosión de los 4 procesos | |
| `diccionario-datos.html` | Diccionario de datos | |
| `especificaciones-procesos.html` | Especificaciones de procesos (español estructurado) | |
| `modelo-datos.html` | Modelo entidad-relación de D1 y D2 | |
| `analisis-objetos.html` | Parte III: diagramas UML | |
| `boleteria.html` | Programa de boletería (enlace y capturas) | |
| `contacto.html` | Datos del equipo (cada integrante completa su fila) | |
| `css/estilos.css` | Estilos de todo el sitio | Acordar antes de tocar |
| `img/` | Diagramas e imágenes | Quien cambie un diagrama |

## Cómo editar una página desde GitHub

1. Entra al repositorio y abre tu archivo (por ejemplo `marco-teorico.html`).
2. Haz clic en el **lápiz** (Edit this file).
3. Cambia solo el texto que está dentro de `<section> ... </section>`. No borres las etiquetas (`<p>`, `<h2>`, `<li>`...); el texto va entre ellas.
4. Abajo, escribe un mensaje corto que diga qué cambiaste (por ejemplo, "Agrego objetivos específicos") y pulsa **Commit changes**.
5. Espera uno o dos minutos y recarga el sitio con Ctrl + F5.

Atajo: dentro del repositorio, presiona la tecla **`.`** (punto) y se abre un editor completo en el navegador.

Si GitHub avisa que el archivo cambió mientras lo editabas, copia tu texto, recarga la página, y vuelve a pegarlo.

## Reglas del grupo

- Cada uno edita solo sus archivos. Si necesitas cambiar el de otro, avísale.
- Abre el archivo justo antes de editarlo para trabajar sobre la última versión.
- Para cambios grandes, elige **Create a new branch and start a pull request** al guardar y pide que un compañero lo revise.
- Las imágenes van en la carpeta `img/`, con nombres en minúsculas y sin espacios. Para reemplazar un diagrama, sube el nuevo con **el mismo nombre**.
- La cabecera con las pestañas está repetida en todas las páginas. Si se agrega o cambia una pestaña, hay que cambiarla en todas.

## Fragmentos para copiar

Figura con leyenda:

```html
<figure><div class="fig"><img src="img/nombre.png" alt="Descripción de la imagen"></div><figcaption>Figura 1. Título. Fuente: elaboración propia.</figcaption></figure>
```

Aviso de "en construcción":

```html
<div class="todo"><b>En construcción</b><p>Texto del aviso.</p></div>
```

Tabla:

```html
<div class="scroll"><table>
<tr><th>Columna 1</th><th>Columna 2</th></tr>
<tr><td>Dato</td><td>Dato</td></tr>
</table></div>
```

## Agregar a los compañeros

En el repositorio: **Settings → Collaborators → Add people**, y escribe el usuario de GitHub de cada uno. Ellos aceptan la invitación desde su correo.

## Publicar con GitHub Pages

**Settings → Pages → Build and deployment → Deploy from a branch**, rama `main`, carpeta `/ (root)`, y **Save**. El repositorio debe ser público.
