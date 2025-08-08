 README.md 
# Control de Versiones y Git

##  Descripción del Proyecto

Este proyecto tiene como finalidad investigar y comprender el concepto de control de versiones, su utilidad en el desarrollo de software, y el funcionamiento básico de la herramienta **Git**, incluyendo los comandos más utilizados desde la línea de comandos.


##  ¿Qué es el Control de Versiones?

El **control de versiones** es un sistema que permite registrar los cambios realizados en los archivos a lo largo del tiempo. Su objetivo principal es facilitar el seguimiento, comparación, restauración y colaboración en proyectos, especialmente en el desarrollo de software.

### Utilidades del Control de Versiones

- Recuperar versiones anteriores de archivos.
- Comparar versiones y ver diferencias.
- Colaborar en equipo sin sobrescribir cambios.
- Llevar un historial detallado de cada modificación.


##  Funcionamiento Básico de Git

**Git** es un sistema de control de versiones distribuido, lo que significa que cada desarrollador tiene una copia completa del historial del proyecto.

### Comandos básicos

| Comando   | Descripción                                                                 |
|-----------|-----------------------------------------------------------------------------|
| \`git init\`     | Inicializa un nuevo repositorio Git local.                              |
| \`git status\`   | Muestra el estado de los archivos en el repositorio.                   |
| \`git add .\`    | Añade todos los archivos al área de preparación (staging).             |
| \`git commit -m "mensaje"\` | Registra los cambios añadidos con un mensaje.                |
| \`git push\`     | Envía los commits al repositorio remoto.                               |
| \`git pull\`     | Descarga y fusiona los cambios desde el repositorio remoto.            |
| \`git branch\`   | Lista las ramas existentes o crea una nueva.                           |
| \`git merge\`    | Fusiona una rama con la actual.                                        |
| \`git checkout\` | Cambia entre ramas o restaura archivos.                                |


## Uso Básico de Git desde la Línea de Comandos

1. **Clonar un repositorio remoto:**
   \`\`\`bash
   git clone 
   \`\`\`

2. **Crear un nuevo repositorio local:**
   \`\`\`bash
   git init
   \`\`\`

3. **Agregar archivos al área de staging:**
   \`\`\`bash
   git add .
   \`\`\`

4. **Crear un commit con mensaje:**
   \`\`\`bash
   git commit -m "Primera versión"
   \`\`\`

5. **Enlazar con un repositorio remoto:**
   \`\`\`bash
   git remote add origin 
   \`\`\`

6. **Enviar los cambios al repositorio remoto:**
   \`\`\`bash
   git push -u origin main
   \`\`\`

7. **Actualizar tu repositorio con cambios remotos:**
   \`\`\`bash
   git pull
   \`\`\`


## Conclusión

Git y el control de versiones son fundamentales para el trabajo colaborativo, seguro y ordenado en proyectos de desarrollo de software. Dominar sus comandos básicos es esencial para cualquier programador o equipo de desarrollo.

