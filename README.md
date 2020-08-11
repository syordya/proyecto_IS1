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

| Módulos | Estilos de programación |
| ------------- | ------------- |
| Implementar el registro de usuario | * Letterbox * Constructivist * Spreadsheet |
| Implementar la validación de usuario | * Bulletin Board * Aspects |
| Implementar el módulo de evaluación | * Letterbox * Constructivist * Aspects |
| Diseño GUI | * Plugins |
| Implementación de funcionalidad de recuperación de contraseña | * Bulletin Board * Aspects |

## S.O.L.I.D.
### Principio de Sustitución de Liskov (LSP)
Módulos: Implementar el módulo de Evaluación, Recompensas Especiales.
Herencia en el proceso de generación de operaciones matemáticas aleatorias.

![img](images/LSP.png)

### Principio de segregación de Interfaces (ISP)
Módulos: Implementar la validación de Usuario, Implementar el registro de usuario.

COHESION:
Cohesión Funcional: Cuando el módulo ejecuta una y sólo una tarea, teniendo un único objetivo a cumplir, se dice que tiene Cohesividad Funcional.

![img](images/ISP_1.png)

ACOPLAMIENTO:
Acoplamiento de Control: Cuando un módulo le envía a otro un elemento de control que determina la lógica de ejecución del mismo.

![img](images/ISP_2.png)

### Principio de la Inversión de Dependencias (DIP)
Módulos: Implementar la ventana del perfil de Usuario, Implementar la validación de Usuario, Recompensas Especiales.

Finalidad de reducir el acoplamiento en la Clase Recompensa, esto hará que los se reduzca la dependencia entre los módulos de código de dicha clase.
