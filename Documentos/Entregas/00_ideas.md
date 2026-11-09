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

### Descripción

Desarrollo de un sistema de Machine Learning capaz de recomendar precios dinámicos para productos de un comercio electrónico. El modelo calculará la elasticidad precio-demanda combinando el histórico de ventas con variables externas (estacionalidad, días festivos) e internas (niveles de inventario, visitas a la web) para sugerir el precio óptimo en el momento exacto, maximizando el beneficio o el volumen de ventas según la estrategia elegida. 

### Problema 

Los e-commerce pierden constantemente margen de beneficio o volumen de ventas por mantener precios estáticos. Reaccionar tarde a picos de demanda, a campañas estacionales o acumular stock inmovilizado genera pérdidas financieras invisibles pero cuantiosas. 

### Usuario

Category Managers, Analistas de Pricing, y Directores de E-commerce o Revenue Management. 

### Solución Actual

Fijación de precios basada en reglas manuales estáticas (coste del producto + margen fijo), análisis rudimentarios en Excel y revisiones periódicas lentas que no tienen en cuenta el comportamiento del usuario en tiempo real ni el exceso de stock. 

### Valor

Automatización de una tarea analítica compleja que permite maximizar los ingresos, optimizar la rotación del inventario (liquidando stock antes de que genere costes de almacenamiento) y reaccionar al mercado sin depender de la intuición humana. 

### Datos 

Histórico transaccional de ventas (tickets, fechas, cantidades), registro histórico de cambios de precio, catálogo de productos (categorías, marcas), datos de tráfico web (clics, carritos abandonados) y un calendario de eventos/festividades. 

### MVP

Un cuadro de mando interactivo (usando Streamlit o Power BI) conectado a un modelo predictivo (como XGBoost o Random Forest) que analice una única categoría de productos de alta rotación. El usuario seleccionará un producto y el sistema le mostrará una curva de elasticidad de demanda y el precio recomendado para la próxima semana. 

### Viabilidad

Alta. Es un proyecto clásico pero muy robusto para un máster de Data Analytics & IA, ya que permite aplicar limpieza de datos intensiva, análisis exploratorio (EDA) profundo, modelos de regresión y creación de dashboards. Existen abundantes datos públicos de e-commerce transaccionales. 

### Riesgo

En un entorno académico es difícil validar el modelo en "producción" real (A/B testing en vivo) para comprobar si el usuario final realmente compraría al precio sugerido por el algoritmo. Además, requiere un trabajo exhaustivo de ingeniería de características (feature engineering) para cruzar bien las fechas y los productos. 

## AgroSmart Predictv

### Descipción 

Plataforma de Inteligencia Artificial para la agricultura de precisión que integra dos motores: uno de Computer Vision (Redes Neuronales Convolucionales) para detectar enfermedades en las hojas de los cultivos a partir de fotografías, y un modelo de Machine Learning tabular que analiza datos meteorológicos históricos y predicciones climáticas para recomendar pautas de riego optimizadas.

### Problema

Las plagas y enfermedades agrícolas merman significativamente las cosechas porque se detectan demasiado tarde. Paralelamente, existe un uso ineficiente y desproporcionado del agua y los fertilizantes, lo que incrementa los costes operativos y genera un impacto medioambiental negativo. 

### Usuario 

Agricultores, Ingenieros Agrónomos, Cooperativas Agrícolas y Gestores de grandes explotaciones. 

### Solución Actual 

Inspección visual humana in situ (lenta, propensa a errores y dependiente de la experiencia del operario) y sistemas de riego programados por horarios fijos sin importar las condiciones reales de humedad o la previsión de lluvia inminente.

### Valor

Reducción drástica del gasto en agua (fomentando la sostenibilidad), disminución del uso de pesticidas al tratar las enfermedades de forma temprana y focalizada, y aumento general del rendimiento económico de la cosecha. 

### Datos 

Bancos de imágenes etiquetadas de hojas (sanas y con diversas enfermedades), series temporales climáticas (temperatura, precipitación, humedad relativa) y datos simulados de las necesidades hídricas del cultivo. 


### MVP

Una aplicación web sencilla o un bot de Telegram donde el agricultor suba una foto de la hoja y el sistema devuelva el diagnóstico (sana o infectada y con qué patología). En paralelo, un módulo en el dashboard que, consumiendo la API meteorológica gratuita para los próximos 3 días, indique si es necesario activar el riego o no. 

### Viabilidad 

Muy buena y visualmente muy atractiva para presentar en la defensa del TFM. Permite al grupo tocar ramas variadas de la IA: Deep Learning (procesamiento de imágenes) y Machine Learning clásico (series temporales/regresión para el clima). Los datasets de imágenes agrícolas públicas son excelentes y están listos para entrenar. 

### Riesgo 

Que el modelo de visión artificial, al ser entrenado con imágenes de laboratorio (muy limpias y bien iluminadas), pierda precisión cuando el usuario suba una foto borrosa, con mala luz o fondos ruidosos tomada desde un teléfono móvil en el campo real. 