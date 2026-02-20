 Decisión: Implementacion de Landmarks ARIA
 Principio SWEBOK: Software Requirements - Compliance with Standards.
 Racional: Para cumplir con el requisito no funcional de accesibilidad (WCAG 2.2), se estructuró el wireframe usando regiones semánticas. Esto reduce la carga cognitiva y el esfuerzo de navegación para usuarios con lectores de pantalla  o navegación por teclado
 y  Facilitar la verificabilidad de los requisitos de accesibilidad durante la fase de pruebas.

 Decisión: Navegación Tabular Lógica y Jerárquica
 Principio SWEBOK: Software Construction - Construction for Verification.
 Racional: El orden de las capas en Figma se organizó para reflejar el orden del DOM (Document Object Model). Esto se hizo para facilitar la Construcción del software, permitiendo que el código HTML siga una secuencia lógica sin necesidad de parches complejos de CSS.
 Impacto: Asegura que el producto construido sea fiel al prototipo en términos de accesibilidad técnica.

 Decisión: Uso de un Sistema de Rejilla (Grid) de 8px
 Principio SWEBOK: Software Design - Design Quality Analysis.
 Racional: La adopción de un sistema de diseño atómico y una rejilla técnica asegura la Mantenibilidad y la Escalabilidad del front-end. Permite que otros ingenieros repliquen interfaces coherentes sin ambigüedades visuales.
 Impacto: Mejorar la comunicación entre diseñadores y desarrolladores, reduciendo la deuda técnica visual.



