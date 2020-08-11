# MATHSOFT
“MATHSOFT” busca incentivar el aprendizaje y mejorar la habilidad para la matemática a través de una interfaz sencilla y divertida. La interfaz va a permitir escoger al usuario un avatar, el cual va a poder ser personalizado con los diferentes “skins” que se irán ganando mientras se avance en el juego y se consigan logros.

El juego estará distribuido en niveles, los cuales se irán alcanzando conforme el usuario vaya superando cada objetivo propuesto, la complejidad de las operaciones aumentará a medida que se alcance un nuevo nivel.

### Autores

* [Yordy W. Santos Apaza](https://github.com/syordya)
* [Jhon I. Flores Pacheco](https://github.com/leviroseb)
* [Victor M. Janampa Canahuire](https://github.com/VictorJanampa)

### Características de los usuarios
* La población objetivo son niños en etapa escolar, entre 6 y 12 años, los cuales se están iniciando en el mundo de la matemática.
* Una característica propia de esta edad es su curiosidad, las ganas de aprender cosas nuevas cada día, pero a su vez la diversión como parte importante.

### Definiciones
* Datos: Información de registro del usuario en el sistema.
* GUI: Interfaz gráfica de usuario.
* Máximo: Puntaje máximo alcanzado en el juego.
* Skin: Aspecto de avatar del jugador.
* Avatar: Aspecto del jugador dentro del juego.
* Perfil: Datos personales del jugador.

## MÓDULOS
| Módulo | Estilos de programación |
| ------------- | ------------- |
| Implementar el registro de usuario | * Letterbox * Constructivist * Spreadsheet |
| Implementar la validación de usuario | * Bulletin Board * Aspects |
| Implementar el módulo de evaluación | * Letterbox * Constructivist * Aspects |
| Diseño GUI | * Plugins |
| Implementación de funcionalidad de recuperación de contraseña | * Bulletin Board * Aspects |

Otros:

* Implementar la ventana del perfil de Usuario.
* Recopilación de tutoriales y fuentes externas.
* Recompensas Especiales.
* Definir e implementar los módulos de aprendizaje.
* Definir los Niveles de dificultad en los módulos.

## S.O.L.I.D.
### Principio de Sustitución de Liskov (LSP)
Módulos: Implementar el módulo de Evaluación, Recompensas Especiales.

Herencia en el proceso de generación de operaciones matemáticas aleatorias.

![img](images/LSP.jpg)

### Principio de segregación de Interfaces (ISP)
Módulos: Implementar la validación de Usuario, Implementar el registro de Usuario.

### COHESIÓN
Cohesión Funcional: Cuando el módulo ejecuta una y sólo una tarea, teniendo un único objetivo a cumplir, se dice que tiene Cohesividad Funcional.

![img](images/ISP1.jpg)

### ACOPLAMIENTO
Acoplamiento de Control: Cuando un módulo le envía a otro un elemento de control que determina la lógica de ejecución del mismo.

![img](images/ISP2.jpg)

### Principio de la Inversión de Dependencias (DIP)
Módulos: Implementar la ventana del perfil de Usuario, Implementar la validación de Usuario, Recompensas Especiales.

Finalidad de reducir el acoplamiento en la Clase Recompensa, esto hará que se reduzca la dependencia entre los módulos de código de dicha clase.

## DOMAIN-DRIVEN DESIGN (DDD)
### LENGUAJE UBICUO
Se le puede definir como un lenguaje común entre los desarrolladores y los ususarios.
DDD ayuda a lograr más cercano al lenguaje natural, para obtener como resultado final un producto que debe ser comprensible para todos los miembros del equipo independientemente de su rol.

### CAPAS DE LA ARQUITECTURA
#### USER INTERFACE
Presenta la información al usuario, interpreta sus acciones y las envía a la aplicación.
![img](images/ddd1.png)
![img](images/ddd2.png)
![img](images/ddd3.png)

### APPLICATION
Encargada de verificar e interactuar con los diferentes usuarios durante el uso de la aplicación.
![img](images/ddd4.png)

### DOMAIN
Es el núcleo de la aplicación que contiene las reglas del "negocio" y el responsable de mantener los objetos del negocio.
En el caso de Mathsoft el núcleo es el manejo de data y las operaciones matemáticas que la aplicación realiza.

### INFRASTRUCTURE
Capa de soporte para el resto de capas, provee la comunicación con las otras capas e implementa las peresistencias de los objetos de negocio y las librerías de soporte para las otras capas.
En el caso de Mathsoft se hizo uso de interconexión en ventanas de SFML y QT permitiendo el uso de diferentes capas.

### MODULES
* Registro de usuario.
* Interfaz de la aplicación.
* Verificación de datos.
* Realización de operaciones.

