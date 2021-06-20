# Calculadora de coste de impresión
[![Solicitudes de funciones](https://img.shields.io/github/issues-raw/alejimdro/tests/enhancement?color=yellow&label=Solicitudes%20de%20funciones%20abiertas)](https://github.com/alejimdro/tests/issues?utf8=✓&q=is%3Aissue+is%3Aopen+label%3Aenhancement+sort%3Areactions-%2B1-desc+)
[![Informes de errores](https://img.shields.io/github/issues-raw/alejimdro/tests/bug?color=yellow&label=Informes%20de%20errores%20abiertos)](https://github.com/alejimdro/tests/issues?utf8=✓&q=is%3Aissue+is%3Aopen+label%3Abug+)
[![Solicitudes de extracción](https://img.shields.io/github/issues-pr-raw/alejimdro/tests?color=yellow&label=Solicitudes%20de%20extracci%C3%B3n%20abiertas)](https://github.com/alejimdro/tests/pulls?utf8=✓&q=is%3Apr+is%3Aopen+)
[![Pacto del Colaborador](https://img.shields.io/badge/Pacto%20del%20Colaborador-2.0-4baaaa.svg)](./CODE_OF_CONDUCT.md)
[![Licencia](https://img.shields.io/github/license/alejimdro/tests?label=Licencia)](./LICENSE)
[![Tamaño del repositorio](https://img.shields.io/github/repo-size/alejimdro/tests?label=Tama%C3%B1o%20del%20repositorio)](https://github.com/alejimdro/tests)

## Índice de contenido

* [1. El repositorio](#1-el-repositorio)
* [2. Descripción del proyecto](#2-descripción-del-proyecto)
* [3. Contribución](#3-contribución)
  - [3.1. Código de conducta](#31-código-de-conducta)
* [4. Requisitos previos](#4-requisitos-previos)
* [5. Métodos de ejecución](#5-métodos-de-ejecución)
  - [5.1. Intérprete de comandos](#51-intérprete-de-comandos)
  - [5.2. Modo interactivo](#52-modo-interactivo)
  - [5.3. Entorno de desarrollo y aprendizaje integrado](#53-entorno-de-desarrollo-y-aprendizaje-integrado)
* [6. Instrucciones de uso](#6-instrucciones-de-uso)
* [7. Demostración](#7-demostración)
* [8. Agradecimientos](#8-agradecimientos)
* [9. Licencia](#9-licencia)

## 1. El repositorio

En este repositorio se lleva a cabo el desarrollo de una calculadora de coste de impresión para la [Universidad de Las Palmas de Gran Canaria](https://www.ulpgc.es) en colaboración con la comunidad de programadores de GitHub. Es concebido no solo como un espacio donde se trabaja en el código y se corrigen errores, sino también como hoja de ruta del proyecto, donde sugerir cambios y proponer nuevas ideas.

**[↑ Volver al principio](#índice-de-contenido)**

## 2. Descripción del proyecto

Una simple y efectiva calculadora de coste de impresión desarrollada para la comunidad universitaria de la Universidad de Las Palmas de Gran Canaria por Alejandro Jiménez ([alejimdro@outlook.com](mailto:alejimdro@outlook.com)).

Este sencillo pero eficiente script le ayudará a conocer con antelación y exactitud cuál es el coste de impresión de un determinado número de páginas, procurando, en todo momento, el aprovechamiento optimizado del importe a pagar.

**[↑ Volver al principio](#índice-de-contenido)**

## 3. Contribución

Además de contribuir a escribir código y solucionar problemas, puede participar en el proyecto de otras maneras, como, por ejemplo:

* [Reportar errores](https://github.com/microsoft/vscode/issues) y [agregar propuestas de funciones](https://github.com/microsoft/vscode/issues) y colaborar en su verificación a medida que se registran
* Revisar los [cambios en el código fuente](https://github.com/microsoft/vscode/pulls)
* Revisar la [documentación](https://github.com/microsoft/vscode-docs) y [enviar solicitudes de extracción](https://github.com/microsoft/vscode/pulls) para corregir errores tipográficos, proponer contenido nuevo o cualquier otro tema

**[↑ Volver al principio](#índice-de-contenido)**

### 3.1. Código de conducta

Tenga en cuenta que el presente proyecto se publica con un [Código de Conducta del Colaborador](./CODE_OF_CONDUCT.md). Al contribuir a este proyecto, usted se compromete a cumplir con sus términos.

**[↑ Volver al principio](#índice-de-contenido)**

## 4. Requisitos previos

Compruebe si su equipo ya dispone de una versión actualizada de Python; para ello, abra el intérprete de comandos e introduzca `python --version` o `python -V`, lo cual generará una salida con la versión de Python instalada.

Por lo general, cualquier versión de Python 3.x será suficiente, pues Python hace todo lo posible por mantener la compatibilidad con versiones anteriores dentro de sus principales versiones.

Las versiones 2.x y 3.x de Python no son intencionadamente compatibles. Si `python` inicia un intérprete de Python 2.x, intente introducir `python3` y compruebe si ya existe una versión actualizada instalada.

Si necesita instalar Python, consulte su [página oficial de descargas](https://www.python.org/downloads/) e instale la versión estable más reciente.

**[↑ Volver al principio](#índice-de-contenido)**

## 5. Métodos de ejecución

Un script, utilizado a menudo para automatizar procesos o realizar tareas específicas, es un archivo de texto que contiene instrucciones escritas en un determinado lenguaje de scripts. Esto significa que la mayoría de scripts pueden ser abiertos y editados con un editor de texto básico; sin embargo, sus comandos solo pueden ser comprendidos y ejecutados por un intérprete apropiado.

A continuación se describen algunas formas convenientes de ejecutar un script de Python en función de su entorno, plataforma, necesidades y habilidades.

**[↑ Volver al principio](#índice-de-contenido)**

### 5.1. Intérprete de comandos

Abra el intérprete de comandos y desplácese hasta el directorio de trabajo que contenga el script de Python; por ejemplo, `cd ~/Desktop/ULPGC/Proyectos/Calculadora`, en Linux o macOS, o `cd \Users\nombre_de_usuario\Desktop\ULPGC\Proyectos\Calculadora`, en Windows.

Una vez se encuentre en el directorio correcto, ejecute el comando `python3 nombre_del_script.py`.

Una alternativa más directa sería escribir `python3` seguido de la ruta del script; por ejemplo, `python3 /Users/nombre_de_usuario/Desktop/ULPGC/Proyectos/Calculadora/nombre_del_script.py`, en Linux o macOS, o `python3 \Users\nombre_de_usuario\Desktop\ULPGC\Proyectos\Calculadora\nombre_del_script.py`, en Windows, y ejecutar dicho comando.

**[↑ Volver al principio](#índice-de-contenido)**

### 5.2. Modo interactivo

El modo interactivo es una forma muy versátil de ejecutar scripts de Python.

Para iniciar dicho modo, abra el intérprete de comandos e invoque al intérprete de Python mediante el comando `python3`.

Una vez invocado el intérprete, por medio de la función integrada [`exec()`](https://docs.python.org/es/3/library/functions.html#exec), que permite la ejecución dinámica de código Python, ejecute la instrucción `exec(open('/Users/nombre_de_usuario/Desktop/ULPGC/Proyectos/Calculadora/nombre_del_script.py').read())`, en Linux o macOS, o `exec(open('\Users\nombre_de_usuario\Desktop\ULPGC\Proyectos\Calculadora\nombre_del_script.py').read())`, en Windows.

**[↑ Volver al principio](#índice-de-contenido)**

### 5.3. Entorno de desarrollo y aprendizaje integrado

Cuando se trata de ejecutar scripts desde un [entorno de desarrollo integrado](https://es.wikipedia.org/wiki/Entorno_de_desarrollo_integrado) (IDE) o un [editor de código fuente](https://es.wikipedia.org/wiki/Editor_de_código_fuente), no solo puede escribir y ejecutar código, sino también depurarlo y modificarlo, así como seleccionar, entre la amplia variedad de alternativas disponibles, el entorno que mejor se adapte a sus necesidades.

Para iniciar su IDE o editor de código fuente predeterminado, en este caso [IDLE](https://docs.python.org/es/3/library/idle.html), el entorno de desarrollo y aprendizaje integrado que forma parte de la distribución estándar de Python, abra el intérprete de comandos e introduzca la instrucción `open -a "IDLE"`, en Linux o macOS, o `start idle`, en Windows, seguida de la ubicación del script a ejecutar; por ejemplo, `open -a "IDLE" /Users/nombre_de_usuario/Desktop/ULPGC/Proyectos/Calculadora/nombre_del_script.py` o `start idle \Users\nombre_de_usuario\Desktop\ULPGC\Proyectos\Calculadora\nombre_del_script.py`.

Por el contrario, para abrir un script de forma manual, haga clic secundario sobre este, elija **Edit with IDLE** o, en su defecto, **Abrir con** y, a continuación, seleccione **IDLE**.

Para abrir un script directamente desde IDLE, haga clic en **File**, seleccione **Open** y, una vez localizado el script, haga clic en **Open**.

Finalmente, para ejecutar un script abierto con IDLE, haga clic en **Run** y, a continuación, seleccione **Run Module**, o bien presione la tecla **F5** de su teclado.

**[↑ Volver al principio](#índice-de-contenido)**

## 6. Instrucciones de uso

Ingrese, en primer lugar, el coste de impresión por página tanto en blanco y negro como a color. A continuación, indique el número de páginas por hoja seguido de un número entero válido de páginas a imprimir y, una vez haya finalizado, inserte la palabra **_hecho_** o el número **_0_**.

**[↑ Volver al principio](#índice-de-contenido)**

## 7. Demostración

<p align="center">
  <img alt="VS Code in action" src="https://github.com/alejimdro/tests/blob/main/demo.gif">
</p>

**[↑ Volver al principio](#índice-de-contenido)**

## 8. Agradecimientos

Sus contribuciones al código abierto, grandes o pequeñas, hacen posible proyectos como este. Muchas gracias por dedicar su tiempo a contribuir.

**[↑ Volver al principio](#índice-de-contenido)**

## 9. Licencia

Copyright (c) Alejandro Jiménez. Todos los derechos reservados.

Código fuente disponible bajo la [licencia MIT](./LICENSE).

**[↑ Volver al principio](#índice-de-contenido)**
