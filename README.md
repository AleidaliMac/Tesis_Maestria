# Detección de zonas de potencial crecimiento para las micro empresas en Nuevo León, Nayarit y Yucatán, basado en técnicas de Clustering Espectral
*Trabajo de tesis para obtener el grado de Maestra en Cómputo Estadístico CIMAT Monterrey*
*Presenta
Yareli Aleidali Macías Ángeles
Director de Tesis:
Dra. Graciela Ma. González Farías

Resumen
En México, las micro empresas representan alrededor de 95% de los establecimientos
y concentran a 37.2% de la población ocupada, por lo que representan el primer
canal por el cual muchos mexicanos cuentan con un trabajo o deciden emprender y
ser fuente de trabajo.
En este proyecto de tesis se presenta una propuesta de modelo de clustering que
permita detectar las zonas que han presentado un escenario favorecedor para los micro
negocios, es decir, en las cuales se ha dado un crecimiento económico acompañado de
bienestar social y no sólo como consecuencia de la expansión urbana.
El modelo toma como base información pública del INEGI a nivel localidad, del
DENUE se obtiene la información sobre los negocios en México y del Censo se obtienen
las variables socio-demográficas. Posteriormente, se aplica la técnica de selección de
variables SPEC propuesto por Zhao y Liu. (2007), de la cual se obtiene un ranking
por nivel de relevancia de cada variable y que es utilizado en la fase agrupamiento.
Se aplica el algoritmo de Clustering Espectral propuesto por Ng, Jordan, y Weiss
(2002) con un par de variantes: (1) en la función de similitud RBF kernel se utiliza un
parámetro de escala local sigma_i en lugar del parámetro global sigma Zelnik-Manor y Perona
(2004) y (2) se elige el valor óptimo de clústeres utilizando criterios de ajuste clásicos
en conjunto con el heurístico Eigengap y la Búsqueda iterativa del Eigengap Afzalan
y Jazizadeh (2019).
El resultado de este trabajo se presenta en forma de mapas interactivos de consulta
pública, los cuales contienen un ranking de localidades por estado de acuerdo al
potencial del sector micro y al nivel de bienestar que han presentado en los últimos
años.


Link Dashboard:
https://app.powerbi.com/view?r=eyJrIjoiZDBiOWFkZWUtMWUyZS00NmViLTk3ZTgtYmNjOWQzYTUzMzVjIiwidCI6IjA3YTgxZjc2LWQwMzEtNGUzOC04YTZmLWQ5MzQ5Y2QwMzI4MSJ9

Link Código:
https://colab.research.google.com/drive/1z8TjqocS-kayVvVcAduFQpcsV1baK2VC?usp=sharing#scrollTo=d11moZ4qUnEe

