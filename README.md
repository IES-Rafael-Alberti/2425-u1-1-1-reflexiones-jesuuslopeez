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
- **Fecha de Entrega:** [Fecha de entrega]
- **Alumno(s):** 
  - **Nombre y Apellidos:** Jesús López Pérez
  - **Correo electrónico:** jlopper299@g.educaand.es
  - **Iniciales del Alumno/Grupo:** JLP

## Descripción de la Actividad
[Descripción detallada de la actividad, objetivos, y contexto necesario para comprenderla. Explicar en qué consiste la actividad y qué se espera que el alumno desarrolle o implemente.]

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
*Por responder*  

**4.1.2. ¿Qué pasa si hay un error de sintaxis en cada lenguaje? ¿Cuándo se detecta el error?**  
En el lenguaje interpretado en el momento de la ejecución del código, y con esto no te deja proseguir con la interpretación.  

Y en el lenguaje compilado, el error lo muestra a la hora de compilar, lo cual no permite ejecutar el código.  

#### 4.2. Segunda parte
**4.2.1. ¿Qué notaron sobre la abstracción entre los lenguajes de alto nivel y bajo nivel?**  
*Por responder*  

**4.2.2. ¿Qué ventajas y desventajas encontraron en cada uno?**  
El lenguaje de alto nivel es más cercano al humano y tienen muchas funcionalidades que ayudan al desarrollador, aunque tienen menos control sobre el sistema. Mientras que el de bajo nivel es más cercano a la máquina y ofrece un mejor control y eficiencia, pero es más complejo a la hora de escribir y comprender.  

#### 4.3. Tercera parte
**4.3.1. ¿Cómo funciona la organización de datos en Java usando objetos y métodos?**  
El ódigo es organizado en objetos, que realmente son instancias de clases. Los objetos también encapsulan datos y comportamientos.

**4.3.2. ¿Cómo es diferente trabajar en un enfoque funcional en Python, usando solo funciones puras?**
*Por responder* 

#### 4.4. Reflexión final
**4.4.1. ¿Qué lenguajes se sintieron más fáciles de usar? ¿Por qué?**  
Principalmente Python, JavaScript, Ruby, PHP, por ser interpretados, porque aunque sean más lentos por ir línea a línea, son más sencillos a la hora de probar al no tener que compilar.  

**4.4.2. ¿En qué casos es preferible usar un lenguaje compilado frente a uno interpretado?**  
*Por responder* 

**4.4.3. ¿Cuándo es mejor usar un lenguaje de alto nivel en lugar de uno de bajo nivel?**  
Para la creación de progamas básicos, es mejor un lenguaje de alto nivel, ya que son más sencillos para el desarollador. A la hora de crear programas más complejos es  mejor el de bajo nivel ya que se puede adaptar y optimizar de mejor manera el rendimiento.

**4.4.4. ¿Cómo se siente trabajar con el paradigma orientado a objetos en comparación con el imperativo o funcional?**  
*Por responder* 

### 5. Herramientas de desarrollo
#### 5.1. Primera parte¶
**5.1.1. ¿Qué hace cada una de las herramientas?**

**5.1.2. ¿Qué tipo de tareas facilita?**

**5.1.3. ¿Qué características ofrece que la hacen única o diferente de otras herramientas similares?**

**5.1.4. Elige una ¿Cómo es la experiencia de usuario al usarla? ¿Es fácil o compleja?**

**5.1.5. Elige una ¿En qué situaciones sería ideal utilizar esta herramienta?**

**5.1.6. Elige una ¿Qué limitaciones encontraste en la herramienta?**

## Desarrollo de la Actividad
### Descripción del Desarrollo
[Explicación de cómo se ha abordado el desarrollo de la actividad, incluyendo las decisiones de diseño, estructura del código y enfoque de resolución de problemas. Se recomienda adjuntar diagramas o capturas de pantalla si es necesario.]

### Código Fuente
[Aquí se incluirá un enlace directo a los archivos de código fuente en el repositorio, por ejemplo, si se está usando GitHub: `src/main.java` o algún enlace directo.]

### Ejemplos de Ejecución
- **Entrada 1:** Descripción de la entrada y valor de prueba.
- **Salida Esperada 1:** Explicación de la salida esperada y el resultado de la prueba.

### Resultados de Pruebas
[Aquí se detallará cómo se ha verificado la funcionalidad del código, incluyendo resultados de pruebas automatizadas o manuales, en caso de que las haya.]

## Documentación Adicional
- **Manual de Usuario:** [Enlace a la documentación del usuario, si existe]
- **Autorización de Permisos:** Verificar que el profesor tenga permisos de lectura en el repositorio para revisar el código.

## Conclusiones
[Resumen de las conclusiones alcanzadas al desarrollar la actividad, las lecciones aprendidas, y posibles mejoras que se puedan implementar en futuras entregas.]

## Referencias y Fuentes
[Aquí se listarán las fuentes consultadas para el desarrollo de la actividad, tales como documentación oficial, artículos, o cualquier recurso externo relevante.]

### Notas Adicionales:
1. **Nombres de Archivos y Repositorios:**
   - Asegúrate de que el nombre del archivo o repositorio siga la estructura definida: `XXX-idActividad-Iniciales`.
2. **Permisos:**
   - Verifica que el profesor tenga los permisos necesarios para acceder al repositorio o documento.
3. **Formato:**
   - Si se entrega en formato PDF o Google Docs, asegúrate de cumplir con el mínimo y máximo de folios establecidos.
4. **Compilación y Ejecución:**
   - Detalla claramente cómo compilar y ejecutar el código, incluyendo las instrucciones en el archivo `README.md`.
