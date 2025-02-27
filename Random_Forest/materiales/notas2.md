
# Introducción a Machine Learning y Random Forest

---

## Slide 1: Portada
**Introducción a Machine Learning y Random Forest**  
Plática para el Hospital Infantil de México Federico Gómez  
[Tu nombre] - [Fecha]

---

## Slide 2: ¿Qué es Machine Learning?
- Rama de la inteligencia artificial que permite a las computadoras aprender patrones a partir de datos.
- Se diferencia de la estadística tradicional porque **optimiza automáticamente modelos** con datos nuevos.
- Ejemplo: diagnóstico médico basado en imágenes vs. reglas predefinidas.

---

## Slide 3: Tipos de Machine Learning
- **Supervisado**: Datos etiquetados (ej. diagnóstico de cáncer: benigno/maligno).
- **No supervisado**: Agrupar datos sin etiquetas (ej. clustering de expresión génica).
- **Aprendizaje por refuerzo**: Un agente aprende a tomar decisiones (ej. control de robots quirúrgicos).

---

## Slide 4: Árbol de Decisión - Base de Random Forest
- Modelo que divide los datos en ramas basadas en preguntas secuenciales.
- Ejemplo: ¿El paciente tiene fiebre? → ¿Tiene dolor muscular? → Posible diagnóstico.
- Limitaciones: Puede **sobreajustarse** y ser muy sensible a los datos de entrenamiento.

---

## Slide 5: Introducción a Random Forest
- **Solución al sobreajuste de los árboles de decisión.**
- Construye múltiples árboles con datos muestreados aleatoriamente (**bootstrap**).
- Cada árbol da su voto y se obtiene la decisión final por mayoría o promedio.

---

## Slide 6: Cómo se construye un Random Forest
1. Se generan múltiples subconjuntos de datos (muestreo bootstrap).
2. Se construyen árboles de decisión con esos datos.
3. Cada árbol usa un subconjunto de variables para dividir los datos.
4. La decisión final es una combinación de los resultados de todos los árboles.

---

## Slide 7: Ejemplo en Ciencias de la Vida
- **Predicción de respuesta a un fármaco**.
  - Datos: Biomarcadores genéticos y clínicos.
  - Salida: ¿El paciente responderá al tratamiento? (Sí/No)
  - Random Forest ayuda a identificar qué variables son más importantes.

---

## Slide 8: Ventajas y Limitaciones
✅ Ventajas:
- Resistente al sobreajuste.
- No necesita preprocesamiento exhaustivo.
- Puede manejar datos faltantes y ruido.

❌ Limitaciones:
- Puede ser computacionalmente costoso.
- No es tan interpretable como modelos lineales simples.
- Puede ser menos efectivo en datos altamente estructurados.

---

## Slide 9: Comparación con Otros Algoritmos
| Algoritmo          | Pros                         | Contras                   |
|------------------|---------------------------|-------------------------|
| Regresión Logística | Fácil de interpretar        | No captura relaciones complejas |
| Redes Neuronales | Aprende relaciones complejas | Requiere muchos datos y tuning |
| Random Forest    | Robusto y versátil          | Menos interpretable       |

---

## Slide 10: Conclusiones
- **Random Forest** es un modelo poderoso y fácil de usar en datos biomédicos.
- Se basa en múltiples árboles de decisión para mejorar la precisión.
- Es útil cuando hay muchas variables y datos complejos.

---

## Slide 11: Preguntas y Discusión
- ¿Dónde creen que se podría aplicar en sus investigaciones?
- ¿Qué dudas tienen sobre su funcionamiento?

---

