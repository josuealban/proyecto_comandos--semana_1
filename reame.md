# Práctica N.º 1: Creación y manipulación de archivos mediante comandos de Linux

## 1. Título

Creación, organización y manipulación de archivos y directorios mediante el uso de comandos de Linux y Git Bash.

## 2. Tiempo de duración

La práctica tuvo una duración aproximada de 30 minutos, durante los cuales se realizaron diferentes actividades relacionadas con la administración de archivos y directorios mediante la terminal Git Bash.

Entre las actividades desarrolladas se encuentran la creación de carpetas, generación de archivos de texto, copia y movimiento de archivos, redirección de contenido, eliminación de archivos y directorios, y almacenamiento del historial de comandos ejecutados.
## 3. Fundamentos teóricos

### 3.1. Sistema operativo Linux

Linux es un sistema operativo de código abierto, basado en el núcleo Linux, que permite administrar los recursos de un equipo y ejecutar diferentes aplicaciones. Es ampliamente utilizado en servidores, desarrollo de software y administración de sistemas debido a su estabilidad, seguridad y flexibilidad.

Una de sus principales características es la posibilidad de interactuar con el sistema mediante una terminal, permitiendo realizar diferentes tareas utilizando comandos.

### 3.2. Terminal y línea de comandos (CLI)

La interfaz de línea de comandos, conocida como CLI (Command Line Interface), permite al usuario interactuar con el sistema operativo mediante instrucciones escritas.

A diferencia de las interfaces gráficas, donde se utilizan ventanas, botones y menús, la terminal permite ejecutar operaciones directamente mediante comandos.

Su utilización resulta especialmente útil para automatizar tareas, administrar archivos, configurar sistemas y trabajar en entornos de desarrollo.

### 3.3. Git Bash

Git Bash es una herramienta que proporciona un entorno de terminal compatible con numerosos comandos utilizados en sistemas Unix y Linux dentro de Windows.

Esta herramienta permite ejecutar instrucciones para crear carpetas, modificar archivos, navegar entre directorios y utilizar Git para el control de versiones.

Durante esta práctica se utilizó Git Bash para realizar las actividades de creación y manipulación de archivos y directorios.

### 3.4. Comandos básicos para la manipulación de archivos

Los comandos permiten realizar operaciones sobre los archivos y directorios del sistema.

Entre los principales comandos utilizados se encuentran:

| Comando | Función |
|---|---|
| `pwd` | Muestra la ubicación actual del usuario. |
| `mkdir` | Crea nuevos directorios. |
| `cd` | Permite cambiar de directorio. |
| `ls` | Muestra los archivos y carpetas existentes. |
| `touch` | Crea archivos vacíos o actualiza sus marcas de tiempo. |
| `echo` | Muestra texto y permite escribirlo en archivos mediante redirección. |
| `cat` | Muestra o concatena el contenido de archivos. |
| `cp` | Copia archivos de una ubicación a otra. |
| `mv` | Mueve archivos o cambia sus nombres. |
| `rm` | Elimina archivos. |
| `rmdir` | Elimina directorios vacíos. |
| `history` | Muestra el historial de comandos de la sesión. |

### 3.5. Redirección de contenido y tuberías

La redirección permite enviar la salida de un comando hacia un archivo en lugar de mostrarla únicamente en la terminal.

Existen diferentes operadores que permiten controlar cómo se almacena la información:

- `>`: redirecciona la salida y sobrescribe el contenido del archivo de destino.
- `>>`: añade información al final de un archivo sin eliminar su contenido anterior.
- `|`: conecta la salida de un comando con la entrada de otro, permitiendo trabajar con varios comandos de manera conjunta.

Por ejemplo, el comando `cat documentos/notas.txt > documentos/resumen.txt` permite copiar el contenido de un archivo de texto hacia otro mediante redirección.

Por otra parte, el comando `history | cat > tarea-s1-josue_alban.txt` permite enviar el historial de comandos a otro proceso mediante una tubería y almacenarlo en un archivo de texto.

Estos operadores son importantes porque facilitan la automatización de procesos y permiten realizar tareas de manera más eficiente.

### 3.6. Importancia de los comandos en el desarrollo de software

Conocer los comandos básicos de Linux representa una ventaja para los desarrolladores de software, ya que permite trabajar con archivos, ejecutar aplicaciones y administrar proyectos desde la terminal.

Aunque actualmente existen herramientas gráficas que facilitan estas actividades, la línea de comandos continúa siendo útil por su rapidez, flexibilidad y capacidad para automatizar tareas repetitivas.

Por esta razón, comprender su funcionamiento ayuda a desarrollar habilidades técnicas que pueden aplicarse en diferentes entornos de trabajo.

![Figura 3-1. Representación del funcionamiento de la terminal Git Bash y su interacción con el sistema de archivos mediante comandos.](evidencias%20%28proximo%20a%20imgs%29/flujo.svg)
## 4. Conocimientos previos

Para realizar esta práctica es necesario contar con conocimientos básicos sobre el funcionamiento de los sistemas operativos y la administración de archivos y directorios.

Entre los principales conocimientos necesarios se encuentran:

- **Manejo básico del sistema operativo:** conocer cómo acceder a las carpetas, archivos y herramientas disponibles en Windows.
- **Uso de la terminal:** comprender cómo ingresar y ejecutar instrucciones mediante una interfaz de línea de comandos (CLI).
- **Comandos básicos de Linux:** tener conocimientos iniciales sobre comandos como `cd`, `ls`, `mkdir`, `cp`, `mv` y `rm`.
- **Administración de archivos y directorios:** comprender la diferencia entre crear, copiar, mover, renombrar y eliminar archivos.
- **Rutas de archivos:** identificar rutas relativas y absolutas para localizar archivos y carpetas dentro del sistema.
- **Redirección de información:** conocer el funcionamiento básico de los operadores `>`, `>>` y las tuberías `|`.
- **Uso de Git Bash:** saber abrir y utilizar esta herramienta para ejecutar comandos desde Windows.
- **Manejo básico de editores de texto:** crear y modificar archivos de texto para almacenar información.
## 5. Objetivos a alcanzar

### Objetivo general

Aplicar los comandos básicos de Linux mediante la terminal Git Bash para realizar operaciones de creación, organización, manipulación y eliminación de archivos y directorios, comprendiendo su funcionamiento y utilidad en la administración del sistema.

### Objetivos específicos

- Crear una estructura de directorios utilizando comandos básicos de la terminal.
- Generar y modificar archivos de texto mediante comandos y operadores de redirección.
- Aplicar los comandos `cp` y `mv` para copiar, mover y renombrar archivos dentro de diferentes directorios.
- Utilizar los operadores `>` y `>>` para redireccionar información y agregar contenido a los archivos.
- Emplear tuberías para conectar comandos y almacenar el historial de instrucciones ejecutadas.
- Eliminar archivos y directorios de manera controlada utilizando los comandos `rm` y `rmdir`.
- Comprender la importancia de la línea de comandos como herramienta para la administración de archivos y el desarrollo de software.
## 6. Equipo necesario

Para el desarrollo de esta práctica se utilizaron los siguientes recursos:

### Hardware

- Computador de escritorio o portátil.
- Teclado y mouse.
- Espacio de almacenamiento disponible para crear y manipular archivos.

### Software

- **Sistema operativo:** Windows.
- **Terminal:** Git Bash, utilizada para ejecutar comandos compatibles con entornos Unix y Linux.
- **Editor de texto:** Antigravity, utilizado para elaborar y organizar el informe en formato Markdown.
- **Navegador web:** para acceder a GitHub y consultar documentación relacionada con los comandos.
- **Git:** herramienta de control de versiones para gestionar los archivos del proyecto.
- **GitHub:** plataforma utilizada para almacenar el repositorio y presentar las evidencias de la práctica.

### Recursos adicionales

- Conexión a Internet para acceder a GitHub.
- Guía de la práctica proporcionada por el docente.
- Capturas de pantalla como evidencia de los procedimientos realizados.

## 7. Material de apoyo

Para el desarrollo de esta práctica se utilizaron los siguientes materiales de apoyo:

- **Guía de la asignatura:** documento proporcionado por el docente con las instrucciones para realizar la práctica de creación y manipulación de archivos en Linux.
- **Documentación de Git:** información sobre el funcionamiento de Git Bash y el uso de herramientas de línea de comandos.
- **Manual de comandos GNU/Linux:** referencia para comprender el funcionamiento de comandos como `mkdir`, `cd`, `ls`, `cp`, `mv`, `rm` y `rmdir`.
- **Documentación de Bash:** material de consulta sobre redirección de contenido, tuberías y ejecución de comandos.
- **Plantilla de informe académico:** estructura proporcionada por el docente para documentar el procedimiento y los resultados de la práctica.

### Enlaces de consulta

- [Documentación oficial de Git](https://git-scm.com/doc)
- [Manual de Bash - GNU](https://www.gnu.org/software/bash/manual/)
- [Manual de GNU Coreutils](https://www.gnu.org/software/coreutils/manual/)
- [Plantilla del informe](https://github.com/maguaman2/informe-tendencias)
## 8. Procedimiento

Para el desarrollo de esta práctica se utilizó la terminal Git Bash en Windows, mediante la cual se ejecutaron diferentes comandos para crear, modificar, copiar, mover y eliminar archivos y directorios.

### Paso 1. Creación de la estructura de directorios

Primero se creó una carpeta principal llamada `proyecto_comandos`, destinada a almacenar todos los archivos y directorios utilizados durante la práctica.

Posteriormente, se ingresó a esta carpeta y se crearon tres subdirectorios: `documentos`, `imagenes` y `scripts`.

**Comandos utilizados:**

```bash
mkdir proyecto_comandos
cd proyecto_comandos
mkdir documentos imagenes scripts
ls
```

Estos comandos permitieron organizar el espacio de trabajo y comprobar la creación de los directorios.

**Evidencia:**

![Figura 8-1. Verificación de la estructura de directorios mediante Git Bash.](<evidencias (proximo a imgs)/8-1 Verificacion de   estructura.png>)

### Paso 2. Creación y modificación de archivos de texto

Dentro del directorio `documentos` se creó un archivo llamado `notas.txt`, al cual se agregaron tres líneas de texto utilizando el comando `echo` y los operadores de redirección.

**Comandos utilizados:**

```bash
echo "Estoy aprendiendo los comandos basicos de Linux." > documentos/notas.txt
echo "La terminal permite administrar archivos y carpetas." >> documentos/notas.txt
echo "Estos conocimientos son utiles para desarrollar software." >> documentos/notas.txt
cat documentos/notas.txt
```

El operador `>` permitió crear el archivo y escribir su contenido inicial, mientras que `>>` permitió agregar nuevas líneas sin eliminar la información anterior.

### Paso 3. Copia y cambio de nombre de archivos

Se realizó una copia del archivo `notas.txt` desde la carpeta `documentos` hacia la carpeta `scripts`.

Posteriormente, se cambió el nombre de la copia a `backup_notas.txt` utilizando el comando `mv`.

**Comandos utilizados:**

```bash
cp documentos/notas.txt scripts/notas.txt
mv scripts/notas.txt scripts/backup_notas.txt
```

Esta actividad permitió comprender la diferencia entre copiar un archivo y cambiar su nombre.

### Paso 4. Movimiento de archivos entre directorios

Una vez creada la copia de seguridad, se trasladó el archivo `backup_notas.txt` desde la carpeta `scripts` hacia la carpeta `imagenes`.

**Comando utilizado:**

```bash
mv scripts/backup_notas.txt imagenes/
```

Mediante este procedimiento se comprobó que el comando `mv` permite cambiar la ubicación de un archivo sin necesidad de crear una copia adicional.

### Paso 5. Redirección y concatenación de contenido

Se creó un archivo llamado `resumen.txt` dentro del directorio `documentos`.

Posteriormente, se redireccionó el contenido de `notas.txt` hacia `resumen.txt` y se añadió una nueva línea sin sobrescribir el contenido existente.

**Comandos utilizados:**

```bash
touch documentos/resumen.txt
cat documentos/notas.txt > documentos/resumen.txt
echo "He aprendido a utilizar la redireccion y concatenacion de contenido." >> documentos/resumen.txt
cat documentos/resumen.txt
```

Con esta actividad se comprendió el funcionamiento de los operadores de redirección y su utilidad para almacenar información.

**Evidencia:**

![Figura 8-2. Visualización del contenido de los archivos notas.txt y resumen.txt mediante el comando cat.](<evidencias (proximo a imgs)/8-2_visualizacion_de_contenido.png>)

### Paso 6. Eliminación de archivos y directorios

Se eliminó el archivo `backup_notas.txt` que se encontraba dentro de la carpeta `imagenes`.

Una vez que el directorio quedó vacío, se procedió a eliminarlo mediante el comando `rmdir`.

**Comandos utilizados:**

```bash
rm imagenes/backup_notas.txt
rmdir imagenes
```

Esta actividad permitió diferenciar la eliminación de archivos mediante `rm` y la eliminación de directorios vacíos mediante `rmdir`.

### Paso 7. Almacenamiento del historial de comandos

Finalmente, se utilizó el comando `history` para obtener el registro de instrucciones ejecutadas durante la práctica.

El historial se almacenó en un archivo de texto mediante el uso de una tubería y redirección.

**Comando utilizado:**

```bash
history | cat > tarea-s1-josue_alban.txt
```

El archivo generado contiene el historial disponible en la sesión de Git Bash y constituye una evidencia de los comandos utilizados.

**Evidencia:**

![Figura 8-3. Registro del historial de comandos ejecutados en Git Bash.](<evidencias (proximo a imgs)/8-3_historial_de_comandos.png>)

## 9. Resultados esperados

Durante el desarrollo de la práctica se aplicaron diferentes comandos básicos de Linux mediante la terminal Git Bash, permitiendo comprender su funcionamiento en la creación, organización y manipulación de archivos y directorios.

Entre los principales resultados obtenidos se encuentran:

- **Creación de directorios:** se creó correctamente la carpeta `proyecto_comandos` y sus respectivos subdirectorios.
- **Manipulación de archivos:** se utilizaron comandos para crear archivos de texto, copiar información, cambiar nombres y mover archivos entre directorios.
- **Redirección de contenido:** se aplicaron los operadores `>` y `>>` para escribir información y agregar nuevas líneas sin sobrescribir el contenido existente.
- **Eliminación de archivos:** se utilizaron los comandos `rm` y `rmdir` para eliminar archivos y directorios de manera controlada.
- **Registro de comandos:** se generó el archivo `tarea-s1-josue_alban.txt`, que contiene el historial disponible de las instrucciones ejecutadas durante la práctica.

### 9.1. Estructura final del proyecto

Una vez finalizadas las actividades, la carpeta principal conserva los archivos de texto generados, el historial de comandos y las evidencias de la práctica.

```text
proyecto_comandos/
├── documentos/
│   ├── notas.txt
│   └── resumen.txt
├── scripts/
├── evidencias/
├── README.md
└── tarea-s1-josue_alban.txt
```

La carpeta `imagenes` fue eliminada como parte del procedimiento solicitado.

### 9.2. Evidencia del resultado final

![Figura 9-1. Estructura final de archivos y directorios después de ejecutar los comandos en Git Bash.](evidencias/9-1_resulatados.png)

### 9.3. Análisis de los resultados

La práctica permitió comprender de manera más clara cómo se administran archivos y directorios utilizando una interfaz de línea de comandos.

Uno de los aspectos más importantes fue aprender a diferenciar las funciones de los comandos `cp` y `mv`, así como el funcionamiento de los operadores de redirección.

También se pudo observar que la terminal facilita la ejecución de diferentes operaciones sin necesidad de utilizar herramientas gráficas.

En conclusión, los resultados de esta práctica permitieron fortalecer los conocimientos básicos sobre el manejo de la terminal y reconocer su utilidad dentro del desarrollo de software.
## 10. Bibliografía

- Free Software Foundation. (s. f.). *Bash reference manual*. GNU Project. https://www.gnu.org/software/bash/manual/

- Free Software Foundation. (s. f.). *GNU coreutils manual*. GNU Project. https://www.gnu.org/software/coreutils/manual/

- Git. (s. f.). *Git documentation*. https://git-scm.com/doc

- Git. (s. f.). *Git for Windows*. https://gitforwindows.org/

- The Linux Foundation. (s. f.). *Linux*. https://www.linuxfoundation.org/