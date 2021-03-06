[![](captura.png)](captura.png "Captura de Pantalla")

# Bootstrap 5 | Containers

📒 Bootstrap 5 Contenedores

    📝 Bootstrap requiere un elemento contenedor para envolver los contenidos del sitio.
    📝 Los contenedores se utilizan para rellenar el contenido dentro de ellos y hay dos clases de contenedores disponibles:
        🔸 La clase .container proporciona un contenedor de ancho fijo receptivo.
        🔸 La clase .container-fluid proporciona un contenedor de ancho completo, que abarca todo el ancho de la ventana gráfica.

📒 Contenedor Fijo

    📝 Utilice la clase .container para crear un contenedor receptivo de ancho fijo.
    📝 Tenga en cuenta que su ancho (ancho máximo) cambiará en diferentes tamaños de pantalla:

                            max-width

        Extra small         100%
        <576px	
        
        Small               540px
        ≥576px	
        
        Medium              720px
        ≥768px	
        
        Large               960px
        ≥992px	
        
        Extra Large         1140px
        ≥1200px	
        
        XXL                 1320px
        ≥1400px

        
        Nota:

        El punto de interrupción XXL (≥1400px) es nuevo en Bootstrap 5, mientras que el punto de interrupción más grande en Bootstrap 4 es Extra grande (≥1200px).

        <div class="container">
            <h1>My First Bootstrap Page</h1>
            <p>This is some text.</p>
        </div>

📒 Contenedor de fluidos

    📝 Use la clase .container-fluid para crear un contenedor de ancho completo, que siempre abarcará todo el ancho de la pantalla (el ancho siempre es 100%):
   						
        <div class="container-fluid">
            <h1>My First Bootstrap Page</h1>
            <p>This is some text.</p>
        </div>

📒 Relleno de contenedores

    📝 De forma predeterminada, los contenedores tienen relleno izquierdo y derecho, sin relleno superior o inferior. Por lo tanto, a menudo usamos utilidades de espaciado, como relleno y márgenes adicionales para que se vean aún mejor. Por ejemplo, .pt-5 significa "agregar un relleno superior grande":

        <div class="container pt-5"></div>

📒 Borde y color del contenedor

    📝 Otras utilidades, como bordes y colores, también se usan a menudo junto con los contenedores:
    
        <div class="container p-5 my-5 border"></div>
        <div class="container p-5 my-5 bg-dark text-white"></div>
        <div class="container p-5 my-5 bg-primary text-white"></div>

📒 Contenedores receptivos

    📝 También puede usar las clases .container-sm|md|lg|xl para determinar cuándo debe responder el contenedor.
    📝 El ancho máximo del contenedor cambiará en diferentes tamaños de pantalla/ventanas:

        <div class="container-sm border">.container-sm</div>
        <div class="container-md mt-3 border">.container-md</div>
        <div class="container-lg mt-3 border">.container-lg</div>
        <div class="container-xl mt-3 border">.container-xl</div>
        <div class="container-xxl mt-3 border">.container-xxl</div>


Redes sociales:

- https://instagram.com/dev.joseltoro
- https://facebook.com/devjoseltoro
- https://tiktok.com/@dev.joseltoro
- https://dev.to/joseltoro
- https://code.dcoder.tech/profile/joseltoro
- https://joseltoro.blogspot.com/
- https://joseltoro.gumroad.com/