![](Aspose.Words.e754369f-f68d-48c7-9314-a3223c5e560b.001.jpeg)![](Aspose.Words.e754369f-f68d-48c7-9314-a3223c5e560b.002.jpeg)

**IES Gran Capitán
Departamento de Informática**

Ciclo Formativo de Grado Superior de
Administración de Sistemas Informáticos

**Implantación de Aplicaciones Web**

**Alberto Cobos Camacho – 2ºASIR**

**Proyecto: Proyecto Final (Any Company Crafting)**

**Curso 2022/2023**
# Contenido
[1.- Introducción](#_Toc129249340)

[2.- Objetivos y requisitos del proyecto](#_Toc129249341)

[3.- Estudio previo	](#_Toc129249342)

[3.1.- Estado actual	](#_Toc129249343)

[3.2.- Estudio de soluciones existentes	](#_Toc129249344)

[4.- Plan de trabajo	](#_Toc129249345)

[5.- Diseño	3](#_Toc129249346)

[5.1.- Diseño general	](#_Toc129249347)

[5.2.- Diseño detallado	](#_Toc129249348)

[6.- Implantación	](#_Toc129249349)

[7.- Recursos	](#_Toc129249350)

[7.1.- Herramientas hardware	](#_Toc129249351)

[7.2.- Herramientas software	](#_Toc129249352)

[8.- Conclusiones	](#_Toc129249353)

[8.1.- Grado de consecución de objetivos	](#_Toc129249354)

[8.2.- Problemas encontrados	](#_Toc129249355)

[8.3.- Futuras mejoras	](#_Toc129249356)

[9.- Información extra	](#_Toc129249357)



# **1.- Introducción**
Este proyecto trata de una tienda llamada Any Company Crafting migraran su sitio web, es una compañía dedicada a vender artesanía en línea y que los clientes tengan posibilidad de vender en su página web

# **2.- Objetivos y requisitos del proyecto**
Crear una página Web de comercio de productos artesanos con posibilidad de los clientes de vender sus diferentes productos artesanos
# **3.- Estudio previo**
Tendremos en cuenta que la Web empieza por el index por lo que haremos una página web llamativa

## ***3.1.- Estado actual***
Para realizar este proyecto, hemos creado una página web dinámica para realizar diferentes formularios y poder registrar tanto los datos de clientes, como los datos de los productos además de señalar que clientes venden X productos
## ***3.2.- Estudio de soluciones existentes***
Realizaremos un despliegue en AWS con diferentes servicios.

\- Crearemos una instancia EC2 donde alojaremos nuestra página web 

-Crearemos una instancia RDS donde tendremos la base de datos la cual solo puede acceder el grupo de seguridad en el que esta el EC2
# **4.- Plan de trabajo**
Nuestro plan de trabajo sería obtener un dominio en Amazon. Una vez tengamos el entorno de trabajo creado, implantaremos medios de seguridad en ese entorno de trabajo, en nuestra instancia donde se alojará la página web crearemos un grupo de seguridad el cual, tendrá la regla de entrada que nos indica

En nuestra instancia donde se alojará la base de datos, crearemos un grupo de seguridad para que solo puedan acceder a la base de datos las instancias que se encuentren en el grupo de seguridad web.

# **5.- Diseño**
## ***5.1.- Diseño general***
Una pagina web de aspecto moderno y minimalista con un diseño simple pero eficaz

![](Aspose.Words.e754369f-f68d-48c7-9314-a3223c5e560b.003.png)
## ***5.2.- Diseño detallado***
Hemos agregado una navbar que aun esta un poco verde aun todo hay que decirlo, ya que si funciona los diferentes login y registros pero 

![](Aspose.Words.e754369f-f68d-48c7-9314-a3223c5e560b.004.png)

También en el caso que se pudiera iniciar sesión hemos preparado un log.out

![](Aspose.Words.e754369f-f68d-48c7-9314-a3223c5e560b.005.png)

Hemos creado un menú tienda.html

# **6.- Implantación**
Instalación de MySQL, Instalación de apache y instalación de PHP

Crearemos una maquina RDS con la base de datos la cual accederemos exclusivamente desde la EC2

![](Aspose.Words.e754369f-f68d-48c7-9314-a3223c5e560b.006.png)

Tendremos instalado apache en la EC2 y PHP

![](Aspose.Words.e754369f-f68d-48c7-9314-a3223c5e560b.007.png)
# **7.- Recursos**
## ***7.1.- Herramientas hardware***
Una maquina EC2 y maquina RDS alojadas en la nube
## ***7.2.- Herramientas software***
Apache,PHP y MySQL y uso eventualmente de Filezilla para pasar archivos de mi PC al EC2
# **8.- Conclusiones**
## ***8.1.- Grado de consecución de objetivos***
Para el apartado tienda, en principio casi totalmente terminado quedaría la opción de comprar apartados para cada producto y poco mas

El Index totalmente terminado

Los usuarios se pueden registrar y logearse pero no sale nada en la página que diga que ese usuario ha iniciado sesión

## ***8.2.- Problemas encontrados***
Descripción de los principales problemas encontrados, las soluciones propuestas y la solución adoptada, justifcando su elección.
## ***8.3.- Futuras mejoras***
Posibilidad de añadir un carrito, tener paginas aparte para cada producto y que salga que usuario ha iniciado sesión en la web
# **9.- Información extra**
El usuario alberto y contraseño alberto sirve para el login

El admin de BD es usuario admin contraseña usuario1

La RDS es: proyectoiaw.czyei6ymdmog.us-east-1.rds.amazonaws.com

LA IP ES: 3.208.102.195
IES Gran Capitán -- C/. Arcos de la Frontera, S/N -- 14014 Córdoba -- 957-379710
http://www.iesgrancapitan.org – http://www.iesgrancapitan.org/blog04 -- informatica@iesgrancapitan.org
