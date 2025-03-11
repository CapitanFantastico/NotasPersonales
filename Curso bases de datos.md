Programa: Tecnología en desarrollo de software
Universidad del Valle
Sede Yumbo

Prerrequisitos:
- Fundamentos de programación imperativa (Informática I), Sem1
- Fundamentos de programación orientada a objetos (Taller tecnológico II), Sem2 - Fundamentos de programación orientada a eventos, Sem3 - Análisis y diseño de algoritmos I, Sem4
- Bases de Datos, Sem4 
- Desarrollo de software I, Sem5
- Desarrollo de software II, Sem6
- Introducción a la gestión de proyectos de software, Sem7 / Desarrollo de aplicaciones para dispositivos móviles, Sem7

Horas de trabajo: Presenciales: 4 horas, Trabajo independiente: 8 horas
Validable; Si
Habilitable: No
Asignatura Profesional?

DESCRIPCIÓN GENERAL DEL CURSO

Esta asignatura tiene por objeto comprender los conceptos, la importancia, las técnicas, las herramientas de las bases de datos, y aplicarlas en el desarrollo de software.
Adicionalmente, busca que el estudiante pueda:
• Describir los conceptos fundamentales propios de las bases de datos (objetivos básicos, funciones, modelos de los DBMS, los roles asociados con la administración de la información, importancia de la persistencia de los datos para una organización, el concepto de independencia, el uso de los conceptos para el modelaje), necesarios en la solución de un problema de manejo de información en una organización.
• Utilizar notaciones apropiadas para el modelaje de una solución donde pueda identificar las restricciones y limitaciones de los requerimientos a resolver.
• Aplicar las técnicas de diseño de Bases de Datos para la construcción de una aplicación informática a un problema del mundo real.
• Aplicar técnicas de modelaje, de solución de consultas relacionales, de creación de programas con consultas embebidas, en el desarrollo de aplicaciones de software, para resolver problemas con Bases de Datos, trabajando principalmente con el modelo de datos relacional


CONTENIDO

1. CONCEPTOS DE BASE DE DATOS
Conceptos básicos: Bases de Datos, DBMS, Esquemas de BD, Independencia Lógica y Física
Enfoque tradicional versus enfoque de base de datos
Ventajas de un ambiente de base de datos
Arquitectura de un DBMS:
Lenguaje de Definición de Datos, Lenguaje de Manejo de Datos
Funciones del manejador de base de datos
Usuarios de un ambiente de base de datos
Evolución histórica de las base de datos (Jerárquica, Red, Relacional, Orientada a Objetos)

2. MODELAMIENTO CONCEPTUAL DE DATOS
Definición de modelo 
Clasificación de los modelos de datos
Importancia de la modelización conceptual
Componentes básicos del modelo E-R
Clases de entidades 

3. ALGEBRA RELACIONAL
Operaciones tradicionales de conjuntos del álgebra relacional: Unión, Intersección, Diferencia, Producto Cartesiano.
Operaciones especiales del modelo relacional:
Proyección, Selección, Unión Natural (Join), División.
Otras operaciones del álgebra relacional.

4. CÁLCULO RELACIONAL
Cálculo relacional de tuplas
Cálculo relacional de dominios
Cálculo relacional vs. álgebra relacional

5. EL LENGUAJE SQL
Características generales del SQL.
Estructura básica
Implementación de operaciones básicas

6. PROGRAMACIÓN EN AMBIENTES DE BD Restricciones
Llaves
Integridad referencial
Definición de procedimientos
Definición de Disparadores
Manejo de cursores
Interfase con GUI en Java

7. FUNDAMENTOS DEL MODELO RELACIONAL
Definición del modelo relacional
Restricciones de integridad del modelo relacional.
Definiciones de claves: Primaria, Candidata, Foránea
Redundancia y Anomalías de actualización de datos
Concepto de dependencia funcional
Concepto de las Formas Normales: 1FN, 2FN, 3FN, BCNF, 4FN
Axiomas de Armstrong

8. NORMALIZACIÓN DE DATOS
Formas Normales basadas en dependencias funcionales: 2FN, 3FN, BCNF
Descomposición de relaciones
Enfoques de diseño relacional: análisis y síntesis.
Dependencia Multivaluada y 4FN – otras dependencias
Costos de la normalización
Ejercicios de Normalización
Desnormalización para el rendimiento


Diapositivas

CONCEPTOS BÁSICOS

Dato: Valor de alguna característica de un objeto, con significado implícito.
Los datos están asociados a un "tipo de dato" y están definidos sobre un "dominio"

Información: Conjunto ordenado de datos que son manejados según la necesidad de usuario.
Conjunto de datos relacionados en un contexto

Conocimiento?

Base de datos: Conjunto de datos relacionados que se encuentra agrupada y estructurada.
Conjunto de datos persistente, lógicamente coherente y con un significado implícito.
Representa aspectos del mundo real (minimundo, universo del discurso)
Los cambios en el minimundo se reflejan en la base de datos.
Se diseña, se crea y se carga para conseguir objetivos determinados.
Los datos son almacenados para algo.
Dirigida a un grupo de usuarios.
Los datos son interesantes para alguien.


COMPONENTES DE LAS BASES DE DATOS

Esquema de base de datos: Componente estático o estructural de la base de datos, normalmente no cambia
Cuando una base de datos es diseñada, interesa definir una estructura para ésta.
Esta estructura permanece "estática" durante un gran período de tiempo, aunque puede sufrir modificaciones ocasionales.

Instancia de la base de datos: Es la información que en un determinado instante del tiempo posee la base de datos y que cambia permanentemente (excepto en algunos tipos de bases de datos particulares)

HISTORIA

Inicio de las civilizaciones: papiro, bibliotecas, papel
1884: Máquina automática de perforación de tarjetas (Herman Hollerith)
1950: Creación de cintas magnéticas
1960: Modelo de red y jerárquico
1970: Modelo de base de datos relacionales (Edgar Codd)
1974-1977: Lenguaje de consulta QUEL
1980: Se estandariza el uso de SQL
1990: Aparece ORACLE y otras herramientas cliente, data mining
Siglo XXI: Tendencias en bases de datos no relacionales, volúmenes de datos

Antes: Realidad fragmentada y otros problemas, cruces y cargues de datos, desactualización, duplicidad de información
Ahora: 
Sacar pantallazo 

SISTEMA DE GESTIÓN DE BASE DE DATOS (SGBS - DBMS)

Interfaz de software entre la BD y los usuarios del sistema responsable de tratar todas las peticiones de información de los usuarios
Conjunto de herramientas para CONSTRUIR Y MANIPULAR bases de datos

Funciones:
Permitir a los usuarios: inserción, consulta y actualización de datos
Garantizar integridad de los datos
Proveer un sistema de seguridad. (privilegios)
Proporcionar un diccionario de metadatos
Permitir el uso de transacciones (ejecución de operaciones en bloque)

Facilitar la auditoría de las operaciones efectuadas
Permitir el uso y control de la concurrencia
Garantizar la independencia de los datos
Ofrecer conectividad con el exterior
Incorporar herramientas para salvaguardar la información

OBJETIVOS DE LAS B.D.
Disminuir:
Redundancia y duplicidad de datos
Aislamiento de los datos
Inconsistencia de los datos

LENGUAJE DE UN SGBD
Soporta algún lenguaje de alto nivel (SQL) para ejecutar las tareas de administración y operación de la B.D.
Ofrece optimización en la búsqueda de la información
Sus instrucciones se clasifican en:
DML: (asociado a la Instancia)
DDL: (asociado al esquema)
DCL: (asociado a la seguridad, creación de usuarios, roles, privilegios)
Diccionario de datos: (Metadatos)
TCL:Lenguaje de control de transacciones.  (Ejecución de instrucciones en bloque)

ACTORES EN UN SGBD
DBA
Diseñadores de las bases de datos
Usuarios finales
Analistas y Programadores de aplicaciones

ARQUITECTURA ANSI/SPARC (Instituto nacional de estándares americanos / Comisión reguladores de requisitos de software) 3 niveles
Nivel externo: de usuario o de vista de usuario (Confidencialidad)
Nivel conceptual: Esquema lógico, resultado de un proceso de modelamiento (Integridad-coherencia) - Esquema lógico (interpretación de la bd desde el punto de vista lógico o conceptual)
Nivel interno: Esquema físico (gestión de acceso)

Nivel de visión: El más cercano a los usuarios finales
Percepción de la base de datos por parte de los usuarios finales
Tantas visiones como tipos de usuarios 
Cada visión de usuario final se puede caracterizar como un subesquema

Nivel conceptual: Mediador entre los otros dos niveles
Se ocupa de los datos almacenados en la bd física y las relaciones entre ellos
Descripción semántica de los datos que conforma la bd (interpretación)
Es una visión completa de todos los requerimientos y elementos de interés para la organización
Debe incluir restricciones sobre los datos
La descripción del nivel conceptual no debe tener detalles dependientes del almacenamiento
Tiene asociado un lenguaje de alto nivle (DER)

Nivel físico: Más cercano a la máquina
Interesa al administrador y al usuario especialista
Se hace una descripción de los tipos de datos: tamaños, precisión, tipos de índices y de estructuras de almacenamiento concretas que se manejan, de acuerda con un SGBD particular

Nivel interno: Describe cómo los datos son almacenados en términos de estructuras de datos particulares
Se encarga de:
Reservar espacio para datos e índices
Compresión de datos
Técnicas de encriptamiento de datos

INDEPENDENCIA DE LOS DATOS
Es uno de los objetivos de la arquitectura Ansi/Sparc
Permite modificar la definición de un nivel sin afectar (en lo posible) el nivel inmediatamente superior
Sin independencia de datos se requiere mucho esfuerzo para cambiar las aplicaciones de tal forma que se adaptasen a la nueva estructura de la bd

Física: inmunidad que tienen los usuarios y las aplicaciones ante los cambios en la forma de almacenar físicamente los datos

Lógica o Conceptual: inmunidad que poseen los usuarios y las aplicaciones ante los cambios en la estructura lógica de la bd

METODOLOGÍA DE DISEÑO DE BASES DE DATOS
Diagrama de flujo 1:26 

Especificación de requisitos
Proceso de establecer los servicios que el cliente requiere de un sistema y las restricciones sobre las cuales debe funcionar y ser desarrollado. -Sommerville.
Es una de las etapas más críticas del proceso de software, determina qué se va a realizar
Más del 30% de los proyectos de software que fracasan es por causa de una mala especificación de requisitos
Medir el éxito de un producto de software:
- Según el grado en que éste cumple con el objetivo para el que fue diseñado
Dificultad:
- Los requerimientos son inherentemente dinámicos
Alternativa:
- El proceso de ingeniería de requisitos debe ser preciso y flexible a la vez
Un requerimiento (requisito) de software define las funciones, capacidades o atributos de cualquier sistema de software.

Representan:
- Factores de calidad
- Los datos de entrada
- Descripción de cómo se debe comportar el sistema

Min 1:39 Diagrama de especificación de requisitos

Requerimientos funcionales: definición de los servicios que un sistema debe proveer, sus comportamientos a las diferentes entradas y situaciones.
Requerimientos No funcionales: Restricciones aplicadas sobre las funcionalidades del sistema como: restricciones de tiempo, sobre el proceso de desarrollo, recursos, dominio del negocio.
Ejemplos:
- El sistema debe almacenar la información de los pacientes: ID, nombres, apellidos, fnacimiento, género
- El sistema debe permitir consultar la historia clínica de un paciente por medio de su ID
- El sistema deberá registrar cualquier acceso o modificación sobre una historia clínica
Definen las propiedades y restricciones del sistema a construir o sobre el proceso que lo consultará
Los requerimientos no funcionales suelen ser más críticos que los funcionales, dado que su incumplimiento puede hacer inútil el sistema
Estos están clasificados según el tipo de restricción que se quiere implementar
Características
- Precisos
- Completos
- Consistentes
- Verificables
Muchos problemas relacionados con requerimientos están asociados a las diferentes interpretaciones que se le pueden dar a los mismos
La ambigüedad puede ser usada para sacar partido de las diversas situaciones:
- Un desarrollador / Un cliente
Aceptable/adecuado: Defina qué constituye la aceptabilidad y cómo el sistema la juzga
Al menos, como mínimo, no: Especificar los valores mínimos y máximos aceptables
Eficiente: Defina como el sistema usa eficientemente recursos, cuán rápidamente ejecuta operaciones o cómo es de fácil para la gente usarlo
Rápido, veloz: Especifique la mínima velocidad aceptable a la que el sistema ejecuta alguna acción

DISEÑO CONCEPTUAL
Describe un conjunto de conceptos de una realidad y cómo se relacionan entre ellos
Descripción de alto nivel de la estructura de la BD
No interesan las estructuras de almacenamiento

Diagrama 1:58 DER , modelo de Chen

Diagrama 2:00 Modelo o diagrama de clases, curso de programación OO (Clases y asociaciones)

DISEÑO LÓGICO
Descripción de la estructura de la BD
Punto de partida: un modelo conceptual
Más detallado que el modelo conceptual
La elección del modelo lógico depende de la clase de modelo soportado por el tipo de SGBD
Puede ser realizado automáticamente por sistemas avanzados
Los modelos lógicos más usados son:
- Relacional
- Objeto - Relacional
- Objetual puro

Diagrama 2:06 Modelo lógico relacional

MODELO FÍSICO
Es una descripción de la implementación de una BD en disco
Describe las estructuras de almacenamiento y las técnicas para tener acceso a los datos
El diseño de un modelo físico depende de un SGBD específico

LENGUAJE SQL
Lenguaje usado para definir, manipular y controlar bd relacionales
Estandarizado por ISO
Comando SQL:
- DDL: Create, Alter, Drop <Después del primer parcial>
- DML: CRUD (Insert, Select, Update, Delete) <Después del primer parcial>
- DCL: Grant, Revoke <Terminando el semestre>
- TCL: Commit, Rollback <Terminando el semestre>

Tarea: Diseñar una infografía sobre las tendencias actuales y futuras de las bases de datos 



Proyecto 
Dada una especificación de requerimientos funcionales (requisitos)
Diseño de base de datos
MER
MR
3FN
Comandos de creación de relaciones
Comandos de creación de restricciones
Consultas
Diseño conceptual
Diseño lógico
Diseño físico






Internet de las cosas
Big data
Data mining
BD orientadas a cubos
DWH