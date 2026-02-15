# Taller Práctico: Fundamentos de Estadística

## Contexto:
Acabas de aplicar una prueba piloto de "Razonamiento Abstracto" a un grupo de 18 estudiantes. La prueba tiene una puntuación máxima de 20 puntos.

## Tus Datos (Puntuaciones Directas $X$):
Aquí están las notas obtenidas por los 19 sujetos:

$$8, \quad 10, \quad 10, \quad 11, \quad 11, \quad 12, \quad 12, \quad 12, \quad 13, \quad 13, \quad 14, \quad 14, \quad 15, \quad 15, \quad 16, \quad 16, \quad 17, \quad 17, \quad 19$$

---

## 📝 Parte 1: Tendencia Central (¿Dónde está la mayoría?)

El primer paso es encontrar el "centro" de tus datos para saber cuál es el rendimiento normal del grupo.

### Instrucciones:
1. **Ordena los datos** de menor a mayor (fundamental para la mediana).
2. **Calcula la Media Aritmética** ($\mu$ o $\bar{x}$): Suma todos los datos y divide por el número total de sujetos ($N=19$).
3. **Encuentra la Mediana**: El valor que deja el 50% de los datos por debajo y el 50% por encima.
4. **Identifica la Moda**: El puntaje que más se repite.

**Pregunta reflexiva:** ¿Se parecen los tres valores? Si son muy diferentes, tus datos podrían no ser "normales".

---

## 📉 Parte 2: Variabilidad (¿Qué tan dispersos están?)

Ahora necesitas saber si el grupo es homogéneo (todos saben más o menos lo mismo) o heterogéneo (hay genios y personas con dificultades).

### Instrucciones:
1. **Calcula la Varianza** ($\sigma^2$).
   - **Paso A:** Toma cada dato ($X$) y réstale la media ($\mu$) que calculaste arriba.
   - **Paso B:** Eleva ese resultado al cuadrado $(X - \mu)^2$.
   - **Paso C:** Suma todos esos resultados al cuadrado.
   - **Paso D:** Divide esa suma entre $N$ (19).

2. **Calcula la Desviación Estándar** ($\sigma$): Simplemente saca la raíz cuadrada de la Varianza.

**Nota:** Este valor ($\sigma$) es tu "vara de medir" para el siguiente paso.

---

## 🔔 Parte 3: Puntuaciones Z (Estandarización)

Vamos a comparar a dos estudiantes específicos: el **Estudiante A** (que sacó 19) y el **Estudiante B** (que sacó 8).

### Fórmula: 
$$Z = \frac{X - \mu}{\sigma}$$

### Instrucciones:
1. Calcula la **Puntuación Z** para el Estudiante A (Puntaje: 19).
2. Calcula la **Puntuación Z** para el Estudiante B (Puntaje: 8).

---

## 🧠 Parte 4: Interpretación (La Curva Normal)

Sin hacer cálculos, responde basándote en tus resultados de la Parte 3 y mirando una gráfica mental de la Campana de Gauss:

1. El Estudiante A, ¿se encuentra dentro del promedio, o es un caso "atípico" superior? (Pista: ¿Su Z es mayor a 1.96?).
2. Si un **Estudiante C** tuviera un $Z = 0$, ¿cuál sería su puntuación directa ($X$)?

---