[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/Z6NE2ogx)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=16551440&assignment_repo_type=AssignmentRepo)
# Práctica 1: Introducción al desarrollo. Reflexiones.

Apoyate en los siguientes recursos para realizar la práctica:

[Descripción de la práctica](https://revilofe.github.io/section3/u01/practica/EDES-U1.-Practica010/)


---

# Título de la Actividad

## Identificación de la Actividad
- **ID de la Actividad:** Práctica 1: Introducción al desarrollo. Reflexiones.
- **Módulo:** EDES
- **Unidad de Trabajo:** UD 1 - Introducción al desarrollo de software
- **Fecha de Creación:** 15/10/2024
- **Fecha de Entrega:** 19/10/2024
- **Alumno(s):** 
  - **Nombre y Apellidos:** Jesús López Pérez
  - **Correo electrónico:** jlopper299@g.educaand.es
  - **Iniciales del Alumno/Grupo:** JLP

## Descripción de la Actividad
La actividad consiste en preguntas sobre todo lo visto en el tema de Entornos de Desarrollo, como el funcionamiento del hardware, el funcionamiento de los lenguajes y códigos y las herramientas para el desarrollo.

## P 1.10: Reflexión y discusión sobre los resultados
### 1. Relación software y hardware
#### 1.1. Primera parte
**1.1.1. ¿Cómo se ejecuta el código en el procesador?**  
Tomando las instrucciones de un programa y realizando los cálculos necesarios para su funcionamiento.  

**1.1.2. ¿Qué hace la memoria RAM con la información del botón o el LED?**  
Almacena temporalmente la información y las instrucciones del funcionamiento del botón para accionar sobre el LED.  

**1.1.3. ¿Cómo se comunican los periféricos (botón y LED) con el procesador?**  
Gracias al sistema de entrada y salida (E/S) del sistema.  

#### 1.2. Segunda parte
**1.2.1. ¿Cómo interactúan el procesador, la memoria y los periféricos en la ejecución del programa?**  
El programa se carga en la memoria, de ahí, pasa sus instrucciones al procesador y los periféricos pueden actuar durante o tras la ejecución.  

**1.2.2. ¿Qué pasa con los datos en la memoria cuando el programa se ejecuta?**  
Mientras se ejecuta y se hace uso del programa, se mantienen en memoria, pero si al cerrar no se han guardado, desaparecerán, ya que la memoria es volátil.  

**1.2.3. ¿Qué roles juegan las instrucciones del software en esta interacción?**  
Las instrucciones harán saber al sistema como debe ejecutarse el software para su correcto funcionamiento.  

**1.2.4. ¿Cómo se relaciona esta simulación con lo que ocurre en un ordenador real?**  
Esta representa como se ejecuta un software en el ordenador, ya sea en que lugar de la RAM se almacena, el funcionamiento de la unidad aritmético-lógica, el acumulador, el registro de direcciones e instrucciones, el contador y la salida.  

### 2. Del código fuente al ejecutable
**2.1. ¿Cómo se diferencia el código fuente del código objeto y del ejecutable?**  
El código fuente es el escrito por el programador mientras que el ejecutable es directamente el ensamblado para utilizarlo.  

**2.2. ¿Por qué el ordenador no puede entender el código fuente directamente?**  
Porque los equipos entienden el lenguaje de máquina, que es una serie de unos y ceros.  

**2.3. ¿Por qué es importante el paso de enlazado en la creación de programas?**  
Porque toma los archivos del código objeto y los unifica en un solo ejecutable.  

**2.4. ¿Qué ocurre si falta alguna de las etapas (código objeto o ejecutable)?**  
En el caso de tener el objeto pero no el ejecutable, a partir del objeto se puede obtener el ejecutable. Si tenemos el ejecutable pero no el objeto, no podemos volver atrás, ya que el ejecutable no es entendido por el humano.  

### 3. Generación de código intermedio
**3.1. ¿Cómo difiere el código intermedio del código ejecutable tradicional?**  
En que es un tipo de código genérico/universal, que permite ser ejecutado por diferentes máquinas virtuales y siendo funcional en distintos S.O.  

**3.2. ¿Por qué es útil tener una máquina virtual?**  
Es un programa que hace de mediador entre el código intermedio y el hardware. Se encargan de ejecutar el código intermedio, traduciendolo a instrucciones que pueda entender el  procesador.  

**3.3. ¿Qué ventajas ofrece el código intermedio?**  
La portabilidad, la seguridad y la optimización en tiempo de ejecución.  

**3.4. ¿Además de java, qué otros lenguajes usan máquinas virtuales?**  
Lenguajes como Java o C#.  

### 4. Lenguajes de programación

#### Primera parte
**4.1.1. ¿Qué diferencias notaron en el proceso de compilación frente a la ejecución directa?**  
Con la compilación se traduce todo a binario antes de llegar a ejecutarse, pero con la interpretación se lee y traduce todo línea a línea.

**4.1.2. ¿Qué pasa si hay un error de sintaxis en cada lenguaje? ¿Cuándo se detecta el error?**  
En el lenguaje interpretado en el momento de la ejecución del código, y con esto no te deja proseguir con la interpretación.  

Y en el lenguaje compilado, el error lo muestra a la hora de compilar, lo cual no permite ejecutar el código.  

#### 4.2. Segunda parte
**4.2.1. ¿Qué notaron sobre la abstracción entre los lenguajes de alto nivel y bajo nivel?**  
Que el lenguaje de bajo nivel es el más cercano a la máquina y a la hora de optimizar un sistema es más óptimo, mientras que el de alto nivel al ser el más cercano al humano, tiene menos control sobre el propio sistema.

**4.2.2. ¿Qué ventajas y desventajas encontraron en cada uno?**  
El lenguaje de alto nivel es más cercano al humano y tienen muchas funcionalidades que ayudan al desarrollador, aunque tienen menos control sobre el sistema. Mientras que el de bajo nivel es más cercano a la máquina y ofrece un mejor control y eficiencia, pero es más complejo a la hora de escribir y comprender.  

#### 4.3. Tercera parte
**4.3.1. ¿Cómo funciona la organización de datos en Java usando objetos y métodos?**  
El ódigo es organizado en objetos, que realmente son instancias de clases. Los objetos también encapsulan datos y comportamientos.

**4.3.2. ¿Cómo es diferente trabajar en un enfoque funcional en Python, usando solo funciones puras?**
Las funciones puras son aquellas que con los mismos datos, la función le delvoverá el mismo resultado siempre. El utilizar las funciones puras en python es recomdendado porque garantiza la
integridad de los datos y que los resultados se repiten.  

#### 4.4. Reflexión final
**4.4.1. ¿Qué lenguajes se sintieron más fáciles de usar? ¿Por qué?**  
Principalmente Python, JavaScript, Ruby, PHP, por ser interpretados, porque aunque sean más lentos por ir línea a línea, son más sencillos a la hora de probar al no tener que compilar.  

**4.4.2. ¿En qué casos es preferible usar un lenguaje compilado frente a uno interpretado?**  
En el caso de que se necesite una mayor rápidez del programa o un rendimiento más optimizado, ya que el compilado es posible optimizarlo de mejor manera (aunque el desarrollo es más complejo), mientras que el interpretado se ejecuta línea a línea (y su desarrollo puede ser más sencillo).

**4.4.3. ¿Cuándo es mejor usar un lenguaje de alto nivel en lugar de uno de bajo nivel?**  
Para la creación de progamas básicos, es mejor un lenguaje de alto nivel, ya que son más sencillos para el desarollador. A la hora de crear programas más complejos es  mejor el de bajo nivel ya que se puede adaptar y optimizar de mejor manera el rendimiento.

**4.4.4. ¿Cómo se siente trabajar con el paradigma orientado a objetos en comparación con el imperativo o funcional?**  
En el orientado a objetos está todo más estructurado y organizado enfoncandose en objetos. El imperativo da instrucciones paso a paso y el funcional va con funciones puras.

### 5. Herramientas de desarrollo
#### 5.1. Primera parte
**5.1.1. ¿Qué hace cada una de las herramientas?**  
Editor de texto: Es la herramienta utilizada para desarrollar y modificar el código.

Compilador: Es la herramienta que se encarga de pasar el código fuente a código máquina.

Intérprete: Es la herramienta que se encarga de ejecutar el código línea a línea sin tener que compilarlo.

Herramientas de documentación: Es la herramienta que analiza el código para generar un documento en base a los comentarios y anotaciones del código.

Depurador: Esta herramienta es la que permite realizar la comprobación del código, siendo posible ejecutarlo de X línea a X línea para examinarlo y verificar que no haya errores.

Sistema de gestión de versiones: Es la herramienta que permite a los desarrolladores ver los cambios en el código, trabjar en distintas ramas y colaborar sin la posibilidad de corromper el trabajo de otros compañeros.

Framework: Esta herramienta es la que se encarga de que la aplicación/programa tenga una estructura predefinida.

Herramientas para pruebas y calidad del código: Asegura el funciomaniento del programa.  
**5.1.2. ¿Qué tipo de tareas facilita?**
Editor de texto: El desarrollo del código y su modificación.

Compilador: El paso del código fuente al código máquina.

Intérprete: La ejecución del programa línea a línea.

Herramientas de documentación: La documentación sobre el funcionamiento del código y su lógica.

Depurador: La búsqueda de errores en el código, pudiendo dividirlo por partes.

Sistema de gestión de versiones: El trabajo en grupo sin riesgo de corromper el trabajo del resto de compañeros.

Framework: El desarrollo del programa, haciendolo más fácil por el uso de una estructura predefinida.

Herramientas para pruebas y calidad del código: El conocer el funcionamiento del programa y su correcto desarrollo.  
**5.1.3. ¿Qué características ofrece que la hacen única o diferente de otras herramientas similares?**
Editor de texto: El estar preparado directamente para el desarrollo.

Compilador: La facilidad que aporta para poder convertir el código a código máquina.

Intérprete: El poder ejecutar un programa sin la necesida de realizar una compilación.

Herramientas de documentación: El poder generar un documento con todas las anotaciones y comentarios.

Depurador: El poder revisar el código por fragmentos y no ser necesario hacerlo todo en una sola vez.

Sistema de gestión de versiones: El poder tener todo centralizaco en un mismo lugar y poder tener versiones diferentes.

Framework: El tener una estructura predefinida para los programas y así facilitar su desarrollo.

Herramientas para pruebas y calidad del código: El poder comprobar el código y su estructuración de una manera sencilla.

**5.1.4. Elige una ¿Cómo es la experiencia de usuario al usarla? ¿Es fácil o compleja?**  
Editor de texto / IDE: En cuanto al editor, algo más complejo, ya que no deja de ser un editor de texto "convencional" para hacer código, mientras el IDE facilita mucho más el trabajo pudiendo instalar extensiones y funcionalidades para trabajar más comodamente.  

**5.1.5. Elige una ¿En qué situaciones sería ideal utilizar esta herramienta?**
IDE: A la hora de realizar cualquier programa, ya que facilita mucho el trabajo en comparación al editor de texto.  

**5.1.6. Elige una ¿Qué limitaciones encontraste en la herramienta?**
Editor de texto: El editor de texto convencional no permite añadir tantas funcionalidades como por ejemplo los IDE.  
#### 5.2. Segunda parte
Céntrate en una herramienta dentro de la misma categoría y compárala con otras:

**5.2.1. ¿Qué herramienta se considera más útil y por qué?**
El sistema de gestión de versiones, ya que para cualquier proyecto es necesario tener el código controlado de manera segura.

**5.2.2. ¿Qué ventajas tiene una sobre la otra?**
Que para mantener un trabajo, ya sea solo o grupal, de una manera segura, es lo más eficiente.

**5.2.3. ¿Cuál herramienta resultó ser la más intuitiva y por qué?**
El IDE, ya que hoy en día, solo con poner el lenguaje que vas a desarrollar, da ayudas de como empezar el programa.

**5.2.4. ¿En qué casos se recomendaría usar un compilador en lugar de un intérprete?**
Cuando sea necesario por rendimiento y por la optimización del código.

**5.2.5. ¿Qué tipo de proyectos se beneficiarían más de un framework como Django?**
Los proyectos web que necesiten desarrollo rápido y escalabilidad, como los negocios online, RRSS, gestión de contenidos.

#### 5.3. Reflexión final
Con base en la experiencia de evaluación de las herramientas:

**5.3.1. ¿Cómo crees que impacta la elección de la herramienta en la calidad del software?**
La elección de la herramienta tiene un gran impacto, ya que puede facilitar significativamente el trabajo, lo cual también le ayuda a mejorar el propio software en su desarrollo.

**5.3.2. ¿Qué características buscarías en una herramienta para facilitar tu flujo de trabajo?**
Que gracias a su uso pudiera hacer el mismo trabajo en un tiempo más reducido y me de más ayudas para solucionar errores a la hora del desarrollo del código.

**5.3.3. ¿Cómo cambió tu percepción de estas herramientas después de haberlas probado y evaluado?**
Cambió significativamente, ya que he aprendido que el buen uso de dichas herramientas puede ayudarte a realizar un trabajo más cómodamente y de una manera más rápida y eficaz.

## Referencias y Fuentes
Se ha buscado y consultado información en:
- [GitHub de Revilofe](https://revilofe.github.io/section3/) (Se ha buscado información)
- [ChatGPT](https://chatgpt.com/) (Se ha consultado y verificado información)
