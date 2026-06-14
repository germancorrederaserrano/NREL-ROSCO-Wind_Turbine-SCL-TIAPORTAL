# NREL ROSCO Wind Turbine Controller in Siemens SCL TIA Portal

Este repositorio contiene la traducción y ha sido validado matemática/estadísticamente del controlador de referencia de código abierto ROSCO (Reference Open-Source Controller) de la NREL https://www.nlr.gov/ (link nuevo) (National Renewable Energy Laboratory), implementado íntegramente en lenguaje SCL (Structured Control Language)
-precisión: el algoritmo ha sido validado obteniendo un 90% de VAF respecto a las simulaciones originales de la NREL.
-optimización: estructurado para entornos industriales deterministas en tiempo real. 
-estado actual: lógica principal de control de pitch y par electromagnetio operativa (incluyendo modulos para la protección de la estructura como por ejemplo IPC o Fore aft damping, reduciendo el DEL). a futuras: turbinas flotantes, estimador de viento y más cambios sutiles. a futuras:  se ha observado que el fore-aft damping aumenta el DEL (damage) de las bases de las palas. 

# Publicación (Jornadas de Automatización 2026)
Este desarrollo y su validación forman parte del artículo técnico aceptado para su presentación en las Jornadas de Automatización 2026 (Córdoba, España).

# Instrucciones de implementación
Todo ha sido implementado en un OB35 de interrupción cíclica de 12.5 ms de período de muestreo. 
Para comparaciones, úsese los mismos parámetros para ambos controladores. 
modelo usado: 5MW_Land_DLL_WTurb

# Propiedad Intelectual y Licencia
Copyright (C) 2026 Germán Corredera Serrano. Todos los derechos reservados.
El código se expone exclusivamente con fines académicos, demostrativos y de revisión para las Jornadas de Automatización. Queda prohibida su reproducción o uso comercial sin autorización explícita del autor.
