## Practica 5: Exportación + Documentación - entregables 

Para ver la aplicación funcionando, haz clic en el siguiente enlace:

## [👉 CLIC AQUÍ PARA PROBAR LA APP](https://www.figma.com/make/An1VIS9vvsTAOXsaw0uB5b/Crear-app-interactiva?fullscreen=1&t=oCszbpvr4fSDDC3w-1&code-node-id=0-9)


Video de uso de la app:

## [VIDEO](diseño_final.webm)

- Exportación a HTML/React
- Documentación con Storybook
- Autoevaluacion del diseño 
Puntos fuertes y de mejora relativos a los criterios de accesibilidad de tu diseño
- Conclusiones

## 1. Resumen Ejecutivo
Este informe detalla el análisis del perfil de los participantes reclutados y la posterior evaluación de usabilidad mediante la **Escala de Usabilidad del Sistema (SUS)** para dos alternativas de diseño: **Método A (Qarmita)** y **Método B (SushiMakiTeriyaki)**. Los datos demuestran que ambas propuestas superan con creces la media de la industria (establecida en 68 puntos), posicionándose en un rango de excelencia.

---

## 2. Análisis del Plan de Reclutamiento
La muestra seleccionada está compuesta por un grupo diverso de 8 participantes, mitigando de forma óptima sesgos demográficos o de experiencia digital previa:
* **Diversidad de Perfiles:** Incluye un rango de edad amplio (de 20 a 64 años) y un equilibrio de géneros (4 Mujeres, 3 Hombres, 1 No Definido).
* **Competencia Técnica:** Los niveles de los usuarios varían de forma balanceada desde "Alto" hasta "Bajo/medio", asegurando que la interfaz haya sido testeada tanto por usuarios expertos como por perfiles que requieren mayor accesibilidad.

### Tabla: Muestra de Participantes Reclutados
| ID | Edad | Género | Competencia | Gafas | Exp previa | Exps apps | Grupo |
| :-: | :-: | :---: | :--- | :-: | :-: | :-: | :-: |
| 1 | 26 | Hombre | Alto | no | No | Si | B |
| 2 | 64 | Mujer | Medio/alto | si | No | Si | A |
| 3 | 63 | Hombre | Bajo/medio | no | no | no | A |
| 4 | 25 | Hombre | Medio/alto | No | No | Si | A |
| 5 | 21 | ND | Medio | Si | NO | Si | A |
| 6 | 26 | Mujer | Medio/alto | No | NO | Si | B |
| 7 | 20 | Mujer | Medio | Si | No | Si | B |
| 8 | 54 | Mujer | Bajo/medio | No | NO | No | B |

---

## 3. Instrumento de Evaluación: Reactivos SUS
El cuestionario aplicado a los participantes constó de las siguientes 10 preguntas estándar de la Escala SUS (puntuadas de 1: Totalmente en desacuerdo, a 5: Totalmente de acuerdo):

* **P1:** Creo que me gustará visitar con frecuencia este website.
* **P2:** Encontré el website innecesariamente complejo.
* **P3:** Pensé que era fácil utilizar este website.
* **P4:** Creo que necesitaría del apoyo de un experto para recorrer el website.
* **P5:** Encontré las funciones del website bastante bien integradas.
* **P6:** Pensé que había demasiada inconsistencia en el website.
* **P7:** Imagino que la mayoría de las personas aprenderían muy rápidamente a utilizar el website.
* **P8:** Encontré el website muy grande al recorrerlo.
* **P9:** Me sentí muy confiado en el manejo del website.
* **P10:** Necesito aprender muchas cosas antes de manejarme en el website.

> 💡 **Nota metodológica sobre el cálculo:** Para obtener la puntuación final estandarizada (0-100), el valor de los reactivos impares (positivos) se calcula como $(Valor - 1)$ y el de los reactivos pares (negativos) como $(5 - Valor)$. La suma de todos los puntajes transformados se multiplica por $2.5$.

---

## 4. Resultados de Usabilidad
### Métricas Globales
* **MÉTODO A (Qarmita):** Puntuación Promedio de **88.33 / 100** ➔ **Excelente (Grado A)**
* **MÉTODO B (SushiMakiTeriyaki):** Puntuación Promedio de **91.25 / 100** ➔ **Excelente / Sobresaliente (Grado A+)**

### Tabla: Resultados de la Escala SUS Calculada
| P1 | P2 | P3 | P4 | P5 | P6 | P7 | P8 | P9 | P10 | Método A/B Testing | Score SUS |
| :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :--- | :---: |
| 3 | 1 | 5 | 1 | 4 | 2 | 4 | 2 | 4 | 1 | B. SushiMakiTeriyaki | **82.5** |
| 5 | 1 | 5 | 1 | 5 | 1 | 5 | 1 | 5 | 1 | B. SushiMakiTeriyaki | **100.0** |
| 3 | 2 | 4 | 1 | 5 | 1 | 5 | 1 | 4 | 1 | B. SushiMakiTeriyaki | **87.5** |
| 5 | 1 | 5 | 1 | 4 | 1 | 5 | 2 | 5 | 1 | B. SushiMakiTeriyaki | **95.0** |
| 4 | 1 | 5 | 1 | 5 | 3 | 5 | 1 | 5 | 1 | A. Qarmita | **92.5** |
| 3 | 1 | 5 | 1 | 3 | 2 | 5 | 1 | 5 | 1 | A. Qarmita | **87.5** |
| 5 | 1 | 4 | 1 | 4 | 3 | 5 | 2 | 4 | 1 | A. Qarmita | **85.0** |

### Hallazgos Clave
1. **Puntaje Perfecto:** El segundo registro del **Método B** obtuvo una puntuación perfecta de **100.0 pts**, lo cual indica que la experiencia de uso fue completamente fluida, intuitiva y carente de frustraciones.
2. **Consistencia:** El **Método A** demostró una consistencia muy alta sin fluctuaciones graves (rango de 85 a 92.5), validando que es una estructura sólida y segura para el usuario general.

---

## 5. Conclusión y Recomendación General
Se aconseja **proceder con la implementación definitiva del Método B (SushiMakiTeriyaki)**. Aunque ambas opciones se ubican muy por encima de la media del mercado, el Método B maximiza la satisfacción del usuario y minimiza la carga cognitiva, registrando un promedio superior de **91.25 puntos**. Los valores mínimos en las respuestas de ítems de frustración (como P2, P4 y P6) ratifican que los flujos no presentan cuellos de botella críticos.
