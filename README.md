TP3 Individual - Portfolio
Martinez Agustin
Computacion III - Catedra Wischñevsky - UNLa - 2do cuatrimestre 2026

Para este trabajo pase mi CV del TP1 a un portfolio. Primero arme la maqueta en Figma y despues la traduje a HTML y CSS. Son 6 paginas (index, contacto, hobbies, dibujos, rugby y trabajos) y todas usan una sola hoja de estilos (estilo.css).

Tamaño de pantalla en la que trabaje: 1920 x 1080 px (tambien lo adapte para celular)
Editor de codigo: Visual Studio Code
Figma: https://www.figma.com/design/sOJzRuDerqyaFHJcE7k5ap/tp3-individual-portfolio-martinez-agustin

Tipografias: Annie Use Your Telescope (titulos) y Amaranth (textos)
Colores: Rojo (#E34625), Beige (#EEE8D8) y Negro (#181413)
Los fondos tienen una trama de "0" que hice en Illustrator (img/trama.svg)


Encabezado (header) - se repite en todas las paginas
Menu de navegacion (nav)
(Caja contenedora del fondo de color Rojo, con sombra abajo)
- Logo AM (img)
(Alineado a la Izquierda, de 70px por 70px, lleva al index)
- Lista de iconos (ul)
(Alineado a la Derecha, en fila)
-- Contacto (a)
-- Hobbies (a)
-- Trabajos (a)
(Iconos de 50px por 50px de color Negro. Al pasar el mouse el icono se rellena y aparece el nombre al lado, con tipografia Annie Use Your Telescope, de color Negro)

Pie de Pagina (footer) - se repite en todas las paginas
(Caja contenedora del fondo de color Negro)
- Texto (ul)
-- Diseñado por Martinez Agustin | Copyright © 2026 Portfolio academico (p)
-- UNLa - 2do cuatrimestre 2026 Computacion III - Catedra Wischñevsky (p)
(Alineado a la Izquierda, con tipografia Amaranth Regular, de color Beige)
- Redes (ul)
-- Instagram (a)
-- LinkedIn (a)
(Alineado a la Derecha, en fila, iconos de 70px por 70px)


INDEX (index.html)

Portada (section)
(Caja contenedora del fondo de color Beige con la trama, ocupa toda la pantalla)
- Agustin Martinez (h1)
(Alineado a la Izquierda, la A y la M son imagenes de mis iniciales y el resto con tipografia Annie Use Your Telescope, de color Negro)
- Saludo (p)
(Alineado a la Derecha del nombre, con tipografia Amaranth Regular, de color Negro)
- Portfolio (a)
(Centrado, con tipografia Annie Use Your Telescope, de color Negro, con una flecha que lleva al curriculum)

Animacion de la portada:
Cuando entras se asoma un lapiz abajo de la M. Al hacerle click el lapiz se mete en la M, la sube hasta la A y se forma el logo, que vuela hasta la barra de arriba. Despues se van los textos y aparece "Portfolio". Esta hecho solo con CSS, usando un checkbox escondido con :checked, @keyframes y animation-delay.

Curriculum (section)
(Caja contenedora del fondo de color Beige con la trama)
- Sobre mi (article)
(Pegado a la Izquierda)
- Estudios (article)
(Pegado a la Derecha)
- Programas que manejo (article)
(Pegado a la Izquierda, los logos en fila: Illustrator, Photoshop, InDesign, Figma, Visual Studio Code y HTML5)
- Aptitudes (article)
(Pegado a la Izquierda)
- Idiomas (article)
(Pegado a la Derecha)
(Todas son cajas de color Rojo con bordes redondeados y sombra. Los titulos (h2) con tipografia Annie Use Your Telescope y los textos (p) con tipografia Amaranth Regular, todo de color Beige)


CONTACTO (paginas/contacto.html)

Contenido (main)
(Caja contenedora del fondo de color Rojo con la trama)
- Contacto (h1)
(Alineado a la Izquierda, con tipografia Annie Use Your Telescope, de color Negro)
- Trabajemos juntos!! (p)
(Alineado a la Izquierda, con tipografia Amaranth Bold, de color Negro)
- Texto (p)
(Alineado a la Izquierda, con tipografia Amaranth Regular, de color Negro)
- Formulario (form)
(Alineado a la Derecha, caja de color Beige con bordes redondeados y sombra)
-- Nombre y Apellido (input text)
-- Email (input email)
-- Numero (input tel)
-- Cargar Archivo (input file)
-- Asunto (textarea)
(Campos de color Rojo con forma de pastilla, de a dos por renglon, el texto de adentro de color Beige)
-- Enviar (button)
(Boton de color Negro, al pasar el mouse se pone Beige)


HOBBIES (paginas/hobbies.html)

Contenido (main)
(Caja contenedora del fondo de color Rojo con la trama)
- Hobbies (h1)
(Alineado a la Izquierda, con tipografia Annie Use Your Telescope, de color Negro)
- Texto (p)
(Alineado a la Izquierda, con tipografia Amaranth Bold, de color Negro)
- Botones (section)
(Alineado a la Derecha, caja de color Beige con sombra)
-- Dibujos (a)
-- Rugby (a)
(Botones de color Rojo con relieve, con tipografia Annie Use Your Telescope, de color Beige. Al pasar el mouse se ponen Negros y al apretarlos se hunden)


DIBUJOS (paginas/secciones-hobbies/hobbies-dibujos.html)

Contenido (main)
(Caja contenedora del fondo de color Rojo con la trama)
- Dibujos (h1)
(Alineado a la Izquierda, con tipografia Annie Use Your Telescope, de color Negro)
- Algunos de mis dibujos favoritos... (p)
(Alineado a la Derecha, con tipografia Amaranth Bold, de color Negro)
- Galeria (ul)
(5 dibujos en fila (img) de 280px por 363px, al pasar el mouse se agrandan un poco)


RUGBY (paginas/secciones-hobbies/hobbies-rugby.html)

Contenido (main)
(Igual que dibujos, pero con 5 tarjetas grises porque todavia no tengo las fotos)


TRABAJOS (paginas/trabajos.html)

Contenido (main)
(Caja contenedora del fondo de color Rojo con la trama)
- Trabajos (h1)
(Alineado a la Izquierda, con tipografia Annie Use Your Telescope, de color Negro)
- Texto (p)
(Alineado a la Izquierda, con tipografia Amaranth Bold, de color Negro)
- Flechas (p)
(Alineado a la Derecha, caja de color Beige con tres flechas que suben y bajan)
- Galeria de trabajos (ul)
(6 tarjetas, de a 3 por renglon, con la foto y el nombre arriba)
-- Dos pares - Juego de naipes - Diseño I (li)
-- Subsuelo - Festival de cine - Diseño II (li)
-- 7 cajas - Afiche de pelicula - Diseño II (li)
-- Pequeño cheff - Recetario - Espacio Tipografico II (li)
-- Ciramdix - Bestiario - Medios Expresivos II (li)
-- Manos - Contraste de color - Medios Expresivos II (li)
(Titulos (h2) con tipografia Annie Use Your Telescope y textos (p) con tipografia Amaranth, de color Beige)
- Carrusel (section)
(Al hacer click en una tarjeta se abre una ventana oscura con las fotos del trabajo y flechas para pasarlas. Lo hice con :target y radio buttons. Dos pares tiene 7 fotos y un gif de las cartas)


Version celular
Hasta los 900px de ancho las cajas se ponen una abajo de la otra y todo se achica, asi la pagina solo se scrollea para abajo. Tambien deje lugar arriba para la barra del telefono (la hora, la bateria y la camara).
