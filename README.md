Este proyecto es una pagina web sobre Microgenesis, una empresa de fertilidad, que busca preparar el cuerpo para llevar a cabo un embarazo de forma natural y no invasiva.
Para ver el sitio web en línea, seguir estos pasos:
Abre un navegador web, luego, Ingresa la siguiente URL en la barra de direcciones:https://theikus218.github.io/Pagina-Web/
La función JavaScript implementada en este proyecto permite al usuario mostrar u ocultar una sección de contenido en la página al hacer clic en un botón.
¿Qué hace? La función detecta cuando el usuario hace clic en el botón "Mostrar/Ocultar Beneficios". Si la sección con el ID benefits está oculta (es decir, tiene el estilo display: none), la función la hace visible cambiando el estilo a display: block.
Si la sección ya está visible, la función la oculta cambiando el estilo de nuevo a display: none.
¿Cómo funciona?
Se asigna un evento de tipo onclick al botón con el ID toggleBenefits.
Cuando el usuario hace clic en el botón, el código JavaScript busca la sección de beneficios utilizando document.getElementById("benefits").
Luego, revisa si la sección está actualmente oculta (verificando el valor de style.display).
Dependiendo del estado (visible u oculto), cambia la propiedad style.display para mostrar u ocultar la sección de beneficios.
Esto brinda a la home page un poco mas de claridad ya que el texto se puede ocultar o mostrar dependiendo del gusto del usuario
