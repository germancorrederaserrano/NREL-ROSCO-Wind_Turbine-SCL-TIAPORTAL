# NREL ROSCO Wind Turbine Controller in Siemens SCL TIA Portal
This repository contains the translation and has been mathematically/statistically validated of the reference open-source controller ROSCO (Reference Open-Source Controller) from NREL https://www.nlr.gov/ (National Renewable Energy Laboratory), implemented entirely in SCL language (Structured Control Language)
-precision: the algorithm has been validated obtaining a 90% of VAF regarding the original simulations of the NREL.
-optimization: structured for real-time deterministic industrial environments.
-current status: main logic of pitch and electromagnetic torque control operational (including modules for the protection of the structure such as for example IPC or Fore aft damping, reducing the DEL). for the future: floating turbines, wind estimator and more subtle changes. for the future: it has been observed that the fore-aft damping increases the DEL (damage) of the blade bases, solution planned for next revisions

# Publication
This development and its validation are part of the technical article accepted for its presentation at the Jornadas de Automatización 2026 (Córdoba, Spain).

# Implementation instructions
Everything has been implemented in a cyclic interrupt OB35 of 12.5 ms of sampling period.
For comparisons, use the same parameters for both controllers.
model used: '5MW_Land_DLL_WTurb'

# Intellectual Property and License
Copyright (C) 2026 Germán Corredera Serrano. All rights reserved.
The code is exposed exclusively for academic and demonstrative purposes. Its reproduction or commercial use without explicit authorization from the author is prohibited.













# NREL ROSCO Wind Turbine Controller in Siemens SCL TIA Portal

Este repositorio contiene la traducción y ha sido validado matemática/estadísticamente del controlador de referencia de código abierto ROSCO (Reference Open-Source Controller) de la NREL https://www.nlr.gov/ (National Renewable Energy Laboratory), implementado íntegramente en lenguaje SCL (Structured Control Language)
-precisión: el algoritmo ha sido validado obteniendo un 90% de VAF respecto a las simulaciones originales de la NREL.
-optimización: estructurado para entornos industriales deterministas en tiempo real. 
-estado actual: lógica principal de control de pitch y par electromagnetio operativa (incluyendo modulos para la protección de la estructura como por ejemplo IPC o Fore aft damping, reduciendo el DEL). a futuras: turbinas flotantes, estimador de viento y más cambios sutiles. a futuras:  se ha observado que el fore-aft damping aumenta el DEL (damage) de las bases de las palas, solución planificada para próximas revisiones

# Publicación
Este desarrollo y su validación forman parte del artículo técnico aceptado para su presentación en las Jornadas de Automatización 2026 (Córdoba, España).

# Instrucciones de implementación
Todo ha sido implementado en un OB35 de interrupción cíclica de 12.5 ms de período de muestreo. 
Para comparaciones, úsese los mismos parámetros para ambos controladores. 
modelo usado: 5MW_Land_DLL_WTurb

# Propiedad Intelectual y Licencia
Copyright (C) 2026 Germán Corredera Serrano. Todos los derechos reservados.
El código se expone exclusivamente con fines académicos y demostrativos. Queda prohibida su reproducción o uso comercial sin autorización explícita del autor.
