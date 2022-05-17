# Syntaxis Highlighter
This repository is a Syntaxis Highlighter in Python with examples in Python, Java and  C+

Documentación Situacion Problema

Profesor:
Victor de la Cueva

Integrantes:
Rodolfo De la O Pérez 			ID: A01366363
Santiago Alberto Sorzano Mongel	ID: A01769673

Introducción
En esta actividad integradora tenemos como objetivo el análisis sintáctico los lenguajes de programación, en donde se nos reta a crear este resaltado que convierta nuestro texto de entrada en HTML+CSS que la salida de este mismo pero resaltando el léxico que esté en nuestro código. 

Resumen
Para la correcta solución a este problema tuvimos varios caminos y además de que fue tardado, ya que planteamos varios escenarios y nos surgieron muchas dudas y problemas que fuimos resolviendo poco a poco, y con esto llegar al código que genera una relación entre los tokens y la posición en memoria de los caracteres, una vez con esto puede identificar que lexema es para así dar su resultado. En este momento los sistemas de resaltado son de mucha ayuda en el ámbito laboral, ya que genera una optimización de procesos y permiten que el usuario de este pueda informarse o clasificar temas de una forma más eficiente, dando así un mejor rendimiento y una capacidad de organización más avanzada.

Una vez dicho esto, el análisis sintáctico es algo que simplemente damos por hecho, dejando de lado el complejo funcionamiento de este, este lo podemos ver tanto en la gramática como en la escritura, y es vital para una clara comprensión de lo que está pasando en un entendimiento estructurado.

Reflexión Final
Éticamente, tanto este proyecto como similares en el área de la tecnología la cual se encuentra en continuo desarrollo, genera varios problemas ya que actualmente es muy fácil apropiarse del contenido que otra personas creó y desarrolló, el plagio se presta de una manera muy sencilla pero al mismo tiempo la comunidad que se enfoca en el desarrollo tecnológico ha tomado un camino bastante liberal en torno al uso de librerías, codigos, etc. Por lo tanto puede haber un debate en torno a que si está justificado el gran avance tecnológico en los últimos años a costa de que nadie se está llevando el crédito de estos.


Comentarios Importantes 


Tenemos el archivo highlighter.py, en este es donde se enlaza el archivo que utilizará para resaltar, tenemos 3 archivos que están como .txt, éstos siendo: EjemploPython, EjemploC y EjemploJava. Cada uno usando el lenguaje que el propio archivo tiene como nombre, de igual manera tenemos el archivo llamado estilos, archivo css donde a través de rgb se la asigna un color diferente a cada palabra, estos viendose en el html llamado SyntaxHighlighter, en este se verá reflejado el resultado final del css y del código que se seleccione. 


En las líneas 39, 40 y 41  están comentados los ejemplos, así en este caso el profesor podrá comentar y desmarcar las opciones para decidir qué ejemplo o código quiere ver en el html. 


También usamos gitignore, esto como una ayuda ya que al trabajar en el proyecto en vsc (visual studio code) surgían muchos problemas, uno de los más relevantes al final siendo que el propio vsc “ignoraba” ciertos archivos y parecía que no estuvieran aquí, gitignore resuelve este problema, en caso de volver a suceder podemos eliminar el archivo o usar ("search.useIgnoreFiles": false) o true en su casa para habilitar o deshabilitar el uso de este archivo.
