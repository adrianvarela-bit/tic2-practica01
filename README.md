# Mi proyecto TIC II

**Diseña tu próximo paso**

## Descripción

Web de tres páginas para comparar tres grados universitarios: Ingeniería Informática y ADE en la UDC, y Medicina en la USC.

Incluye una portada con tarjetas, una tabla comparativa y una página con salidas profesionales y una conclusión.

## Tecnologías

- **HTML5:** estructura de las páginas.
- **CSS3:** diseño propio en `css/estilos.css`.
- **Bootstrap 5.3.8:** usado para las tarjetas, el menú y el diseño adaptable. Se carga desde jsDelivr, por lo que necesita Internet.
- **Git y GitHub:** para guardar los cambios y subir el proyecto.

Bootstrap aporta componentes y herramientas de diseño. El contenido HTML y los estilos propios los he hecho para este proyecto.

## Estructura y cómo abrirlo

```text
tic2-practica01/
├── index.html
├── opciones.html
├── salidas.html
├── README.md
├── css/
│   └── estilos.css
├── img/
└── evidencias/
```

Para abrir la web, basta con abrir `index.html` en un navegador. Hace falta Internet para cargar Bootstrap.

**Repositorio:** https://github.com/adrianvarela-bit/tic2-practica01

## Fuentes oficiales

**Ingeniería Informática — UDC**

1. [Información del grado](https://estudos.udc.es/es/study/detail/614G01V01)
2. [Acceso y admisión](https://estudos.udc.es/es/study/admission/614G01V01)

**Medicina — USC**

3. [Información del grado](https://www.usc.gal/es/estudios/grados/ciencias-salud/grado-medicina)
4. [Plan de estudios — BOE](https://www.boe.es/buscar/doc.php?id=BOE-A-2026-4510)

**ADE — UDC**

5. [Información del grado](https://estudos.udc.es/es/study/detail/611G02V01)
6. [Acceso y admisión](https://estudos.udc.es/es/study/admission/611G02V01)

**Fecha de consulta:** 11/11/2026.

## Créditos de las imágenes

Completar los datos con la información de la página original de cada imagen.

| Archivo | Autor y título | Fuente | Licencia | Cambios |
|---|---|---|---|---|
| `informatica.png` | [Autor y título] | [Enlace] | [Licencia] | [Cambios] |
| `ade2.png` | [Autor y título] | [Enlace] | [Licencia] | [Cambios] |
| `medicina.png` | [Autor y título] | [Enlace] | [Licencia] | [Cambios] |
| `fondooscuro.gif` | [Autor y título] | [Enlace] | [Licencia] | [Cambios] |

## Decisiones técnicas

- **HTML:** he separado la web en tres páginas y organizado la información con títulos, enlaces, tarjetas y una tabla.
- **CSS:** he creado una hoja propia para cambiar colores, tamaños, márgenes y otros detalles. También he añadido foco visible para el teclado y ajustes para móviles.
- **Bootstrap:** he usado su retícula, tarjetas, botones, menú desplegable y acordeones para adaptar la web a distintas pantallas.

## Pruebas y error corregido

He revisado las tres páginas en 390, 768 y 1280 píxeles. También hay que comprobar el menú, los enlaces, las imágenes, el teclado y que la tabla se desplace dentro de su espacio en móvil.

Las capturas se guardan en `evidencias/`: portada en los tres tamaños y tabla en móvil. También se revisa el HTML con el [validador W3C](https://validator.w3.org/).

**Error corregido:** [Indicar un error real que se haya encontrado y solucionado].

## Autor

Adrián Varela Timofte.

## Estado

Terminado.