# Ideas para el proyecto de fin de máster.

## Sport Safe

### Descripcion

Desarrollo de un sistema de Data Science capaz de utilizar los datos recogidos por un chaleco inteligente para identificar patrones de carga, fatiga y recuperación asociado al riesgo de lesión y genera una alerta preventiva para cada jugador. Para este producto proponemos un sistema que combina un chaleco portátil de movimiento con datos de entrenamiento, esfuerzo, recuperación e histórico de lesiones, consiste en convertir datos dispersos en información útil y comprensible, y con ello tomar decisiones profesionales.  

### Problema

Algunos de los problemas actuales que nos enfrentamos en la actualidad son: 
- (Principal) Riesgos de lesiones y sobrecarga de jugadores de forma itinerante. 
- Datos no vinculados, no existe visión completa en lugar específico por cada jugador. 
- Si no hay revisión diaria, las lesiones pueden pasar desapercibidas y sin darle la importancia que necesitan. 
- Personalización en la carga para cada deportista.
- Limitación de recursos, por tiempo, presupuestos y personal. 

### Usuario

Quien podría comparar este tipo de producto:
- Preparador físico: El cual necesita de interpretación de los datos para carga y planificación de rutinas para sus sesiones.  
- Club: Un comprador mas institucional, donde busca la mejora y el seguimiento a nivel de varios equipos.  
- Deportista: Comodidad y confianza con el uso de datos para su propia mejoría deportiva.  
- Fisioterapeuta: Para realizar valoraciones a partir de consultas de datos, tendencias, estadística… 

### Valor

Centralización de datos, cuando existan evidencia suficiente con modelos validados, informes automáticos con evolución temporal, evaluación de resultados antes y después de intervenir. Además, se puede dar valor en los siguientes aspectos mas técnicos: 
- Reducción de tiempos al consolidar informenes y datos.  
- Ir al dato y eficiencia temporal para evitar lesiones, dolor y una buena recuperación. 
- Ofrecer a clubes, una solución mas eficiente y con presupuesto rentable, par aquellos que tenga recursos limitados. 
- Identificar de manera eficiente y temprana cambios de patron, que merezca la pena, una revisión profesional.  

### Datos candidatos

Algunos datos que necesitamos recoger: 
- Exposición de juego. 
- Datos médicos.
- Datos de recuperación. 
- Histórico de lesiones.  
- Datos principales del deportista (nombre, edad, deporte, posición…) 

### MVP

En principio podríamos comenzar con un pequeño equipo, con datos de sensores ya disponibles o conjunto de datos fiables. Realizar la limpieza de datos de la importación del CVS, y llegar a los indicadores descriptivos y tendencias individuales de cada jugador. 

### Visibilidad

Comenzar por un pequeño equipo y ver su viabilidad, con sensores comerciales que estén disponibles y sean fiables. Podrimos partir de un formulario/datos breves de fatiga, dolor, RPE y recuperación de un pequeño equipo, y si es viable, entonces buscar la ampliación en un futuro.  Para que tengamos una mejor viabilidad importaremos datos por sesión para que no aumente la complejidad con la sincronización de datos a tiempo real.  

### Riesgo

- Coste elevado del producto, solución realizar un presupuesto por etapas. 
- Encontrar un club/equipo que nos pueda dar datos reales. 
- Privacidad en los datos, (pérdida de confianza). 
- Ajuste del chaleco, que sea incomodo, hay que tenerlo en cuenta. 
- Datos incompletos, debemos realizar un producto eficiente, validando y realizando seguimientos de datos ausentes.  

## Sistema Inteligente de Triaje y Resolución Automatizada

### DESCRIPCIÓN:
Desarrollo de un sistema de Inteligencia Artificial que combina modelos de clasificación supervisada con modelos de lenguaje (LLM y RAG) para analizar, categorizar y asignar automáticamente los tickets de soporte entrantes. Resuelve incidencias recurrentes sin intervención humana y asiste a los técnicos proponiendo respuestas basadas en la base de conocimiento interna.

### PROBLEMA:
Algunos de los problemas actuales a los que nos enfrentamos son:
* (Principal) Tiempos de espera excesivos para la resolución de tickets por parte de los clientes.
* Cuellos de botella operativos por la clasificación manual de cientos de peticiones diarias.
* Redirección ineficiente de tickets (rebotes constantes entre departamentos) por diagnósticos iniciales erróneos.
* Saturación del equipo de soporte resolviendo dudas repetitivas ya documentadas.

### USUARIO:
Quién podría comprar este tipo de producto:
* Director de Soporte Técnico / Helpdesk: Necesita métricas de eficiencia, reducción de costes y control de tiempos.
* Técnicos de Soporte (L1/L2): Buscan automatizar el triaje tedioso y recibir borradores de respuestas.
* Cliente Final: Exige respuestas inmediatas y soluciones precisas sin ser rebotado.

### SOLUCIÓN ACTUAL:
Triaje completamente manual realizado por operadores o sistemas rígidos basados en palabras clave que fallan constantemente, provocando acumulación de tickets en cola.

### VALOR:
* Reducción drástica del tiempo medio de resolución (MTTR).
* Eliminación de tareas repetitivas de clasificación manual, liberando tiempo para casos complejos.
* Erradicación de los rebotes ineficientes de tickets entre departamentos.
* Aumento directo de la satisfacción del cliente (CSAT).

### DATOS CANDIDATOS:
Algunos datos que necesitamos recoger:
* Histórico de tickets anteriores (asunto, cuerpo del mensaje, categoría, prioridad y tiempo empleado).
* Bases de conocimiento internas, FAQs y manuales técnicos (KMS).
* Registros de satisfacción e historial de interacción de los clientes.

### MVP:
En principio podríamos comenzar con un modelo de clasificación entrenado para un dominio acotado (ej. incidencias de acceso o software), con un panel interactivo que muestre la categoría predicha y sugiera una respuesta automática generada mediante RAG lista para ser validada por el técnico.

### VIABILIDAD:
Comenzar por un pequeño departamento para ver su viabilidad, utilizando datasets públicos estructurados de soporte al cliente (como *IT Helpdesk Tickets*) combinados con documentos en PDF para la parte generativa, y si es viable, buscar la ampliación a otras áreas de la empresa.

### RIESGO:
* Clasificación incorrecta de la severidad (falsos negativos en incidencias críticas).
* Posibles "alucinaciones" del modelo si se habilitan respuestas automáticas sin supervisión.
* Mantenimiento de la base de conocimiento para que el modelo no dé soluciones obsoletas.

## PreiceOptimize AI

## AgroSmart Predictv