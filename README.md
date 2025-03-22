<div align="center">
  <h1>PROYECTO ETL - MONITORÍA 3280</h1>
  <p>EVALUACIÓN DEL CUMPLIMIENTO DE LA RUTA MATERNO-PERINATAL EN LAS IPS</p>
  <img src="https://github.com/ManuelG09/Equipo-4-GYA/blob/main/images/etl.png" width="100">
  <img src="https://github.com/ManuelG09/Equipo-4-GYA/blob/main/images/Gestante.jpg" width ="50">
</div>

<div align="justify">
  <h3>Objetivo:</h3> Evaluar y optimizar el cumplimiento de la Resolución 3280 de 2018 en las IPS que trabajan con la Asociación Indígena del Cauca EPSI, a través de un sistema de monitoreo automatizado basado en datos.
</div>
<div align="justify">
  <p></p>
</div>
<div align="justify">
  <h3>Fuentes de Datos</h3>
  <div>
<h4>📊 Análisis del Dataset: GESTANTES CORTE 2024</h4>
<div>🏥 1. Identificación de las Fuentes de Datos</div>
Este dataset proviene de registros clínicos y administrativos relacionados con gestantes, diligenciados en cada institución prestadora de salud. Conocer su origen es clave para garantizar calidad y fiabilidad. 
Posibles fuentes:
<br>&nbsp;&nbsp;📌 Registros hospitalarios de atención prenatal y parto.
<br>&nbsp;&nbsp;🏛️ Bases de datos del sistema de salud de las entidades.
<br>&nbsp;&nbsp;🤰 Información recopilada por IPS y EPS.<br>
<br>
<div>📂 2. Estructura del Dataset</div>
<br>&nbsp;&nbsp;📊 Tamaño: 7,309 filas y 422 columnas.
<br>&nbsp;&nbsp;🔢 111 columnas → tipo float64 (valores numéricos decimales).
<br>&nbsp;&nbsp;🔤 311 columnas → tipo object (texto o datos mixtos).<br>
<br>
<div>⚠️ 3. Posibles Problemas Identificados</div>
<br>&nbsp;&nbsp;❌ Errores en fechas: Algunos valores están fuera de rango.
<br>&nbsp;&nbsp;📉 Datos desnormalizados: El alto número de columnas sugiere posible redundancia.
<br>&nbsp;&nbsp;⚠️ Valores nulos: Muchas columnas contienen datos faltantes.

<h4>📊 Análisis del Dataset: RIPS_GESTANTES</h4></div>
<div>🏥 1. Identificación de las Fuentes de Datos</div>
Este dataset contiene información detallada sobre la atención en salud de gestantes, incluyendo:
<br>&nbsp;&nbsp;📌 Código de actividades realizadas.
<br>&nbsp;&nbsp;🆔 Identificación de gestantes y datos poblacionales.
<br>&nbsp;&nbsp;💰 Costos y diagnósticos facturados por cada prestador a la EPS.
<br>&nbsp;&nbsp;📌 Calidad de datos: Mayor precisión en comparación con la base en Excel, ya que se genera directamente desde los sistemas de información de los prestadores.<br>
<br>
<div>📂 2. Estructura del Dataset</div></div>
<br>&nbsp;&nbsp;📊 Tamaño: 251,878 registros y 52 columnas.
</div>
