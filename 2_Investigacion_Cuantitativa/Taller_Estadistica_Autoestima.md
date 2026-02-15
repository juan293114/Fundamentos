# Taller Práctico: Fundamentos de Estadística

## Contexto:
Trabajas en el departamento de psicología de una universidad. Acabas de aplicar la "Escala de Autoestima de Rosenberg" (versión adaptada) a un grupo de 19 estudiantes universitarios de primer año. La escala tiene una puntuación mínima de 10 y máxima de 40 puntos, donde **puntuaciones más altas** indican **mayor autoestima**.

## Tus Datos (Puntuaciones Directas $X$):
Aquí están las puntuaciones obtenidas por los 19 participantes:

$$18, \quad 22, \quad 22, \quad 24, \quad 24, \quad 26, \quad 26, \quad 28, \quad 28, \quad 28, \quad 30, \quad 30, \quad 32, \quad 32, \quad 34, \quad 34, \quad 36, \quad 36, \quad 38$$

---

## 📝 Parte 1: Tendencia Central (¿Dónde está la mayoría?)

El primer paso es encontrar el "centro" de tus datos para saber cuál es el nivel de autoestima promedio del grupo.

### Instrucciones:
1. **Ordena los datos** de menor a mayor (fundamental para la mediana).
2. **Calcula la Media Aritmética** ($\mu$ o $\bar{x}$): Suma todos los datos y divide por el número total de participantes ($N=19$).
3. **Encuentra la Mediana**: El valor que deja el 50% de los datos por debajo y el 50% por encima.
4. **Identifica la Moda**: El puntaje que más se repite.

**Pregunta reflexiva:** ¿Se parecen los tres valores? Si son muy diferentes, tus datos podrían no ser "normales".

---

## 📉 Parte 2: Variabilidad (¿Qué tan dispersos están?)

Ahora necesitas saber si el grupo es homogéneo (todos tienen niveles similares de autoestima) o heterogéneo (hay personas con autoestima muy alta y muy baja).

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

Vamos a comparar a dos participantes específicos: el **Participante A** (que obtuvo 38 puntos) y el **Participante B** (que obtuvo 18 puntos).

### Fórmula: 
$$Z = \frac{X - \mu}{\sigma}$$

### Instrucciones:
1. Calcula la **Puntuación Z** para el Participante A (Puntaje: 38).
2. Calcula la **Puntuación Z** para el Participante B (Puntaje: 18).

---

## 🧠 Parte 4: Interpretación (La Curva Normal)

Sin hacer cálculos, responde basándote en tus resultados de la Parte 3 y mirando una gráfica mental de la Campana de Gauss:

1. El Participante A, ¿se encuentra dentro del promedio, o es un caso "atípico" con autoestima excepcionalmente alta? (Pista: ¿Su Z es mayor a 1.96?).

2. El Participante B, ¿cómo se compara con el resto del grupo? ¿Sería candidato para una intervención psicológica?

3. Si un **Participante C** tuviera un $Z = 0$, ¿cuál sería su puntuación directa ($X$)?

4. ¿Qué porcentaje aproximado de participantes tiene una autoestima superior a la del Participante A? (Usa tu conocimiento de la curva normal).

---

## 💭 Reflexión Final:

Basándote en tus cálculos:

- ¿Dirías que este grupo de estudiantes de primer año tiene, en general, autoestima baja, media o alta? Justifica tu respuesta.
- ¿Los datos sugieren que hay "casos extremos" que requerirían atención especial?
- ¿Crees que la autoestima en este grupo sigue una distribución normal? ¿Por qué?
