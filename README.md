# Sistema Experto - Componentes principales

A continuación se describen los módulos de un **Sistema Experto** indicando su **¿Qué?**, **¿Para qué?** y **¿Cómo?**.

---

## 1. Módulo de adquisición de conocimiento
- **¿Qué?**  
  Es la parte del sistema que recopila información proveniente de expertos humanos, sensores o bases de datos.  

- **¿Para qué?**  
  Para capturar y formalizar el conocimiento necesario que será usado por el sistema experto.  

- **¿Cómo?**  
  Mediante entrevistas con expertos, técnicas de elicitación del conocimiento o integrando datos de sensores/bases de datos que alimentan la base de conocimiento y la base de hechos.  

---

## 2. Base de Conocimiento
- **¿Qué?**  
  Es el “almacén” donde se guardan reglas, hechos y relaciones lógicas del dominio del problema.  

- **¿Para qué?**  
  Para que el sistema tenga la sabiduría acumulada y pueda aplicarla en la resolución de problemas.  

- **¿Cómo?**  
  Se estructura con reglas del tipo **SI… ENTONCES…**, ontologías, redes semánticas o marcos conceptuales.  

---

## 3. Base de Hechos
- **¿Qué?**  
  Es la memoria temporal donde se almacenan los datos y hechos específicos de cada problema a resolver.  

- **¿Para qué?**  
  Para representar la situación particular sobre la cual se aplicarán las reglas de la base de conocimiento.  

- **¿Cómo?**  
  Se llena con datos introducidos por el usuario o capturados por sensores, y se actualiza conforme avanza el razonamiento del sistema.  

---

## 4. Motor de Inferencia
- **¿Qué?**  
  Es el “cerebro” del sistema experto encargado de razonar y aplicar las reglas a los hechos disponibles.  

- **¿Para qué?**  
  Para deducir conclusiones, resolver problemas y generar recomendaciones basadas en el conocimiento almacenado.  

- **¿Cómo?**  
  Utilizando técnicas de inferencia:  
  - **Encadenamiento hacia adelante (Forward chaining):** parte de los datos y aplica reglas hasta llegar a una conclusión.  
  - **Encadenamiento hacia atrás (Backward chaining):** parte de una hipótesis y busca confirmarla a través de los datos.  

---

## 5. Módulo de Explicaciones
- **¿Qué?**  
  Es la parte del sistema que explica al usuario cómo y por qué se llegó a una conclusión o recomendación.  

- **¿Para qué?**  
  Para generar confianza en el usuario y permitirle entender el razonamiento del sistema.  

- **¿Cómo?**  
  Mostrando las reglas aplicadas, los hechos considerados y la secuencia lógica de deducción.  

---

## 6. Interfaz de Usuario
- **¿Qué?**  
  Es el medio de comunicación entre el sistema experto y el usuario.  

- **¿Para qué?**  
  Para que el usuario introduzca datos, formule consultas y reciba las respuestas o recomendaciones.  

- **¿Cómo?**  
  A través de pantallas gráficas, menús interactivos, lenguaje natural o incluso sistemas de voz.  

---
