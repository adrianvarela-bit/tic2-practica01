# Diseña tu próximo paso

## Descripción

Página web para comparar tres grados universitarios y conocer sus estudios, requisitos de acceso y posibles salidas profesionales.

Las tres opciones son:

- Ingeniería Informática, en la Universidade da Coruña (UDC).
- Administración y Dirección de Empresas (ADE), en la Universidade da Coruña (UDC).
- Medicina, en la Universidade de Santiago de Compostela (USC).

## Estructura del proyecto

```text
tic2-practica01/
├── css/
│   └── estilos.css
├── evidencias/
├── img/
│   ├── informatica3.png
│   ├── ade3.png
│   └── medicina3.png
├── .gitattributes
├── index.html
├── opciones.html
├── salidas.html
└── README.md
```

## Tecnologías

- HTML5.
- CSS3.
- Bootstrap 5.3.8.
- JavaScript incluido en Bootstrap.
- Git y GitHub.

## Cómo abrir la web

1. Descargar o clonar el repositorio.
2. Abrir el archivo `index.html` en un navegador.
3. Utilizar el menú para visitar las páginas de opciones y salidas.

Es necesaria conexión a Internet para cargar Bootstrap desde su CDN.

## Fuentes oficiales

Información consultada para el curso 2026/2027. Fecha de consulta: 11 de noviembre de 2026.

### Ingeniería Informática (UDC)

- [Información del grado y plan de estudios](https://estudos.udc.es/es/study/detail/614g01v01).
- [Acceso y admisión](https://estudos.udc.es/es/study/admission/614G01V01).

### Administración y Dirección de Empresas (UDC)

- [Información del grado y plan de estudios](https://estudos.udc.es/es/study/detail/611g02v01).
- [Acceso y admisión](https://estudos.udc.es/es/study/admission/611g02v01).

### Medicina (USC)

- [Información del Grado en Medicina](https://www.usc.gal/es/estudios/grados/ciencias-salud/grado-medicina).
- [Admisión en el Sistema Universitario de Galicia (CIUG)](https://www.ciug.gal/admision-sug).

La información sobre plazas, notas de admisión y requisitos puede cambiar en cada convocatoria.

## Imágenes y créditos

| Archivo | Autor y título | Fuente | Licencia | Cambios |
|---|---|---|---|---|
| `informatica3.png` | Imagen generada con ChatGPT (OpenAI): Ingeniería Informática | [ChatGPT](https://chatgpt.com/) | Imagen generada con IA mediante ChatGPT (OpenAI). No se le ha aplicado una licencia Creative Commons. | Recortada del mosaico original para obtener una imagen individual. |
| `ade3.png` | Imagen generada con ChatGPT (OpenAI): Administración y Dirección de Empresas | [ChatGPT](https://chatgpt.com/) | Imagen generada con IA mediante ChatGPT (OpenAI). No se le ha aplicado una licencia Creative Commons. | Recortada del mosaico original para obtener una imagen individual. |
| `medicina3.png` | Imagen generada con ChatGPT (OpenAI): Medicina | [ChatGPT](https://chatgpt.com/) | Imagen generada con IA mediante ChatGPT (OpenAI). No se le ha aplicado una licencia Creative Commons. | Recortada del mosaico original para obtener una imagen individual. |

## Decisiones técnicas

1. Se ha utilizado HTML semántico para organizar el contenido mediante cabecera, navegación, contenido principal y pie de página.
2. Se ha utilizado Bootstrap para crear tarjetas, columnas adaptables, menú desplegable y tabla con desplazamiento horizontal en pantallas pequeñas.
3. Se ha creado una hoja CSS propia para los colores, tamaños, márgenes, bordes, foco visible y ajustes para móviles.

## Pruebas y correcciones

Se revisa la adaptación de la web a pantallas de 390, 768 y 1280 píxeles. También se comprueban el menú móvil, la navegación con teclado, los enlaces, las imágenes y la tabla en pantallas pequeñas.

Se han revisado los tres archivos HTML con [W3C Validator](https://validator.w3.org/) y se han corregido los errores detectados.

Se corrigieron los estilos de los títulos del acordeón de `salidas.html` para mantener su tamaño y color.

Las capturas de las pruebas se guardan en la carpeta `evidencias/`.

## Uso de inteligencia artificial

Se ha utilizado ChatGPT como apoyo para generar las tres imágenes y para revisar y redactar parte del contenido y del código.

## Autor

Adrián Varela Timofte

## Repositorio

[GitHub: tic2-practica01](https://github.com/adrianvarela-bit/tic2-practica01)

## Estado

Terminado.