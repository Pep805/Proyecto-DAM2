# Proyecto-DAM2
|| Pep Luna DAM 2 Proyecto Final de Grado ||  Explicación ejecución de la aplicacion al final del documento  ↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓

📖 Explicación idea del proyecto:

Mi app es Schedule Master, una app de escritorio que te permite establecer metas de diferentes tipos y para diferentes categorías, así como establecer metas en días puntuales en un calendario interno que tiene la app, establecer repeticiones en estas metas, y como toque final, tiene una sección que te ayuda a organizarte la semana. Tú estableces en los horarios de mañana y tarde las tareas que tengas y, luego, eligiendo entre varios diseños, la app te permite exportar el "Schedule" a PDF aplicando el diseño bonito que has elegido, y que te lo permita descargar, imprimir o lo que quieras hacer con él.

🎯 Nuestros Objetivos

El objetivo principal de este proyecto no es otro que obligarme a tocar otras tecnologías como Visual Studio WPF y C#, salirme un poco de lo que hacen los demás, explorar nuevos campos y poder ofrecer una app que permita a los que la quieran usar una vida llena de orden y paz.

🌐 Tecnologías Usadas

Para llevar a cabo dicho proyecto, he recurrido a WPF desarrollado con C#, un tipo de proyecto para desarrollar aplicaciones de escritorio con más potencial y alcance que el clásico Forms. Permite desarrollar interfaces más modernas, tener más control de los elementos, establecer animaciones y una infinidad de opciones modernas.

Visual Studio: Un entorno de desarrollo integrado creado por Microsoft. Ayuda a los programadores a escribir, depurar, probar y desplegar aplicaciones de software de manera más eficiente. Admite una gran gama de lenguajes de programación y tiene herramientas para la edición de código, diseño de interfaz de usuario, compilación y control de versiones.

WPF (Windows Presentation Foundation): Una tecnología de Microsoft para la creación de interfaces gráficas de usuario en aplicaciones de escritorio. Permite diseñar interfaces modernas y atractivas usando XAML.

C#: Un lenguaje de programación desarrollado por Microsoft. Es muy utilizado para crear aplicaciones de todo tipo, desde servicios web hasta aplicaciones de escritorio y móviles.

MySQL: Para crear la base de datos, sus tablas, relaciones y la gestión y guardado de datos.

Utilizando estas tecnologías, llevaré a cabo una app de escritorio para Windows con una base de datos SQL que guarde los datos y los cargue.

💻Pagina Web

    💭Mockup
        (Los mock ups estan en la carpeta Mock_Up).
        Su uso es sencillo: El login incorpora una animación inicial que permite saltarla si quieres iniciar sesión de forma más rápida y no comerte toda la animación de inicio. 
        Una vez iniciado sesión, se accede al menú en el que uso un UserControl, una barra lateral con los apartados por los que se puede navegar, con una barra con una animación que se mueve lateralmente según la opción a la que se navega.
        Uso un fondo negro, ya que con las apps de organización y ese entorno, es un color que pega, además de mostrar elegancia y orden de cara al público y al marketing. 
        Con botones grises y azules que combinan bien, y otros verdes y rojos para confirmación y negación.

        Uso font-weight bold para textos con mayor importancia, animaciones sobre botones al pasar el cursor por encima y otros pequeños detalles que, a la vista del usuario, ofrecen una experiencia agradable. 
        Así como una buena gestión de errores para evitar acciones no deseadas por parte del usuario.

    🎨Paleta De Colores
        Blanco (#FFFFFF): Un color clásico, el blanco representa simplicidad y limpieza. Hace que el contenido sea fácil de leer. Lo uso para los contenidos principales, que seas de lectura fácil.

        Negro (#000000): El negro es un color elegante, que aporta un fuerte contraste y una sensación de solidez.
        Perfecto para el fondo de la aplioacion, y buen contraste con azul, gris y blanco.

        Gris (#FF525151): Este gris es moderno, ofrece un buen equilibrio entre el blanco y el negro. Es perfecto para los fondos, los bordes y los elementos secundarios. Y así lo he hecho, para elementos no tan protagonistas en mi app.

        Verde (#FF25CA82): Este verde representa crecimiento, renovación y estabilidad. Y lo utilizo para destacar elementos importantes.

        Rojo (#FF0000): El rojo es llamativo, y simboliza urgencia, pasión y alerta. Los uso para representar advertencia, cautela y urgencia en el sentido de no procrastinar y ponerte ya! a organizar tu vida.
    👀Logo
        Para el tema del logo de la app, no he sido muy selectivo, he tirado pro el camino del minimalismo, y dado que mi aplicacion es de metas y objetivos he seleccionado una diana azul y el texto dependiendo del formato debajo o a la izquierda del logo.
        (El logo se halla en la carpeta de _Logo).

    🔗Funcionalidades Web

    (La funcionalidad están en la carpeta _funcionalidades).

Roadmap/Trello/Gantt (El enlace a mi proyecto de Trello lo adjunto debajo de la explicación). 
En este programa que he realizado en Trello, he establecido los diferentes objetivos que tengo que realizar en la app por nivel de prioridad. 
He separado aquellos que ya estoy diseñando (en proceso), los que aún no he iniciado (pendientes) y aquellos ya finalizados (terminados). 
También he incorporado los recursos empleados para desarrollar dicho proyecto, y aquellas opciones o ideas que finalmente han sido abortadas/canceladas, por otras que me han parecido más adecuadas. 
En resumen, todos aquellos procesos involucrados en el proyecto, por orden de prioridad, los recursos para su desarrollo y los elementos abortados.

Enlace a Trello: [Enlace al Trello](https://trello.com/b/jNKCrBrS/mi-tablero-de-trello)



*******************************************************************************************************************************************************************************
ACCESO A TEASTEAR LA APLICACIÓN
*******************************************************************************************************************************************************************************
EXPLICACIÓN EJECUCIÓN DE LA APP:
En la carpeta Schedule master ejecutable la cual se encuentra comprimida en un zip se deberá extraer, y dentro de ella hay 2 carpetas, la primera llamada "Schedule master" la cual se utilizará para levantar el contenedor con la imagen de MYSQL, y con el script y las clases del programa. Para poder testear la all hay que estar dentro de la carpeta Schedule master en donde se hallan archivos ya mencionados como el scrip de la bbdd y el archivo docker compose.yaml entre otros, entonces una vez en terminal apuntando a dicha carpeta se ha de ejecutar el comando docker compose up --build, PERO antes de deberá abrir docker como administrador!!! entonces el contenedor se levantará y el servicio MYSQL se arrancará permitiendo acceder a la  aplicación. 
COMO ACCEDER AL EJECUTABLE, una vez levantado el contendor, se debe ir a la otra carpeta que es Schedule master EJECUTABLE y buscar el ejecutable un archivo, llamado Schedule Master.exe ejecutará el programa y ya iniciará todo correctamente para el testeo.

********************************************************************************************************************************************************************************
ADJUNTO EL ENLACE A DRIVE EN DONDE HAY UNA CARPETA PUBLICA DESDE DONDE SE PUEDE EXTRAER EL ZIP DE LA APLICACIÓN, YA QUE PESA MAS DE 25MB Y NO ME DEJABA SUBIRLA A GIT.

ENLACE A DRIVE: https://drive.google.com/file/d/1huvD31spSIYZxDzB7oNM0_jqEaOBwGwW/view?usp=sharing
