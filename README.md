## Proyecto Individual - Data Engineer 
_Ingeniera: Zapata, María Belén_

> En este README encontrarán toda la documentación, e instrucciones necesarias, para poder utilizar la API que se me solicitó desarrollar.
 
:purple_circle: **Las funciones que componen la API son:** :purple_circle:

:small_blue_diamond: Conteo de palabras clave, por plataforma. <br>
:small_blue_diamond: Conteo de peliculas, por año, plataforma y puntuación. <br>
:small_blue_diamond: Segunda película mejor puntuada en la plataforma seleccionada. <br>
:small_blue_diamond: Película de mayor duración, por plataforma y por año. <br>
:small_blue_diamond: Cantidad de películas con determinada clasificación. <br>

:purple_circle: **Cómo escribir cada función en el navegador:** :purple_circle: 

:diamond_shape_with_a_dot_inside: https://twj1kq.deta.dev/get_word_count/{plataforma}/{keyword} <br>
:diamond_shape_with_a_dot_inside: https://twj1kq.deta.dev/get_score_count/{plataforma}/{puntaje}/{ano} <br>
:diamond_shape_with_a_dot_inside: https://twj1kq.deta.dev/get_second_score/{plataforma} <br>
:diamond_shape_with_a_dot_inside: https://twj1kq.deta.dev/get_longest/{plataforma}/{duration_type}/{ano} <br>
:diamond_shape_with_a_dot_inside: https://twj1kq.deta.dev/get_rating_count/{rating} <br>

:purple_circle: **Queries de ejemplo para probar la api** :purple_circle: 

:diamond_shape_with_a_dot_inside: https://twj1kq.deta.dev/get_word_count/netflix/love <br>
:diamond_shape_with_a_dot_inside: https://twj1kq.deta.dev/get_score_count/netflix/85/2010 <br>
:diamond_shape_with_a_dot_inside: https://twj1kq.deta.dev/get_second_score/amazon <br>
:diamond_shape_with_a_dot_inside: https://twj1kq.deta.dev/get_longest/netflix/min/2016 <br>
:diamond_shape_with_a_dot_inside: https://twj1kq.deta.dev/get_rating_count/18+ <br>

:warning: **Sintaxis a tener en cuenta al escribir una consulta:** :warning:
:small_blue_diamond: Todo debe estar escrito en minúsculas.  <br>
:small_blue_diamond: Las plataformas que admite son: Amazon, Disney, Hulu y Netflix. <br>
:small_blue_diamond: Evite utilizar caracteres hispanos. <br>
:small_blue_diamond: En caso de la query no arroje resultados, un mensaje explicativo se imprimirá en pantalla.<br>
:small_blue_diamond: En caso de que se ingrese una plataforma inválida, un mensaje explicativo se imprimirá en pantalla. <br>

:purple_circle: **Funciones extra** :purple_circle: 
:small_blue_diamond::small_blue_diamond:Función Presentación: `/` <br>
Simplemente invocando el link vacío, muestra el nombre y a quien pertenece la api.<br>
Función menú: `/menu` <br>
Muestra una lista de las funciones disponibles para consultar. <br>
:small_blue_diamond:Función Contacto: `/contacto`<br>
Muestra dos maneras de contactar conmigo, en caso de necesidad. <br>
Función docs: `/docs` <br>
Muestra el menú principal de la api, donde también se puede testear las consultas.<br>

:purple_circle: **Notas finales:** :purple_circle:
:innocent: Muchas gracias por testear mi api! <br> 
Todo el feedback es bien recibido. :coffee: