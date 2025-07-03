## Analisis de venta de videojuegos
Análisis de ventas de videojuegos por región, plataforma y género para identificar patrones clave, permitiendo a Ice detectar proyectos con alto potencial y diseñar campañas publicitarias efectivas. El estudio de las dinámicas de mercado en Norteamérica, Europa y Japón busca optimizar estrategias de marketing y maximizar el ROI en los lanzamientos más prometedores.

### herramientas y tipo de proyecto
![Python](https://img.shields.io/badge/python-357ebd?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23357ebd.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23357ebd.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)
![Seaborn](https://img.shields.io/badge/Seaborn-357ebd?style=for-the-badge)
![SciPy](https://img.shields.io/badge/SciPy-%23357ebd.svg?style=for-the-badge&logo=scipy&logoColor=white)
![Limpieza de datos](https://img.shields.io/badge/Limpieza_de_datos-295F98?style=for-the-badge)
![Transformación de datos](https://img.shields.io/badge/Transformación_de_datos-295F98?style=for-the-badge)
![Análisis de datos](https://img.shields.io/badge/Análisis_de_datos-295F98?style=for-the-badge)
![Pruebas de hipótesis](https://img.shields.io/badge/Pruebas_de_hipótesis-295F98?style=for-the-badge)
![Visualización de datos](https://img.shields.io/badge/Visualización_de_datos-295F98?style=for-the-badge)

### Puntos clave de investigación
Tendencias de plataformas: Distribución de ventas globales y variaciones regionales.
Preferencias de género: Popularidad comparativa en Norteamérica, Europa y Japón.
Impacto de reseñas: Relación entre puntuaciones (usuarios/críticos) y desempeño comercial.
Diferencias cualitativas: Calificaciones promedio por plataforma y género.

### Enfoque metodológico
Limpieza de datos: Eliminación de inconsistencia (datos faltantes/duplicados) y estandarización de formatos.
EDA: Identificación de patrones en plataformas/géneros y análisis de correlación reseñas-ventas.
Análisis regional: Contraste de preferencias entre mercados clave.
Validación estadística: Pruebas de hipótesis para comparar evaluaciones de usuarios.

### Hallazgos y acciones estratégicas
Preferencias regionales:
1. Occidente: Dominio de acción/disparos en Xbox/PlayStation.
2. Japón: Predominio de RPG en portátiles (3DS).
Influencia de reseñas:
1. Críticos: impactan ventas (r≈0.35)
2. usuarios: mínimo efecto.
La brecha comercial entre géneros sugiere que los juegos con narrativas inmersivas (RPG) o mecánicas competitivas (deportes/disparos) tienen mayor aceptación global.

## Resultados clave:
Xbox One y PC: calificaciones similares.
Acción vs. Deportes: diferencias significativas.

### Recomendaciones:
Priorizar PS4/Xbox One en campañas globales.
Localizar estrategias: RPG en Japón; acción/disparos en Occidente.

## Visualizaciones

**Análisis de ventas por género**
Tendencias destacadas:
- Géneros más vendidos: Acción, disparos (shooters), juegos de rol (RPG) y deportes lideran el mercado.
- Géneros con menor demanda: Rompecabezas y estrategia registran ventas significativamente más bajas.
![ventas](assets/img/games_ventas_por_genero.png)

**Relación entre críticas y desempeño comercial**
Se observa una correlación moderada (coeficiente ~0.4) entre las valoraciones de expertos y el volumen de ventas, lo que sugiere que:
Las reseñas profesionales influyen parcialmente en las decisiones de compra.
Los consumidores no basan su elección únicamente en este factor (otros elementos como franquicias, marketing o preferencias personales podrían tener mayor peso).
![critica](assets/img/games_critic_score_correlacion.png)
