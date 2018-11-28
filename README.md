# AW

1.- Estructura minima de una web:
<html>
<head>
	<title></title>
</head>
<body>

</body>
</html>

2.- Explica las 3 formas de usar CSS en HTML:
 - CSS Externo:
   Declara los estilos CSS en otro archivo para dotar de estilos a otros archivos html.
 
 - CSS Interno:
   Es cuando incluyes los estilos en la cabezera del documento html.
 
 - CSS Embebido:
  Se usa en las etiquetas usando el atributo style="".
 
3.- Crea una lista sin ordenar con 5 ingredientes de una receta de cocina.
<ul>
  <li> 300g Harina
  <li> 150g Azúcar
  <li> 1/2 Levadura
  <li> 2 Limones
  <li> 150ml aceicte
</ul>

4.- Como se puede incluir javascript en HTML.
   Poniendo: <script type="text/javascript"></script>

5.- ¿Que diferencia hay entre una clase y una ID.
  Una clase puedes identificar varios elementos y con una ID solo 1.

6.- Código para hacer un enlace a otra página y que esta se abra en una nueva ventana.
  <a href="pagina.html" target="_blank">Enlaceaotrapagina</a>.

7.- ¿Qué son las pseudoclases?, pon ejemplos.
  Son palabras clave que se ponen en los selectores y especifican un estado especial de un elemento.
  Ejemplo :hover, :visited, :checked...

8.- Explica el modelo de caja de CSS (margin, border y padding)
  Padding es un relleno transparente alrededor del contenido.
  Border es un borde alrededor del padding y del contenido.
  Margin limpia un area transparente alrededor del border y padding.

9.- Explica que son los selectores de CSS y pon ejemplos
  Son patrones que se utilizan para seleccion elementos a los que vas a aplicar un estilo.
  * {}
  p {}
  ul {}
  li {}
  body {}
  
10.- Di a quien afectan:
      p a { color: red; }
        Todos los parrafos que tenga una <a> o enlace, que es color de la letra sea de color rojo.
        
      p > a { color: red; }
      
      h1 + h2 { color: red }
        El h1 mas el h2 el color de la letra saldra en rojo.
      
      a[class] { color: blue; }
        Los enlaces que contengan un class que tengan el color azul en la letra. 
      
      a[class="externo"] { color: blue; }
        Todos los enlaces que tengan dentro un class="externo" que tengan la letra de color azul.
      
      a[href="http://www.ejemplo.com"] { color: blue; }
        Todos los enlaces que ponga href="http://www.ejemplo.com" tengan el color de letra azul
 
