# Compilador FAX

## Descripción
El proyecto **Compilador FAX** es un compilador desarrollado para un lenguaje de programación en español llamado **FAX**.  
Actualmente, el compilador cubre la **fase léxica**, la cual se encarga de identificar los **tokens válidos**, reconocer errores léxicos y mostrar estadísticas de los elementos encontrados en el código fuente.

El compilador está desarrollado en **Java** utilizando **JavaCC** para la generación del analizador léxico.  
El proyecto es parte de un trabajo académico enfocado en **construcción de compiladores** y aprendizaje de análisis léxico.

---

## Características
- Reconocimiento de **palabras reservadas**, **identificadores**, **literales**, **operadores** y **símbolos especiales**.
- Detección y reporte de **errores léxicos** con línea y columna.
- Ejecución desde **consola**, sin necesidad de interfaz gráfica.
- Capacidad de **continuar la lectura del código** incluso si se encuentra un error léxico.
- Clasificación de tokens en categorías para facilitar el análisis posterior.

---

## Requisitos
- Java **8** o superior.
- JavaCC **7.x** (archivo `.jar` incluido en el repositorio o descargar desde [JavaCC](https://javacc.org)).
- Sistema operativo con terminal / consola.

---

## Instalación
1. Clonar el repositorio:
    ```bash
    git clone <LINK_DEL_REPOSITORIO>
    ```
2. Colocar el archivo `javacc.jar` en la carpeta del proyecto.
3. Generar los archivos del compilador usando JavaCC:
    ```bash
    java -cp javacc.jar org.javacc.parser.Main LenguajeEspañol.jj
    ```
4. Compilar el código Java generado:
    ```bash
    javac *.java
    ```
5. Ejecutar el compilador sobre un archivo de entrada:
    ```bash
    java AnalizadorLexico < entrada.txt
    ```

## Documentación (**FASE LEXICA**)
- Manual de Usuario: https://drive.google.com/file/d/1qZhEb2UiSwG3yPitY--hHVnmXVV8Dx4F/view?usp=sharing
- Manual Tecnico: https://drive.google.com/file/d/1fUL-_nxXkFZ0lJLFOTEe3-TXpli2OFU7/view?usp=sharing
---


