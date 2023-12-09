# Compara los modelos de calidad propuestos por McCall yBoehm, identifica y lista sus características escenciales y reflexiona sobre cuál de estos dos modelos sería más adecuado para aplicar en tu proyecto de desarrollo de software. Justifica tu elección.
## Barry Boehm
**Modelo de calidad fijo propuesto por Barry Boehm (1978), siendo muy similar al modelo McCall, el cual incorpora 19 criterios que incluyen características de performance del hardware, incluye una estructura jerárquica, donde los factores generales se descomponen en específicos para ser medidos.** 
**Estas métricas permiten evaluar el nivel, de acuerdo a un criterio del factor de calidad, siendo estas propiedades estáticas a diferencia de las interpretaciones específicas que constituyen propiedades dinámicas; sin embargo, para la aplicación de las métricas es necesario considerar las características de calidad del software en tres niveles:**
### Alto o principal:
**Mantenimiento, utilidad, portabilidad.**
### Componente intermedio:
**Fiabilidad, flexibilidad, eficiencia, capacidad de prueba.**
### Componente primitivo.:
**Independencia, exactitud, consistencia, comunicatividad.**
## Mccall 
**Este modelo de calidad fue presentado en 1977 y propone una serie de factores de calidad conocidos como factores de McCall, Richards, & Walters (1977), la idea del modelo es la descomposición del concepto genérico de calidad en tres capacidades importantes para un producto software todo desde la mirada del usuario. A su vez cada capacidad se descompone en un conjunto de factores y finalmente se definen criterios para evaluar el factor a través de métricas que indican en qué medida el sistema posee una característica dada.**
### Operación.
**Corrección: Grado de cumplimiento de las especificaciones y objetivos del usuario**

**Confiabilidad: Grado en el sistema está disponible para usarse** 

**Usabilidad: Grado de esfuerzo necesario que se requiere para aprender a utilizarlo.**

**Integridad o seguridad: Grado en el que se controla el acceso al programa o los datos por usuarios no autorizados.**
### Transición.
**Portabilidad: Grado que mide el esfuerzo para migrar un programa de un entorno de operación a otro.** 

**Reusabilidad: Grado de esfuerzo requerido para que el programa o una de sus partes pueda ser utilizado en otro proyecto** 

**Interoperabilidad. Grado de esfuerzo dedicado para que un sistema o programa pueda operar conjuntamente con otro.**

### Revisión. 

**facilidad de mantenimiento: Esfuerzo requerido para localizar y corregir un error en un programa en funcionamiento.** 

**Flexibilidad: Esfuerzo requerido para modificar un software en funcionamiento.**

**Facilidad de prueba: Grado de esfuerzo requerido para probar un programa verificando que realice adecuadamente sus funciones**

### El modelo adecuado para nuestro proyecto es el de Mccall debido a que se centra en las nececidades y perspectivas del usaruio. Este modelo es fundamental para cualquier tipo de proyectos y se implementa en todas las actividaes, y es por ello que se involucra en el nuestro debido a que involcra tanto al cliente, el servicio y los programadores.

## Auditoría de Gestión de Configuración del Software
Artefactos elegidos

1. Prototipo de Interfaz de Usuario (UI).
2. Código Fuente del Software.

1. Prototipo de Interfaz de Usuario (UI):
•	¿Se ha establecido un sistema de control de versiones para el prototipo de UI?
•	¿Se han etiquetado las versiones del prototipo para su fácil identificación?
•	¿Existe un registro de cambios que documenta las modificaciones realizadas en cada versión del prototipo?
•	¿Se ha configurado un repositorio centralizado para almacenar y gestionar el prototipo de UI?
•	¿Se han implementado prácticas de respaldo regular para el prototipo?
2. Código Fuente del Software:
•	¿Se utiliza un sistema de control de versiones (como Git) para gestionar el código fuente?
•	¿Cada cambio en el código fuente está asociado con un mensaje de confirmación descriptivo?
•	¿Las versiones del código están etiquetadas de manera clara y significativa?
•	¿Existe un flujo de trabajo establecido para fusionar cambios en el código desde diferentes ramas?
•	¿Se han establecido políticas para la rama principal y la creación de nuevas ramas?
General:
•	¿Se ha documentado y comunicado el proceso de gestión de configuración a todos los miembros del equipo?
•	¿Se ha asignado a alguien la responsabilidad de la gestión de configuración del proyecto?
•	¿Se realiza una revisión regular de la configuración y versionamiento del software?
Observaciones Adicionales:
________________________________________
Esta lista de verificación se puede utilizar durante el desarrollo del proyecto para asegurarse de que la gestión de configuración se lleva a cabo de manera efectiva para los artefactos específicos. Cada elemento marcado ○ "[○]" con debe ser revisado y marcado como "[●]" una vez que se haya confirmado su implementación. 
El equipo ha demostrado una sólida implementación de las prácticas de gestión de configuración. Todos los aspectos revisados cumplen con las mejores prácticas y contribuyen a un desarrollo de software efectivo y controlado.