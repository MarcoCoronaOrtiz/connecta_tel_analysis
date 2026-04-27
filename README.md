# connecta_tel_analysis
Analsysis on users consumption for connecta tel

Objetivo del proyecto:
Identificar patrones de uso, detectar comportamientos atípicos y comprender qué segmentos de clientes muestran necesidades diferenciadas, con el fin de optimizar la oferta comercial y mejorar la experiencia del usuario.

'Datasets' utilizados:
- plans.csv: los planes actuales (precio, minutos incluidos, GB incluidos, costo por extra).
- users_latam.csv: información de clientes: edad, ciudad, fecha de registro, plan contratado.
- usage.csv: el detalle de uso real: llamadas (duración) y mensajes (longitud).

Etapas del análisis realizadas:
- Importación y exploración de las bases de datos,
 <img width="502" height="256" alt="image" src="https://github.com/user-attachments/assets/4a3a8958-e93d-4203-a9ce-bdbe4d65d3e2" />

- Limpieza de valores nulos y detección de valores inválidos y sentinels,
<img width="722" height="152" alt="image" src="https://github.com/user-attachments/assets/4c698ee5-3082-42bb-87f9-04d4be5bc0fa" />


- Estandarización de datos (formato de fechas, tratamiento de datos inválidos y sentinels y fechas imposibles,
<img width="642" height="270" alt="image" src="https://github.com/user-attachments/assets/fcb2694a-0cbc-4e0b-9d45-f762164b16af" />


- Análisis estadístico a través de agrupaciones numéricas y categóricas,
<img width="1392" height="626" alt="image" src="https://github.com/user-attachments/assets/dfe6024a-e908-4874-8ccc-5dba43dd208e" />


- Creación de histogramas para revelar el comportamiento de consumo a través de planes y grupos de edad, para también identificar sesgos,
<img width="818" height="727" alt="image" src="https://github.com/user-attachments/assets/28b4d5d5-7199-4a78-8528-3d8b5098b2b9" />


- Creación de gráficas de cajas para revelar valores extremos (outliers), y complementar el análisis de consumo de los usuarios),
<img width="688" height="566" alt="image" src="https://github.com/user-attachments/assets/f99f97ef-dcb8-4e0c-ab34-4a1edbf8304d" />


- Cálculo de valores intercuartiles (IQR),
<img width="750" height="251" alt="image" src="https://github.com/user-attachments/assets/8fd37385-5521-4a6c-a011-7dde5f820d41" />


- Segmentación y visualización de consumidores por grupos de uso y edad.
<img width="463" height="223" alt="image" src="https://github.com/user-attachments/assets/8b78257e-abe6-4de3-bbf8-b6f19b5c6d5a" />
<img width="722" height="681" alt="image" src="https://github.com/user-attachments/assets/98629dc9-2cf5-4376-8aae-ad6824c66129" />


Ejecución del notebook en Google Colab:

Haz clic en el siguiente botón:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1dSCIFo0bLPX4wz2VWTMCkp1P12a7Sdso)

O
1. Abre el archivo .ipynb en GitHub
2. Haz clic en Open in Colab
