## <p align = "center"> PRACTICA Nº1</p>
##  <p align = "center">SISTEMAS EMPRESARIALES</p>

|||
|----------|-------------|
|Carrera:| Ingenieria De Sistemas|
|Materia:| Tecnologias Emergentes II|
|Apellidos y Nombres:| Choque Vargas Martha|
|C.I.:| 7071937 L.P.|
|Lugar y Fecha:| El Alto - 2019|


<![endif]-->

>1) Explique que son los sistemas empresariales

Un Sistema de Información Empresarial es un sistema que tiene un impacto muy importante en el funcionamiento de la organización o negocio y cuya falla traería graves consecuencias.

Son aquellos que constituyen el conjunto de recursos de la empresa, que sirven como soporte para el proceso básico de captación, transformación y comunicación de la información.

>2) Describa cuales son las características más importantes de una aplicación empresarial

En la actualidad prácticamente todas las tareas que llevamos a cabo través de un ordenador las realizamos gracias a la implantación de un software de aplicación.

*características*.

**--Procesadores de palabras** gracias a ellos podemos escribir textos, borrarlos, revisar la ortografía, hacer cambios en la escritura, entre otras muchas cosas.

**--Procesadores de números** (hojas de cálculo), estas son para crear plantillas en donde poder priorizar formulas, hacer operaciones incluso se puede incluir textos.

**--Bases de datos**, que es una herramienta fundamental para poder tener controlado toda la información que hemos guardado en el ordenador y consultarla rápidamente.

**--Graficadores** que sirven para crear tablas, gráficas y todo tipo de ilustraciones.

**--Operaciones transaccionales**, cumple con las propiedades ACID.

**--Escalables**, permiten escalabilidad vertical y horizontal.

**--Disponibles**, idealmente prestan servicios de forma continua.

**--Seguras**, no todos los usuarios acceden con la misma funcionalidad.

>3) Investigue y proponga cinco (5) instituciones que requerirían aplicaciones de misión crítica.

Justifique su respuesta

Las aplicaciones de misión critica a aquellas aplicaciones que tienen un impacto muy importante en el funcionamiento de la organización o negocio y cuya falla traerá efectos terribles.

Estas aplicaciones no están instaladas en redes locales sino en la nube

>4) Explique cuáles son las diferencias entre la escalabilidad horizontal y escalabilidad vertical

- **Escalabilidad vertical** el escalar hacia arriba un sistema viene a significar una migración de todo el sistema a un nuevo hardware que es más potente y eficaz que el actual, una vez se ha configurado el sistema futuro, se realizan una serie de validaciones y copias de seguridad y se pone en funcionamiento.

Esta tiene un aspecto negativo al aumentar la potencia en base a aplicaciones de hardware

- **Escalabilidad horizontal** consiste en potenciar el rendimiento del sistema desde un aspecto de mejora global a diferencia de aumentar la potencia de una única parte del mismo, este tipo de escalabilidad se basa en el modularidad de su funcionalidad, normalmente en esta se añade equipos para dar más potencia a la red de trabajo.

Como principal e importante defecto este modelo supone una gran modificación en el diseño, lo que lleva un gran trabajo de diseño y de implantación.

Las diferencias entre estas escalabilidades es que la horizontal significa que la escala agregando más maquinas a su grupo de recursos, mientras que la escala vertical significa que la escala agregando más potencia (CPU, RAM) a una maquina existente

>5) Que es un servidor Web y que es un servidor de aplicaciones

- **El servidor web** (servidor Http) es un programa informático que procesa una aplicación del lado del servidor, realizando conexiones bi-direccionales o uní-direccionales y síncronas o asíncronas con el cliente y generando o cediendo una respuesta en cualquier lenguaje o aplicación de lado del cliente.

- **El servidor de aplicaciones** usualmente se trata de un dispositivo de software que proporciona servicios de aplicaciones a la computadora cliente.

>6) Con un gráfico explique cómo funciona el protocolo HTTP

![Resultado de imagen para funcionalidad   el protocolo HTTP](https://slideplayer.es/slide/5620844/2/images/3/Funcionamiento.jpg)

<![endif]-->

>7) Explique los elementos importantes de REQUEST en HTTP

**--Método http**

**--La página para acceder**

**--Formar parámetros**

>8) Explique los elementos importantes de RESPONSE en HTTP

**--un código de estado**, para saber si la solicitud fue exitosa.

**--tipo de contenido**, texto, imagen, HTML , etc.

**--el contenido**, el HTML real, imagen, etc.

>9) Describa con un gráfico la arquitectura Java EE

![Resultado de imagen para arquitectura de java ee](https://image.slidesharecdn.com/jatunandjavaee-110905104600-phpapp02/95/desarrollo-de-aplicaciones-empresariales-con-java-ee-4-728.jpg?cb=1316098712)


<![endif]-->

>10) Explique cuáles son los contenedores, componentes y servicios de Java EE

**--Contenedores:** es un entorno de ejecución que provee al componente una serie de servicios.

-Contenedores web

-Contenedores de negocio (o de EJBs)

**--Componentes:** es una unidad de software que forma parte de una aplicación.

-Componente cliente: Cliente AWT, Swing, Applet y navegador Web.

-Componenteweb: Servlet, JSP, JSF.

-Componente de negocios: EJB.

**--Servicios:** son los servicios que deben ofrecer los contenedores de Java EE

-De directorio: para la indexación y búsqueda de componentes y recursos.

-De despliegue: para poder personalizar los componentes y recursos.

-De tranaccionalidad: para poder ejecutar distintas acciones de una misma unidad transaccional.

-De seguridad: para poder autenticar y autorizar a los usuarios de la aplicación.

-De acceso a datos: para facilitar el acceso a Bases de Datos

-De conectividad: para poder acceder facilmente a distintos EIS.

-De mensajeria: para poder comunicarse con otros componentes, aplicaciones o EIS.

>11) Investigue los métodos más utilizados de las clases HttpServlet, HttpServletRequest y HttpServletResponse, y para cada uno de los métodos muestre un ejemplo.

**-HttpServletResponse:**

*-addCookie(Cookie cookie)*: Para definir nuevas _cookies_ en el cliente.

*-setHeader(String name, String value)*: Para definir un header HTTP a enviar al cliente.

*-sendRedirect(String location)*: Envía un mensaje al cliente para redireccionar la respuesta a la dirección señalada.

**--HttpServletRequest:**

*-getHeader(String name)*: Permite obtener el valor de los Headers de HTTP con que fue llamado el servlet.

*-getCookies()*: Retorna un arreglo que contiene todas las _cookies_ que el cliente envía al servlet.

*-getSession()*: Retorna la sesión en la cual se encuentra el cliente.

**--HttpServlet:**

*-init(ServletConfig config)*: Es el método utilizado para crear una nueva instancia del servlet.

*-getServletConfig()*: Retorna la configuración dada para la inicialización del servlet.

*-service(ServletRequest req, ServletResponse res)*: Este método es el que se llama cuando se recibe una petición de un cliente y en su implementación normal para HTTP verifica el tipo de solicitud GET, POST, etc. y la redirige a los métodos respectivos. En general no es necesario reimplementar este método.

*-destroy()*: Este método es llamado por el servidor para indicar que el servlet será destruido.

> Written with [StackEdit](https://stackedit.io/).
