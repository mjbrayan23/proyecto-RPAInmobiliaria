# proyecto-RPAInmobiliaria
El objetivo de este proyecto es desarrollar una aplicación de software que permita a la empresa RPA Inmobiliaria digitalizar y automatizar sus procesos administrativos. 

El producto final esperado del proyecto para RPA INMOBILIARIA es un sistema de gestión de propiedades integral y digitalizado que proporcione las siguientes funcionalidades y beneficios:
1.	Automatización de la Gestión de Cuotas: Un módulo para manejar el cobro, seguimiento y reporte de las cuotas de mantenimiento de los 36 departamentos del condominio Cuauhtémoc.
2.	Gestión Administrativa de Inmuebles: Capacidad para administrar las tareas de mantenimiento, resguardo de la propiedad y cualquier otra actividad administrativa relacionada con la gestión de inmuebles.
3.	Supervisión de Mantenimiento: Funcionalidad para programar, supervisar y documentar las actividades de mantenimiento, así como la administración del personal a cargo de estas tareas.
4.	Digitalización de Procesos: Transición completa de los procesos en papel a un sistema digital, permitiendo un acceso y manejo más eficiente de la información relacionada con la gestión de las propiedades.
5.	Interfaz de Usuario Intuitiva: Una interfaz fácil de usar que sea accesible para los administradores de la inmobiliaria y otros usuarios sin necesidad de conocimientos técnicos avanzados.
6.	Documentación y Capacitación: Documentación completa del sistema y materiales de capacitación para facilitar una transición suave para los usuarios del sistema.
7.	Soporte y Mantenimiento: Un plan de soporte técnico para ayudar a los usuarios con cualquier problema que pueda surgir y proporcionar mantenimiento continuo para mejorar el sistema.
8.	Seguridad y Conformidad: Asegurar que el sistema cumpla con todas las regulaciones pertinentes y mantener la seguridad de todos los datos de los inquilinos y la propiedad.
El sistema estará diseñado para ser robusto, seguro y escalable, permitiendo a RPA INMOBILIARIA adaptarse a medida que crece y se expande su portafolio de propiedades. Este producto final no solo mejorará la eficiencia operativa, sino que también mejorará la experiencia del cliente y proporcionará a la empresa una ventaja competitiva en el mercado.

En resumen: El resultado final del proyecto para RPA INMOBILIARIA será un sistema de gestión de propiedades digitalizado y completo que transformará la administración manual de inmuebles en un proceso automatizado, eficiente y seguro. Este sistema proporcionará una interfaz de usuario intuitiva para la gestión de cuotas, el seguimiento del mantenimiento y la administración del personal, facilitando la transición del papel al digital y mejorando significativamente la eficiencia operativa y la satisfacción del cliente. Con funcionalidades robustas, documentación detallada y soporte técnico, el sistema está diseñado para ser escalable y adaptable a las necesidades futuras de la empresa, estableciendo una base sólida para el crecimiento y la expansión de RPA INMOBILIARIA.


# Fase lV del proyecto (resultados y documentación)
# Sistema de Gestión Inmobiliaria
## Tabla de Contenido 
- [Descripción](#descripción)
- [Problema](#problema)
- [Solución](#solución)
- [Arquitectura](#arquitectura)
- [Servidores](#Servidores)
- [BD](#BD)
- [Adicionales](#Adicionales)
- [Versión-Java](#Versión-Java)
- [Dependencias](#Dependencias)
- [Configuración-Instalación](#Configuración-Instalación)
- [Configuración-Producto](#Configuración-Producto)
- [Uso](#Uso)
- [Contribución](#Contribución)
- [Roadmap](Roadmap)

## Descripción
El proyecto consiste en el desarrollo de un sistema digital integral para la gestión de propiedades de la empresa RPA Inmobiliaria. El sistema busca automatizar y optimizar los procesos administrativos y operativos relacionados con la administración de condominios.

## Problema
RPA Inmobiliaria actualmente lleva todos sus procesos de forma manual a través de papel. Esto genera ineficiencias, pérdida de información y dificultad para escalar. Algunos problemas específicos son:
- Demora en el procesamiento manual de pagos de cuotas
- Falta de trazabilidad en las tareas de mantenimiento
- Alta probabilidad de errores humanos
- Imposibilidad de acceder a información de manera rápida y sencilla

## Solución
La solución consiste en una plataforma web que digitaliza los procesos en 4 módulos principales:
- Gestión de inquilinos y unidades
- Procesamiento de pagos y cuotas
- Coordinación de mantenimientos
- Análisis de métricas e informes

Esto permite automatizar tareas manuales, reducir errores, mejorar eficiencia y satisfacción del cliente.

## Arquitectura
Infraestructura: El sistema debe estar alojado en la nube, utilizando servicios como AWS o Azure. Esto proporcionará escalabilidad, redundancia y seguridad.
Tecnología: El sistema debe utilizar RPA para automatizar las tareas repetitivas y manuales. Las herramientas de RPA más comunes son UiPath, Blue Prism y Automation Anywhere.
Datos: Los datos del sistema deben almacenarse en una base de datos relacional, como MySQL o PostgreSQL. Esto permitirá realizar consultas complejas y análisis de datos.
La siguiente imagen muestra un diagrama de arquitectura de alto nivel para el proyecto:

El diagrama muestra los siguientes componentes:

Frontend: La interfaz de usuario del sistema, que estará disponible en los navegadores web y móviles.
Backend: El núcleo del sistema, que incluye la lógica de negocio y la integración con los sistemas existentes.
RPA: El motor de RPA, que automatiza las tareas repetitivas y manuales.
Base de datos: La base de datos que almacena los datos del sistema.
La arquitectura propuesta proporciona una base sólida para el proyecto. Es escalable, segura y utiliza las tecnologías más adecuadas para el trabajo.

Además de los componentes mencionados anteriormente, el sistema también puede incluir los siguientes componentes:

Servicios de seguridad: Para proteger los datos del sistema contra el acceso no autorizado.
Servicios de análisis: Para analizar los datos del sistema y generar informes.
Servicios de integración: Para integrar el sistema con otros sistemas existentes.
La inclusión de estos componentes adicionales dependerá de los requisitos específicos del proyecto.

![INMOBILIARIA drawio](https://github.com/mjbrayan23/proyecto-RPAInmobiliaria/assets/84410509/b205d244-156b-41c3-9755-144f06ffb0f4)

# Requisitos del Sistema

## Servidores
- **Aplicación:** Apache Tomcat 9.x
- **Web:** Nginx 1.18.x
- **Balanceador de Carga:** AWS Elastic Load Balancing

## BD
- **Sistema de Gestión de Bases de Datos:** PostgreSQL 12.5
- **Configuración:** 
  - Tamaño de Instancia: db.m4.large
  - Almacenamiento: SSD de 500 GB

## Adicionales
- **Framework de Seguridad:** Spring Security 5.4.x
- **Autenticación:** OAuth 2.0
- **Librerías de Frontend:** React 17.x, Redux 4.x

## Versión-Java
- **JDK:** OpenJDK 11

## Dependencias
- **Gestión de Paquetes:** Maven 3.6.x
- **Control de Versiones:** Git 2.30.x
```

# Instalación

## Configuración-Instalación

Para iniciar el entorno de desarrollo en tu máquina local, sigue estos pasos:

```bash
# Clonar el repositorio
git clone https://github.com/mjbrayan23/proyecto-RPAInmobiliaria.git

# Cambiar al directorio del proyecto
cd proyecto-RPAInmobiliaria

# Instalar las dependencias de Node.js (asegúrate de tener Node.js instalado)
npm install

# Si el proyecto utiliza una base de datos, configura las variables de entorno para la conexión a la base de datos

# Iniciar la aplicación en modo de desarrollo
npm start

# Ejecutar pruebas
npm test

# Construir la aplicación para producción
npm run build

# Iniciar el servidor en modo producción (puede requerir un servidor web como nginx o Apache)
npm run serve

# Iniciar sesión en Heroku CLI (debes tener Heroku CLI instalado)
heroku login

# Crear una nueva aplicación en Heroku
heroku create nombre-de-tu-app

# Desplegar la aplicación en Heroku
git push heroku main

# Ejecutar migraciones de base de datos o cualquier paso de configuración final necesario
heroku run npm run migrate

Recuerda reemplazar `nombre-de-tu-app` con el nombre que le quieras dar a tu aplicación en Heroku y ajustar cualquier comando según las necesidades específicas de tu proyecto.
```

# Configuración

## Configuración-Producto

Antes de ejecutar la aplicación, necesitas configurar los archivos de entorno:

```bash
# Copia el archivo de ejemplo de configuración y ajusta los valores según tu entorno
cp .env.example .env

# Edita el archivo .env con las variables de entorno necesarias
# Por ejemplo, define las conexiones a la base de datos, claves de API, etc.

# Por ejemplo, si necesitas instalar un servidor de base de datos como MySQL:
sudo apt-get install mysql-server

# O si necesitas configurar un servidor web como Nginx:
sudo apt-get install nginx

Este formato proporciona un esqueleto básico para documentar los pasos de configuración. Deberás personalizar el contenido con los detalles específicos de tu proyecto y su entorno.
```

# Uso

## Para Usuarios Finales

Los usuarios finales pueden utilizar la plataforma de gestión inmobiliaria siguiendo estos pasos:

### Iniciar Sesión
- Visita la página de inicio de sesión.
- Ingresa tus credenciales proporcionadas por el administrador del sistema.

### Gestión de Inquilinos y Unidades
- Accede al módulo de 'Inquilinos' para ver y editar detalles de los inquilinos.
- Utiliza la sección 'Unidades' para gestionar la información de las propiedades.

### Procesamiento de Pagos
- En el módulo de 'Pagos', revisa las cuotas pendientes.
- Realiza pagos utilizando los métodos disponibles y obtén recibos instantáneos.

### Reportes
- Genera informes financieros y de mantenimiento desde la sección 'Reportes'.

### Soporte
- Para ayuda adicional, visita la sección de 'Soporte' o contacta al equipo técnico.

## Para Administradores del Sistema

Los administradores pueden gestionar la plataforma con las siguientes herramientas y procesos:

### Configuración del Sistema
- Asegúrate de revisar la configuración del sistema y personalizar los ajustes desde el panel de administración.

### Gestión de Usuarios
- Administra las cuentas de usuario, asigna roles y permisos desde la sección 'Usuarios'.

### Actualizaciones de la Plataforma
- Mantén el sistema actualizado siguiendo el procedimiento de actualización detallado en la sección 'Mantenimiento'.

### Seguridad y Respaldo
- Implementa políticas de seguridad regularmente y realiza copias de seguridad de datos para proteger contra pérdidas de información.

### Análisis de Datos
- Utiliza las herramientas de análisis para revisar el rendimiento del negocio y tomar decisiones basadas en datos.

Recuerda consultar la documentación técnica detallada y los manuales de usuario proporcionados para un entendimiento completo de todas las funcionalidades.

# Contribución

Agradecemos las contribuciones de todos los usuarios. Si deseas contribuir al proyecto, por favor sigue estos pasos:

## Configuración Inicial
1. Clona el repositorio:
   ```bash
   git clone https://github.com/mjbrayan23/proyecto-RPAInmobiliaria.git
   
## Haciendo-Cambios:
1. Crea un nuevo branch para tus cambios:
```bash
  git checkout -b nombre-de-tu-branch
```
2. Haz tus cambios en el código localmente.
3. Asegúrate de seguir las guías de estilo del código y añade pruebas si es posible.

## Pull Request
1. Haz commit a tus cambios:
```bash
  git commit -m "Añade una descripción detallada de tus cambios"
```
2.  Envía tus cambios al repositorio remoto:
```bash
  git push origin nombre-de-tu-branch
```
3. Ve a GitHub y crea un nuevo Pull Request desde tu branch.
4. Describe los cambios y cualquier otro detalle relevante para tu PR.

## Después del Pull Request
1. Espera feedback o la aprobación del Pull Request por parte de los mantenedores del proyecto.
2. Puede que se te pida hacer modificaciones adicionales.
4. Una vez aprobado, un mantenedor hará merge de tu PR.
5. Asegúrate de revisar la documentación del proyecto y cualquier otra guía de contribución proporcionada para más detalles sobre el proceso de contribución.
```bash
Asegúrate de personalizar las instrucciones de contribución para adaptarse a las políticas y procedimientos específicos de tu proyecto.
```
# Roadmap

El desarrollo futuro del proyecto `proyecto-RPAInmobiliaria` incluirá varias mejoras y nuevas funcionalidades. Algunos de los requerimientos planificados son:

- **Integración de Pagos en Línea:** Implementar opciones de pago en línea para facilitar transacciones más rápidas y seguras.
- **Módulo de Inteligencia Artificial:** Desarrollar un sistema de análisis predictivo para identificar tendencias del mercado inmobiliario.
- **Aplicación Móvil:** Crear una aplicación móvil para proporcionar acceso fácil y rápido a la plataforma.
- **Mejoras en la Interfaz de Usuario:** Continuar mejorando la experiencia del usuario, basándose en feedback y estudios de usabilidad.
- **Funcionalidades de Reportes Avanzados:** Ampliar las capacidades de generación de informes para ofrecer análisis más profundos y personalizables.

Estos elementos se implementarán progresivamente, con el objetivo de mejorar continuamente la plataforma y satisfacer las necesidades de los usuarios.


![image](https://github.com/mjbrayan23/proyecto-RPAInmobiliaria/assets/84410509/650cb700-d653-46ce-964f-d0c6cc8abff1)

![image](https://github.com/mjbrayan23/proyecto-RPAInmobiliaria/assets/84410509/1c7ff547-ac1e-48aa-84a2-4d68782d45eb)

![image](https://github.com/mjbrayan23/proyecto-RPAInmobiliaria/assets/84410509/211469c2-d07c-4c83-a313-b47901ac42ff)

![image](https://github.com/mjbrayan23/proyecto-RPAInmobiliaria/assets/84410509/242be6bb-a28d-40c3-a274-813d67a20088)









