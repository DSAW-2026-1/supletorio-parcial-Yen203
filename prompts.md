##Prompt 1 - Estrcutura HTML
Prompt 1(Estructura): Definición de la semántica HTML (uso de etiquetas correctas).  Teniendo en cuenta este html semántico que realice: 
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>Parcial Desarrollo Web con React-JS | Yenifer Mongui Pinilla</title>
    <link href="style.css">
</head>
<body>
<div> class= "container">
    <div class="item"></div>
    <div class="item"></div>
    <div class="item"></div>
            
    <div class="item"></div>
    <div class="item"></div>
</div>
</body>
</html>
El objetivo es crear y corregir una base estructural que después será estilizada con el modelo e caja  y técnicas de layout como Flexbox o CSS Grid. Entonces genera una estructura HTML semántica para un componente de interfaz.
Conectar la hoja de estilos externa utilizando la etiqueta    ‘<link href="style.css">’
Añade  la etiqueta necesaria a la estructura semántica de HTML para que se puedan permitir caracteres especiales
Debo realizar una imagen que debe tener un contenedor principal (con la clase: ‘.container’) de todo el diseño  
 Dentro del contenedor debe tener 5 elementos (con la clase ‘item’) que luego serán estilizados con CSS, está bien estructurado? 
Las clases utilizadas si facilitan la especifidad de los selectores para CSS? Si no, coloca las correctas 

##Prompt 2 - Estilos base (Box model y Colores)
El objetivo es la implementación de colores, tipografía y el modelo de caja, para los estilos visuales inciales antes de aplicar la técnica de Flexbox y demás.
A partir de la estructura HTML anterior, agrega los estilos de base usando CSS:
-Aplicar un ** reset básico** usano el selector universal ‘*’ para eliminar márgenes y padding por defecto del navegador
-Utilizar  ‘box-sizing: border-box’  para controlar el **Box Model** de forma correcta
- Definir un contenedor principal ‘.container con un ancho de  ‘400px’ y un altura de ‘300px’
-Aplicar un color de fondo similar al diseño original
-Estilizar los elementos ‘.item’ con un color de fondo claro  similar al diseño original
-Utilizar ‘border-radius’ para que se creen formas ovaladas en cada elementos en las esquinas
- Mantener una buena organización de selectores CSS para facilitar la especifidad

##Prompt 3- (Layout y Refinamiento):
Uso de Flexbox o Grid para alinear los elementos exactamente como en la imagen. 
El objetivo es alinear ( o refina el diseño) los 5 elementos como en la imagen e referencia utilizando las técnicas Flexbox  y CSS Grid:
-Utilizar CSS Grid para organizar los elementos entro el contenedor
-Definir ‘display: grid’ en el contenedor interno que agrupa los elementos
-Usar ‘grid-templste-columns’ para crear tres columnas
-Usar ‘ grid-template-rows’ para organizar los elementos en dos filas
-Aplicar ‘gap’ para generar el espacio uniforme entre los elementos
- Asegurar que el contenedor principal esté centrado en el viewport 	Flexbox con ‘display: flex’,  ‘ justify-content: center’  y ‘align-items: center’
-Mantener una jerarquía correcta de selectores para  tener una buena especificad del CSS  


