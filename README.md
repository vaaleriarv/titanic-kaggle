# Descripción del Proyecto

En este proyecto trabajé con el dataset del Titanic para predecir quién sobrevivió. Mi objetivo fue construir un modelo de machine learning eficiente.
---

# Qué hice y por qué

- **Limpieza de datos:**  
  Traté los valores faltantes usando la mediana para edades y tarifas, y la moda para los puertos de embarque. Esto evita que los datos incompletos afecten negativamente el modelo.

- **Ingeniería de características:**  
  Creé variables nuevas que aportan información relevante, como:  
  - _FamilySize_ (tamaño familiar), sumando hermanos, padres y el propio pasajero.  
  - _Title_ (título de clase extraído del nombre), para capturar aspectos sociales.  
  - _Deck_ (cubierta de la cabina), que indica la ubicación y puede influir en la supervivencia.

- **Codificación de variables categóricas:**  
  Convertí variables de texto a números (sexo, puerto de embarque, títulos) para que los modelos los puedan procesar.

- **Modelado:**  
  Probé Random Forest y XGBoost, destacando XGBoost por su mejor desempeño y capacidad de ajuste. Realicé una búsqueda de hiperparámetros con validación cruzada para optimizar el modelo.

- **Resultados:**  
  Logré una precisión del 84%.

---
