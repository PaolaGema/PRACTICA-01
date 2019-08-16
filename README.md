# PRACTICA-01

# SISTEMAS EMPRESARIALES #

<table>
    
<tr>
    <td>CARRERA:</td>
    <td>INGENIERIA DE SISTEMAS</td>
    <td rowspan=5>M</td>
</tr>
<tr>
    <td>MATERIA</td>
    <td>TECNOLOGIAS EMERGENTES II</td>
</tr>
  <tr>
    <td>APELLIDOS Y NOMBRES</td>
    <td>MAMANI JANCO PAOLA GEMA</td>
</tr>
  <tr>
    <td>C.I. </td>
    <td>13797938</td>
</tr>
  <tr>
    <td>LUGAR Y FECHA</td>
    <td>CIUDAD DE EL ALTO</td>
   
</table>
               


### Explique que son los sistemas empresariales.
 
 Son sistemas centrales de una organizacion que permiten transmitir la informacion a todas las areas funcionales de una empresa para dar  soporte a la operacion y a la administracion de la misma.
### Describa cuales son las características más importantes de una aplicación empresarial.

•	Disponibilidad, una aplicación empresarial debe prestar servicios de manera continua.


•	Seguridad,  no todos los funcionarios de la empresa acceden al sistema con la  misma funcionalidad.


•	Acceso a base de datos, usualmente a base de datos relacionales.


•	Escalabilidad, que permita escalabilidad horizontal como escalabilidad vertical


### Investigue y proponga cinco (5) instituciones que requerirían aplicaciones de misión crítica.
### Justifique su respuesta.
 
 •	Instituciones Financieras, es muy necesaria su disponibilidad durante los horarios de atencion, debido a que perjudica a las personas su caida de sistema.
 
 
 •	Instituciones Privadas (empresas), es muy importante la capacidad operativa dentro de una empresa.
 
 
 •	Instituciones Publicas(hospitales,oficinas policiales,etc), es muy importante la disponibilidad, usabilidad, capacidad operativa dentro de cada una de las instituciones publicas debido a que mucha gente recurre diariamente a estos lugares. 
 
 
 •	Instituciones Telefonicas, es muy necesaria su disponibildad las 24 horas del dia, caso contario la empresa perderia millones de bolivianos.
 
 
 •	Instituciones Gubernamentales, son sistemas de índole social y cooperativa por lo que es muy necesaria su disponiblidad diaria.
 
 
### Explique cuáles son las diferencias entre la escalabilidad horizontal y escalabilidad vertical.
 
 <table>
<tr>
    <td>ESCALABILIDAD HORIZONTAL</td>
    <td>ESCALABILIDAD VERTICAL</td>
</tr>
<tr>
    <td>Complicado de Implementar</td>
    <td>Fácil de implementar</td>
</tr>
  <tr>
    <td>El crecimiento es prácticamente
 Infinito, permite agregar servidores cuantos sean necesarios.
</td>
    <td>El crecimiento esta limitado por el Hardware</td>
</tr>
  <tr>
    <td>Soporta la alta disponibilidad </td>
    <td>No soporta la Alta disponibilidad</td>
</tr>
  <tr>
    <td>Si un nodo falla, los demás siguen trabajando</td>
    <td>Una falla en el Servidor implica que la aplicación se detenga</td>
    </tr>
<tr>
    <td>Requiere de mucho mantenimiento</td>
    <td></td>
</tr>
</table>
 



### Que es un servidor Web y que es un servidor de aplicaciones
  Un servidor web es el software que se encarga de despachar el contenido de un sitio web al usuario.
   
   
 Un servidor de aplicaciones es un programa de servidor en un equipo en una red distribuida que proporciona la lógica de negocio para un programa de aplicación.
 
 
### Con un gráfico explique cómo funciona el protocolo HTTP

![IMAGEN](http://www.profesordeinformatica.com/images/http_funcionamiento.gif)
### Explique los elementos importantes de REQUEST en HTTP

• Method HTTP, método HTTP para la petición


•URL, URL a la cual enviar la petición.


•	FORMULARIO DE PARAMETROS:


        Contenido, Contenidos del cuerpo (body) de la petición.
        
        
        Respuesta, Resultado de la petición.
        
        
       	NomEncab, Nombre de los encabezados de la petición.
        
        
      	ValoresEncab, Valores de los encabezados de la petición.
        
        
    	Resultado, código de estado HTTP

### Explique los elementos importantes de RESPONSE en HTTP


•	Estado de Código, para saber si la solicitud fue exitosa.


•	Tipo de contenido, ( texto, imagen, html, etc).


•	Contenido, el actual contenido ya sea (Html, image, texto, etc).

### Describa con un gráfico la arquitectura Java EE

![IMAGEN1](https://image.slidesharecdn.com/jatunandjavaee-110905104600-phpapp02/95/desarrollo-de-aplicaciones-empresariales-con-java-ee-4-728.jpg?cb=1316098712)
### Explique cuáles son los contenedores, componentes y servicios de Java EE.
**CONTENEDORES

•	Java EE Server: La porción de tiempo de ejecución de un producto Java EE. provee los contenedores web y de ejb.


•	Contenedor EJB: Maneja la ejecución de los enterprise beans.


•	Contenedor Web: Maneja la ejecución de las paginas web, servlets y algunos componentes ejb para las aplicaciones Java EE.


•	Contenedor de aplicación cliente: Maneja la ejecución de la aplicación cliente no necesita un servidor de aplicaciones.


•	Contenedor Applet: Maneja la ejecución de applets, no necesita servidor de aplicaciones, consiste en un browser y el plugin web de java.

**COMPONENTES

•	Componente Cliente (Lado Cliente)

---Web.


---Applets.


---Aplicaciones de Escritorio.


•	Componente Web (Lado Servidor)
---Servlets


---JavaServer Pages (JSP)/Facelets.


---JavaServer Faces (JSP),framer para aplicaciones web


•	Componente de Negocio (Lado Servidor)


---Entrerprise JavaBeans (EJB)


---Java Persistence API (JPA)


**SERVICIOS

•	De directorio: para la indexación y búsqueda de componentes y recursos 


•	De despliegue: para poder personalizar los componentes y recursos 


•	De transaccionalidad: para poder ejecutar distintas acciones en una misma unidad transaccional 


•	De seguridad: para poder autenticar y autorizar a los usuarios de la aplicación


•	De acceso a datos: para facilitar el acceso a Bases de Datos


•	De conectividad: para poder acceder fácilmente a distintos EIS 


•	De mensajería: para poder comunicarse con otros componentes, aplicaciones o EIS 


### Investigue los métodos más utilizados de las clases HttpServlet, HttpServletRequest y
### HttpServletResponse, y para cada uno de los métodos muestre un ejemplo.

**Metodos de HttpServlet

•	init(ServletConfig config): Es el método utilizado para crear una nueva instancia del servlet (análogo al constructor).  Este método


puede ser sobreescrito para realizar tareas como crear una conexión a una BD que se mantendrá mientras el servlet se mantenga cargado y 


puede ser utilizada por cada petición. ServletConfig contiene los parámetros de inicialización que entrega el servidor al servlet.


•	getServletConfig(): Retorna la configuración dada para la inicialización del servlet.


•	service(ServletRequest req, ServletResponse res): Este método es el que se llama cuando se recibe una petición de un cliente y en su

implementación normal para HTTP verifica el tipo de solicitud GET, POST, etc. 

•	destroy(): Este método es llamado por el servidor para indicar que el servlet será destruido. Es llamado sólo una vez y uno debe

encargarse de esperar por posibles peticiones en curso.



**Metodos de HttpServletRequest

•	El método getParameter devuelve el valor de un parámetro nombrado.


•	El método getParameterValues devuelve un array de valores 


•	Para peticiones GET de HTTP, el método getQueryString devuelve en un String una línea de datos desde el cliente


•	Para peticones POST, PUT, y DELETE de HTTP.


Si esperamos los datos en formato texto, el método getReader devuelve un BufferedReader utilizado para leer la línea de datos.


Si esperamos datos binarios, el método getInputStream devuelve un ServletInputStream utilizado para leer la línea de datos.

**Metodos de HttpServletResponse

•	El método getWriter devuelve un Writer
•	El método getOutputStream devuelve un ServletOutputStream



