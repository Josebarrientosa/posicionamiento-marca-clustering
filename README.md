# Posicionamiento de marca y segmentación de consumidores con K-Means

Segmentación de consumidores y análisis de posicionamiento de marca mediante clustering K-Means (k=4), a partir de evaluaciones de percepción en escala Likert de 7 puntos. Trabajo de titulación de Estadística — Instituto de Estadística, PUCV (2025).

## Problema

El posicionamiento de una marca electrónica pierde efectividad cuando se basa solo en la visión interna de la empresa y no en cómo la perciben realmente los consumidores. Este proyecto responde a una pregunta concreta: ¿cómo representar y analizar la percepción del consumidor frente a distintas marcas de aparatos electrónicos, para orientar una estrategia de posicionamiento más alineada con el mercado?

## Datos

- Fuente: base de evaluaciones perceptuales del libro *Multivariate Data Analysis* (Hair et al., 2010), ampliamente usada en estudios de marketing.
- 3.050 observaciones, cada una correspondiente a la evaluación de un consumidor sobre una marca.
- 4 marcas evaluadas (anonimizadas como Romeo, Sierra, Papa, Tango).
- 9 atributos perceptuales medidos en escala Likert de 7 puntos: Adaptable, Best Value, Cutting Edge, Delightful, Exciting, Friendly, Generous, Helpful, Intuitive.

## Metodología

- Análisis exploratorio de las percepciones por marca (gráficos comparativos 6–7 vs 1–2 por atributo).
- Agrupación conceptual de los 9 atributos en tres dimensiones: racional, emocional y funcional.
- Estandarización de variables y uso de distancia euclidiana.
- Selección del número óptimo de clusters mediante el método del codo (se compararon k=3 y k=4).
- Segmentación final con K-Means (k=4) y caracterización de cada cluster.
- Análisis de la distribución de marcas dentro de cada segmento.

## Resultados principales

- Se identificaron 4 segmentos de consumidores con tamaños equilibrados (722, 837, 776 y 715 observaciones), lo que refuerza la estabilidad del modelo.
- Los segmentos reflejan cuatro lógicas de percepción distintas: quienes priorizan la **funcionalidad**, quienes valoran la **innovación**, quienes buscan un perfil **equilibrado**, y quienes responden a la **emoción y la novedad**.
- A nivel de posicionamiento, dos marcas mostraron perfiles bien diferenciados: Papa, asociada a lo funcional y cercano (intuitiva, confiable, fácil de usar), y Tango, asociada a lo emocional e innovador (moderna, atractiva, buena relación valor-precio).
- A partir de estos perfiles se propusieron lineamientos estratégicos de posicionamiento por marca.

## Tecnologías

- Python (pandas, scikit-learn, matplotlib, seaborn)

## Estructura del repositorio
