# PRIMEROS PASOS  
## Uso de Git y GitHub: Introducción al control de versiones y colaboración en el desarrollo de software. 
En esta sección, aprenderás sobre Git y GitHub, dos herramientas fundamentales para el control de versiones y la colaboración en el desarrollo de software. Descubrirás cómo utilizar Git para llevar un registro de los cambios en tu código y cómo aprovechar las características de GitHub para trabajar en equipo, compartir proyectos y contribuir a la comunidad de programadores.

**Git:**
Git es un sistema de control de versiones distribuido ampliamente utilizado en el desarrollo de software. Permite a los programadores llevar un registro de los cambios realizados en el código fuente de un proyecto a lo largo del tiempo. Con Git, puedes crear "repositorios" que contienen el historial completo de cambios, ramas de desarrollo y colaboradores.

Git es útil porque te permite:

1. Controlar versiones: Puedes rastrear y comparar diferentes versiones del código, lo que facilita revertir cambios o fusionar diferentes líneas de desarrollo.
2. Trabajar en equipo: Varios desarrolladores pueden colaborar en un mismo proyecto, trabajando en diferentes ramas y fusionando sus cambios de manera controlada.
3. Experimentar y explorar: Puedes crear ramas separadas para probar nuevas características sin afectar la versión principal del código.

**GitHub:**

GitHub es una plataforma basada en web que utiliza Git para alojar, administrar y compartir proyectos de software. Proporciona una interfaz amigable para trabajar con repositorios Git, y agrega características sociales y colaborativas.

GitHub es importante porque:

1. Permite colaboración: Puedes invitar a otros desarrolladores a contribuir en tus proyectos o unirte a proyectos existentes. Esto facilita el trabajo en equipo y la revisión de código.
2. Compartir y aprender: Puedes explorar proyectos de código abierto, aprender de otros programadores y compartir tus propios proyectos con la comunidad.
3. Despliegue y hosting: GitHub proporciona opciones para alojar y desplegar aplicaciones web, lo que facilita la puesta en marcha de tus proyectos.

Ahora, aquí tienes una guía básica para empezar a usar Git y GitHub:

1. **Instalar Git:** Descarga e instala Git en tu computadora desde el sitio web oficial (https://git-scm.com/). Sigue las instrucciones para tu sistema operativo.

2. **Configurar Git:** Configura tu nombre de usuario y dirección de correo electrónico en Git. Utiliza los siguientes comandos en la terminal:

```shell
git config --global user.name "Tu Nombre"
git config --global user.email "tu@email.com"
```

3. **Crear un repositorio local:** En tu computadora, crea una carpeta para tu proyecto y abre la terminal en esa ubicación. Ejecuta el siguiente comando para iniciar un repositorio Git:

```shell
git init
```

4. **Realizar cambios y hacer commit:** Agrega tus archivos al repositorio y haz tu primer commit. Por ejemplo, si tienes un archivo llamado `index.html`, ejecuta los siguientes comandos:

```shell
git add index.html
git commit -m "Primer commit"
```

5. **Crear un repositorio en GitHub:** Ve a la página de inicio de GitHub (https://github.com/) y crea una cuenta si aún no tienes una. Luego, crea un nuevo repositorio en GitHub con un nombre descriptivo.

6. **Conectar repositorio local con GitHub:** En la página del repositorio en GitHub, encontrarás la URL del repositorio. En la terminal, ejecuta el siguiente comando para conectar tu repositorio local con el repositorio remoto en GitHub:

```shell
git remote add origin URL_DEL_REPOSITORIO
```

7. **Subir cambios a GitHub:** Envía tus cambios locales al repositorio remoto en GitHub ejecutando

