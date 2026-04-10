&#x20;Trabajo Práctico Final — Ingeniería de Prompts 

10 de Abril del 2026

Curso: GEMINI

Participante: Matilde Miranda Luna

Gemini: Última actualización: 8 de abril de 20268 de abril de 2026



###### **Prompt 1 Prompt de lógica compleja (CRFT + CoT)**



"Actúa como un Arquitecto de Sistemas de IA. Tu Tarea es realizar un análisis técnico para justificar si el aumento de la ventana de contexto en un LLM garantiza proporcionalmente una mayor precisión en la recuperación de información.



###### **Prompt 2  Automatización (Google Sheets)**



=GEN("Actúa como analista de mercado. Compara el producto " \& A5 \& " con el competidor " \& B5 \& ". Usando tu conocimiento de mercado; categoriza la estrategia de precios de A2 en un único término (ej: Liderazgo de Costos, Diferenciación o Nicho).")



Resultado 1 Papa fritas	Burger KING	Liderazgo de Costos

Resultado 2 Papa fritas	Carls jr	Diferenciación



###### **Prompt 3 (Desafío 3: Diseño de Jerarquía de Análisis (Mitigación de Chunking)) ( De momento se cuenta con un documento de 138 páginas cn el siguiente enlace http://lac.unfpa.org/sites/default/files/pub-pdf/Embarazo%20en%20Adolescentes.pdf**



Eres un director de estrategia regional experto en auditoría documental. Analiza el informe adjunto de 138 páginas para dar una recomendación de política pública para el próximo trimestre. Lista numerada estricta, con una sola recomendación final. 

Jerarquía de Análisis (CoT Estricto)

Paso a Paso: 

1\. Revisar datos social, cultural y económico de los/as adolescente (p. 1-43) para extraer las 2 regiones con peor crecimiento y citar el crecimiento %. 

2\. Revisar los resultados de los estudios (p. 43-87 ) para identificar si hay problemas de suministro en esas 2 regiones. 

3\. Revisar recomendaciones del estudio considerando el contexto (p. 88-138) para identificar 2 oportunidades de mitigación aplicables a esas regiones. 

4\. Concluir con la recomendación ejecutiva final.





###### **Prompt 4  Multimodalidad (OCR)**

Componente

Prompt Maestro de Extracción OCR



Version 1.0 Actúa como un analista contable especializado en la extracción de datos de facturas.Utiliza la función OCR para analizar la imagen de la factura adjunta y extraer 3 campos de datos específicos.Presenta los resultados obligatoriamente en formato JSON con las claves: "Total\_Adeudado", "Fecha\_Vencimiento", y "Numero\_Factura". Tool Utiliza la capacidad de Multimodalidad / OCR para la extracción.



Version 1.1 Actúa como un analista contable especializado en la extracción de datos de facturas.Tarea (R/T)Utiliza la función OCR para analizar la imagen de la factura adjunta y extraer 3 campos de datos específicos.Formato (F)Presenta los resultados obligatoriamente en formato JSON con las claves: "Producto con mayor precio unitario", "Fecha\_Vencimiento", y "Numero\_Factura". Tool Utiliza la capacidad de Multimodalidad / OCR para la extracción.

###### 

###### **Prompt 5 Estrategia SMART**



El prompt aplica el Marco de Planificación SMART para desglosar un objetivo genérico en tareas ejecutables.

Componente

Prompt Maestro de Planificación SMART

Rol (C/R)

Eres un Project Manager certificado en la metodología SMART.Tarea (R/T) Transforma el objetivo vago "Mejorar la retención de clientes el próximo trimestre" en 3 tareas SMART específicas. Formato (F) Presenta el resultado en una tabla de tres columnas: "Fase", "Tarea SMART" y "Métrica/Plazo". Restricción (T) Cada tarea debe incluir un verbo de acción, una métrica de finalización clara y un plazo definido.



