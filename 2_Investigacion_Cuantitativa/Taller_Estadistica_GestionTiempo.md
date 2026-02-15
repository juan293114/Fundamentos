# Taller Práctico: Fundamentos de Estadística

## Contexto:
Eres estudiante de psicología y en este taller aprenderás a aplicar una escala psicológica real, recolectar datos y analizarlos estadísticamente. Aplicarás la **"Escala de Gestión del Tiempo Académico"** a tus compañeros de clase para evaluar sus habilidades de organización y planificación.

---

## 📋 Instrumento: Escala de Gestión del Tiempo Académico

### Descripción del Instrumento:
La escala consta de **15 ítems** que evalúan tres dimensiones:
- **Planificación** (5 ítems): Capacidad para organizar tareas y establecer prioridades
- **Control del Tiempo** (5 ítems): Uso eficiente del tiempo y cumplimiento de plazos
- **Autorregulación** (5 ítems): Monitoreo y ajuste de estrategias de estudio

### Formato de Respuesta:
Cada ítem se responde en una escala Likert de 5 puntos:
- **1** = Nunca
- **2** = Raramente
- **3** = A veces
- **4** = Frecuentemente
- **5** = Siempre

### Puntuación:
- **Mínimo**: 15 puntos (peor gestión del tiempo)
- **Máximo**: 75 puntos (excelente gestión del tiempo)
- **Puntuación más alta** = **Mejor gestión del tiempo**

---

## 📝 Ítems de la Escala

### Dimensión 1: Planificación
1. Hago una lista de las tareas que debo completar cada semana
2. Establezco prioridades entre mis actividades académicas
3. Planifico con anticipación mis trabajos y proyectos
4. Organizo mi agenda de estudio con horarios específicos
5. Divido las tareas grandes en pasos más pequeños

### Dimensión 2: Control del Tiempo
6. Cumplo con los plazos de entrega de mis trabajos
7. Evito la procrastinación cuando tengo tareas importantes
8. Distribuyo mi tiempo de estudio de manera equilibrada
9. Logro completar las tareas en el tiempo que planifico
10. Mantengo un ritmo constante de trabajo durante el semestre

### Dimensión 3: Autorregulación
11. Reviso regularmente si estoy cumpliendo con mis metas académicas
12. Ajusto mi planificación cuando no funciona como esperaba
13. Reflexiono sobre cómo puedo mejorar mi uso del tiempo
14. Identifico las actividades que me hacen perder tiempo
15. Soy consciente de cuánto tiempo dedico a cada actividad

---

## 🎯 ACTIVIDAD 1: Recolección de Datos

### Paso 1: Preparación
- Cada persona debe responder la escala
- Explica que la escala evalúa hábitos de organización (no hay respuestas correctas o incorrectas)
- Asegura confidencialidad de las respuestas
- Tiempo estimado: 10-15 minutos

### Paso 2: Instrucciones para los Participantes
"Lee cada afirmación y marca la opción que mejor describe tu comportamiento habitual durante este semestre. Responde con honestidad pensando en cómo realmente actúas, no en cómo te gustaría actuar."

### Paso 3: Calificación
- Cada estudiante suma los valores de sus 15 respuestas
- Todos los ítems se califican directamente (no hay ítems inversos)
- Resultado: Puntuación total entre 15 y 75
- **Registra todas las puntuaciones en una tabla**

### Paso 4: Organización de Datos
- Reúne todas las puntuaciones del grupo
- Anota el número total de participantes ($N$)
- Tendrás un conjunto de datos real para analizar

---

## 📊 Tus Datos (Puntuaciones Directas $X$):

**Instrucciones:** Registra aquí las puntuaciones totales de todos los participantes de tu grupo:

**Número total de participantes ($N$):** _______

**Puntuaciones obtenidas:**





*(Deja espacio para anotar los datos recolectados)*

---

## 📝 ACTIVIDAD 2: Parte 1 - Tendencia Central (¿Dónde está la mayoría?)

El primer paso es encontrar el "centro" de tus datos para saber cuál es el nivel promedio de gestión del tiempo en el grupo.

### Instrucciones:
1. **Ordena los datos** de menor a mayor (fundamental para la mediana).
2. **Calcula la Media Aritmética** ($\mu$ o $\bar{x}$): Suma todos los datos y divide por el número total de participantes ($N$).
3. **Encuentra la Mediana**: El valor que deja el 50% de los datos por debajo y el 50% por encima.
4. **Identifica la Moda**: El puntaje que más se repite.

**Pregunta reflexiva:** ¿Se parecen los tres valores? Si son muy diferentes, tus datos podrían no ser "normales".

---

## 📉 ACTIVIDAD 3: Parte 2 - Variabilidad (¿Qué tan dispersos están?)

Ahora necesitas saber si el grupo es homogéneo (todos gestionan su tiempo de manera similar) o heterogéneo (hay estudiantes muy organizados y otros muy desorganizados).

### Instrucciones:
1. **Calcula la Varianza** ($\sigma^2$).
   - **Paso A:** Toma cada dato ($X$) y réstale la media ($\mu$) que calculaste arriba.
   - **Paso B:** Eleva ese resultado al cuadrado $(X - \mu)^2$.
   - **Paso C:** Suma todos esos resultados al cuadrado.
   - **Paso D:** Divide esa suma entre $N$ (el número total de participantes).

2. **Calcula la Desviación Estándar** ($\sigma$): Simplemente saca la raíz cuadrada de la Varianza.

**Nota:** Este valor ($\sigma$) es tu "vara de medir" para el siguiente paso.

---

## 🔔 ACTIVIDAD 4: Parte 3 - Puntuaciones Z (Estandarización)

Aquí es donde la psicometría cobra vida. Vamos a comparar casos extremos de tu muestra.

### Fórmula: 
$$Z = \frac{X - \mu}{\sigma}$$

### Instrucciones:
1. Identifica la **puntuación más alta** de tus datos. Llámala "Participante A".
2. Identifica la **puntuación más baja** de tus datos. Llámala "Participante B".
3. Calcula la **Puntuación Z** para el Participante A.
4. Calcula la **Puntuación Z** para el Participante B.

---

## 🧠 ACTIVIDAD 5: Parte 4 - Interpretación (La Curva Normal)

Responde basándote en tus resultados de la Parte 3 y en una gráfica mental de la Campana de Gauss:

1. El Participante A (puntuación más alta), ¿tiene habilidades de gestión del tiempo excepcionales, o está dentro del rango normal? (Pista: ¿Su Z es mayor a 1.96?).

2. El Participante B (puntuación más baja), ¿cómo se compara con el resto del grupo? ¿Sería candidato para un taller de técnicas de estudio?

3. Si un **Participante C** tuviera un $Z = 0$, ¿cuál sería su puntuación directa ($X$)? ¿Qué significa esto?

4. Calcula aproximadamente qué porcentaje de tus participantes tiene puntuaciones Z entre -1 y +1. ¿Coincide con el 68% esperado en una distribución normal?

5. Si un participante tuviera un $Z = +1.5$, ¿aproximadamente qué percentil ocuparía? (Usa tu conocimiento de la curva normal).

---

## 💭 ACTIVIDAD 6: Reflexión Final

Basándote en los datos que recolectaste y tus cálculos:

### 1. Interpretación de niveles
Considerando que la escala tiene un rango de 15-75 puntos:
- **15-35**: Gestión del tiempo deficiente
- **36-54**: Gestión del tiempo moderada
- **55-75**: Buena gestión del tiempo

**Preguntas:**
- ¿En qué rango se encuentra la mayoría de tu grupo según la media que calculaste?
- ¿Qué te dice esto sobre las habilidades de gestión del tiempo de tu grupo?

### 2. Identificación de casos
- ¿Cuántos estudiantes obtuvieron puntuaciones menores a 35?
- ¿Cuántos obtuvieron puntuaciones mayores a 55?
- Según la puntuación Z, ¿hay casos que necesitarían apoyo urgente en técnicas de organización? (Z < -2.0)

### 3. Normalidad de la distribución
- ¿Se parecen la media, mediana y moda en tus datos?
- ¿Crees que estos datos siguen una distribución normal? Justifica tu respuesta.
- Haz un histograma simple con tus datos. ¿Tiene forma de campana?

### 4. Aplicación práctica
- Si tuvieras que diseñar un programa de intervención, ¿para qué porcentaje del grupo lo harías?
- ¿Cómo determinarías el punto de corte? (Sugerencia: usa puntuaciones Z)
- ¿Qué recomendaciones específicas darías basándote en los resultados?

### 5. Comparación con la teoría
- Según la curva normal, aproximadamente el 68% de los datos debería estar entre $\mu - \sigma$ y $\mu + \sigma$. ¿Sucede esto en tus datos?
- Calcula estos límites y cuenta cuántos participantes caen en ese rango. ¿Qué porcentaje representa?

---

## 📌 Notas para el Evaluador

### Interpretación Clínica:
- **Z > +2.0**: Excelentes habilidades de gestión del tiempo (top 2.5%)
- **Z entre +1.0 y +2.0**: Buenas habilidades (aproximadamente 13.6%)
- **Z entre -1.0 y +1.0**: Rango promedio (aproximadamente 68%)
- **Z entre -1.0 y -2.0**: Dificultades moderadas (aproximadamente 13.6%)
- **Z < -2.0**: Dificultades significativas, requiere intervención (bottom 2.5%)

### Recomendaciones según puntuación:
- **< 35 puntos**: Intervención inmediata con programa estructurado
- **35-45 puntos**: Taller de técnicas de gestión del tiempo
- **46-60 puntos**: Recomendaciones generales y seguimiento
- **> 60 puntos**: Funcionamiento óptimo, posible mentor para otros
