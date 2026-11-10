---
layout: page
permalink: /schedule/
title: Programa
description: La 2da Escuela de Primavera en Deep Learning se dará entre el 11 y el 13 de noviembre de 2026.
nav: true
nav_order: 2
---

<style>
  .schedule-wrapper { width: 100%; overflow-x: auto; }
  .schedule-grid {
    display: grid;
    grid-template-columns: repeat(3, minmax(220px, 1fr));
    gap: 6px;
    min-width: 700px;
    text-align: center;
  }
  .schedule-grid > div {
    padding: 10px;
    border-radius: 6px;
    display: flex;
    flex-direction: column;
    justify-content: center;
  }
  .schedule-grid .head {
    background-color: rgb(215, 215, 215);
    font-weight: 700;
    border-bottom: 1pt solid black;
  }
  .schedule-grid .time {
    display: block;
    font-size: 0.8em;
    font-weight: 500;
    color: #555;
  }
  .schedule-grid .talk { background-color: #e8ecf8; }
  .schedule-grid .posters { background-color: #dff1ec; grid-row: span 2; }
  .schedule-grid .panel { background-color: #ece6f6; }
  .schedule-grid .lunch { background-color: #faefd9; }
  .schedule-grid .break { background-color: #f0f0f0; font-size: 0.9em; }
  .schedule-grid .cocktail { background-color: #fde3d6; }
  .schedule-grid .empty { background: none; }
</style>


<div class="schedule-wrapper">
<div class="schedule-grid">
<div class="head">Miércoles<br>11 de noviembre</div>
<div class="head">Jueves<br>12 de noviembre</div>
<div class="head">Viernes<br>13 de noviembre</div>
<div class="talk"><span class="time">09:00 - 09:15</span><i>Apertura</i><br><br><span class="time">09:15 - 10:45</span>"Modelos generativos para series temporales" <strong>Felipe Tobar</strong><br><small><i>Imperial College London</i></small></div>
<div class="talk"><span class="time">09:00 - 10:30</span>"Causalidad y Transfer Learning: Qué haces cuando no ves?" <strong>Mariela Sued</strong><br><small><i>Universidad de San Andrés - CONICET</i></small><br><br><span class="time">10:30 - 10:45</span><i>Charla Sponsor: Multidisciplinary Institute in Artificial Intelligence of Grenoble</i></div>
<div class="talk"><span class="time">09:00 - 10:30</span>"Eficiencia en LLMs y sistemas agénticos: de la GPU a la orquestación, métodos para una adopción generalizada" <strong>Luciano del Corro</strong><br><small><i>Universidad de San Andrés</i></small></div>
<div class="break"><span class="time">10:45 - 11:15</span><i>Coffee break</i></div>
<div class="break"><span class="time">10:45 - 11:15</span><i>Coffee break</i></div>
<div class="break"><span class="time">10:30 - 11:00</span><i>Coffee break</i></div>
<div class="talk"><span class="time">11:15 - 12:45</span>"Exploración y análisis de representaciones internas en redes neuronales" <strong>Celia Cintas</strong><br><small><i>IBM Research - Africa</i></small></div>
<div class="talk"><span class="time">11:15 - 12:45</span>"Métodos Estadísticos para Validación de IA" <strong>Jeremías Sulam</strong><br><small><i>Johns Hopkins University</i></small></div>
<div class="talk"><span class="time">11:00 - 12:30</span>"Aprendizaje con matrices de covarianza: Análisis de componentes principales desde una perspectiva de grafos" <strong>Gonzalo Mateos</strong><br><small><i>University of Rochester</i></small></div>
<div class="lunch"><span class="time">12:45 - 14:00</span><strong><i>Almuerzo</i></strong></div>
<div class="lunch"><span class="time">12:45 - 14:00</span><strong><i>Almuerzo</i></strong></div>
<div class="lunch"><span class="time">12:30 - 14:00</span><strong><i>Almuerzo</i></strong></div>
<div class="talk"><span class="time">14:00 - 14:45</span>"Métodos basados en aprendizaje para la reconstrucción de imágenes" <strong>Julian Tachella</strong><br><br><span class="time">14:45 - 15:30</span>"Segmentación anatómica robusta de imágenes médicas mediante redes neuronales en grafos" <strong>Enzo Ferrante</strong><br><br><span class="time">15:30 - 15:45</span><i>Charla Sponsor: ZS</i></div>
<div class="talk"><span class="time">14:00 - 15:30</span>"Del ruido al diseño de proteínas: introducción a modelos de difusión" <strong>Tomás Geffner</strong><br><small><i>NVIDIA</i></small></div>
<div class="talk"><span class="time">14:00 - 15:30</span>"¿Qué mira la máquina cuando nos mira? Luces, sombras y puntos ciegos de la visión artificial" <strong>Gabriel Kreiman</strong><br><small><i>Harvard Medical School y Engramme</i></small></div>
<div class="posters"><span class="time">15:45 - 17:30</span><strong><i>Sesión de pósters + coffee</i></strong></div>
<div class="break"><span class="time">15:30 - 16:00</span><i>Coffee break</i></div>
<div class="empty"></div>
<div class="talk"><span class="time">16:00 - 17:00</span>"Los obreros de la IA: trabajo de datos, precarización y sesgos" <strong>Milagros Miceli</strong><br><small><i>DAIR Institute</i></small></div>
<div class="empty"></div>
<div class="cocktail"><span class="time">17:30 - 19:00</span><strong><i>Cocktail de bienvenida</i></strong></div>
<div class="panel"><span class="time">17:00 - 18:00</span><strong>Panel</strong></div>
<div class="empty"></div>
</div>
</div>

<br>

## Pósters

<style>
  .poster-list { list-style: none; padding: 0; margin: 0; }
  .poster-item { border-bottom: 1px solid #e0e0e0; }
  .poster-item:last-child { border-bottom: none; }
  .poster-toggle {
    width: 100%; text-align: left; background: none; border: none;
    padding: 12px 8px; cursor: pointer; font-size: 1em;
    display: flex; align-items: baseline; gap: 8px;
  }
  .poster-toggle:hover { background-color: #f5f5f5; }
  .poster-toggle .poster-arrow {
    display: inline-block; transition: transform 0.2s; font-size: 0.7em; flex-shrink: 0;
  }
  .poster-toggle[aria-expanded="true"] .poster-arrow { transform: rotate(90deg); }
  .poster-num { font-weight: 700; color: #555; min-width: 28px; flex-shrink: 0; }
  .poster-title-text { font-weight: 600; }
  .poster-author { font-weight: 400; color: #666; font-size: 0.92em; }
  .poster-body {
    display: none; padding: 4px 8px 16px 44px; font-size: 0.93em; line-height: 1.5;
  }
  .poster-body.open { display: block; }
  .poster-affiliation { font-style: italic; color: #888; margin-bottom: 6px; }
  .poster-abstract { color: #333; }
</style>

<ul class="poster-list">
<li class="poster-item">
  <button class="poster-toggle" aria-expanded="false" onclick="this.setAttribute('aria-expanded', this.getAttribute('aria-expanded')==='true'?'false':'true'); this.nextElementSibling.classList.toggle('open')">
    <span class="poster-arrow">&#9654;</span>
    <span class="poster-num">1.</span>
    <span><span class="poster-title-text">Distintos Mecanismos para el uso de Chain-of- Thought</span> — <span class="poster-author">Juan José Alegría Fuentes</span></span>
  </button>
  <div class="poster-body">
    <div class="poster-affiliation">U. de Chile / CENIA</div>
    <div class="poster-abstract">El Chain-of-Thought (CoT) mejora el rendimiento de los modelos de lenguaje de gran tamaño (LLMs) y se ha presentado como una ventana a su razonamiento, aunque trabajos recientes cuestionan que el CoT refleje el cómputo que produce una respuesta. Por ello, la naturaleza de la relación entre el CoT y la respuesta, así como los mecanismos subyacentes, siguen siendo poco claros. En este trabajo nos hacemos dos preguntas: primero, si el CoT es necesario para generar la respuesta y suficiente por sí solo; segundo, cómo lo utilizan los modelos a nivel mecanicista. Para estudiar estas preguntas, diseñamos un banco de pruebas controlado: una tarea simbólica de múltiples saltos en la que el CoT sigue un camino hasta una referencia terminal cuyo valor está almacenado en una tabla de consulta. Entrenamos 81 modelos con 27 configuraciones de arquitectura, variando la profundidad, el ancho y la inicialización aleatoria. Mediante activation patching, evaluamos la necesidad del CoT reemplazando la traza y manteniendo fijo el prompt, y su suficiencia reemplazando el prompt y manteniendo fija la traza. El CoT es necesario en todos los modelos: reemplazarlo hace colapsar la probabilidad de la respuesta esperada. Su suficiencia, en cambio, varía de forma sustancial. Combinando intervenciones complementarias, linear probes y las respuestas producidas bajo intervención, logramos distinguir dos mecanismos de uso del CoT: los estados ocultos del CoT (i) almacenan la respuesta ya resuelta, o (ii) actúan como un puntero hacia la tabla de consulta, de modo que la recuperación ocurre solo en el momento de responder. Así, trazas de CoT idénticas pueden sustentar cómputos fundamentalmente distintos. El mecanismo que se implementa está condicionado por el tamaño del modelo: el mecanismo de puntero surge únicamente en modelos suficientemente profundos y anchos. Aun así, el tamaño por sí solo no determina qué mecanismo se aprenderá: modelos con arquitecturas y datos de entrenamiento idénticos pueden converger a mecanismos distintos únicamente por efecto de la inicialización aleatoria, de modo que una explicación mecanicista derivada de un modelo entrenado podría no generalizarse a otro con la misma arquitectura y los mismos datos.</div>
  </div>
</li>
<li class="poster-item">
  <button class="poster-toggle" aria-expanded="false" onclick="this.setAttribute('aria-expanded', this.getAttribute('aria-expanded')==='true'?'false':'true'); this.nextElementSibling.classList.toggle('open')">
    <span class="poster-arrow">&#9654;</span>
    <span class="poster-num">2.</span>
    <span><span class="poster-title-text">Generación composicional zero-shot de ensambles conformacionales de proteínas condicionada a ligandos</span> — <span class="poster-author">Facundo Alvarez Motta</span></span>
  </button>
  <div class="poster-body">
    <div class="poster-affiliation">UBA, Argentina</div>
    <div class="poster-abstract">La función de una proteína no está determinada por una única estructura sino por el ensamble de conformaciones que visita en equilibrio, distribución que se ve modulada por la presencia de ligandos. Caracterizar ese ensamble por dinámica molecular es informativo pero computacionalmente costoso, y el costo se vuelve prohibitivo cuando se quiere explorar la combinatoria de múltiples estados conformacionales estables. En esta tesis abordamos el problema de generar ensambles conformacionales del sitio activo de una proteína condicionados a ligandos mediante un modelo generativo de difusión basado en score, y proponemos como aporte central un método para generar el ensamble de combinaciones de ligandos nunca observadas durante el entrenamiento (zero-shot). El modelo se construye sobre una red de score E(3)-equivariante (EGNN) con centro de masa nulo, entrenada por denoising score matching sobre trayectorias de dinámica molecular y condicionada al ligando a través de un canal invariante con guía libre de clasificadores. Aplicamos el método a la TcAKR, una enzima presente en el parásito Trypanosoma cruzi (agente causal de la enfermedad de Chagas), de interés como objetivo terapéutico. Bajo una hipótesis de aditividad energética entre las contribuciones de cada ligando sobre un fondo de referencia sin ligando (apoenzima) común, derivamos la identidad composicional de scores, que demostramos exacta por construcción para todo tiempo de difusión y que concentra toda la física del problema en un único supuesto falsable. Esto permite muestrear el ensamble de un sistema con dos ligandos a partir únicamente de modelos entrenados sobre las condiciones individuales. Evaluamos la generalización composicional zero-shot contra trayectorias de dinámica molecular de las condiciones combinadas reservadas íntegramente como referencia, validando primero la fidelidad del modelo condicional sobre cada ensamble individual y contextualizando los resultados contra líneas base internas que aíslan las decisiones de diseño. La construcción no depende del sistema particular ni se restringe a dos ligandos, generalizándose a K ligandos sin reentrenamiento, con valor directo para el descubrimiento de fármacos.</div>
  </div>
</li>
<li class="poster-item">
  <button class="poster-toggle" aria-expanded="false" onclick="this.setAttribute('aria-expanded', this.getAttribute('aria-expanded')==='true'?'false':'true'); this.nextElementSibling.classList.toggle('open')">
    <span class="poster-arrow">&#9654;</span>
    <span class="poster-num">3.</span>
    <span><span class="poster-title-text">Reconstrucción de Radar de Apertura Sintética mediante Destilación de Conocimiento</span> — <span class="poster-author">Sarah Camila Aranibar Velasquez</span></span>
  </button>
  <div class="poster-body">
    <div class="poster-affiliation">Universidad Privada Boliviana (UPB)</div>
    <div class="poster-abstract">La Tomografía de Radar de Apertura Sintética (TomoSAR) permite reconstruir el perfil de reflectividad de una escena en función de la elevación utilizando múltiples adquisiciones SAR complejas obtenidas desde diferentes pasadas satelitales. Sin embargo, su calidad depende del número de adquisiciones disponibles. Cuando se emplean menos pasadas, el problema de inversión se vuelve más difícil y pueden aparecer ambigüedades de elevación, pérdida de resolución y artefactos. Este trabajo propone el uso de destilación de conocimiento para mejorar la reconstrucción TomoSAR con un número reducido de adquisiciones SAR. Para ello, se entrena un modelo maestro con un conjunto más completo de pasadas, mientras que un modelo estudiante aprende a reconstruir el perfil tomográfico utilizando menos adquisiciones. Durante el entrenamiento, el estudiante imita tanto la reconstrucción final como representaciones intermedias generadas por el maestro. El objetivo es transferir la capacidad de reconstrucción aprendida en un escenario con mayor información hacia uno con menor disponibilidad de datos, mejorando la robustez y eficiencia del proceso en aplicaciones reales de percepción remota.</div>
  </div>
</li>
<li class="poster-item">
  <button class="poster-toggle" aria-expanded="false" onclick="this.setAttribute('aria-expanded', this.getAttribute('aria-expanded')==='true'?'false':'true'); this.nextElementSibling.classList.toggle('open')">
    <span class="poster-arrow">&#9654;</span>
    <span class="poster-num">4.</span>
    <span><span class="poster-title-text">Detección de retinopatía diabética referible en retinografías de campo ultra-amplio con ResNet-18</span> — <span class="poster-author">Lautaro Jose Barraza</span></span>
  </button>
  <div class="poster-body">
    <div class="poster-affiliation">PLADEMA, Argentina</div>
    <div class="poster-abstract">por ahora no esta definido si lo llevamos, mas cerca de la fecha confirmo.</div>
  </div>
</li>
<li class="poster-item">
  <button class="poster-toggle" aria-expanded="false" onclick="this.setAttribute('aria-expanded', this.getAttribute('aria-expanded')==='true'?'false':'true'); this.nextElementSibling.classList.toggle('open')">
    <span class="poster-arrow">&#9654;</span>
    <span class="poster-num">5.</span>
    <span><span class="poster-title-text">Hacia sistemas eficientes de traducción automática del habla para lenguas indígenas de América Latina</span> — <span class="poster-author">Diego Alberto Barriga Martínez</span></span>
  </button>
  <div class="poster-body">
    <div class="poster-affiliation">PCIC, UNAM, México</div>
    <div class="poster-abstract">La traducción automática del habla (AST) ha evolucionado desde sistemas en cascada hacia enfoques de extremo a extremo (end-to-end), los cuales reducen la latencia, la propagación de errores y los costos de entrenamiento. Sin embargo, los modelos estándar basados en arquitecturas transformer requieren miles de horas de audio alineado, recurso del que carecen la mayoría de las lenguas indígenas de América Latina debido a su condición de bajos recursos digitales y tradición predominantemente oral. Para enfrentar este reto, se plantea el uso de técnicas de ajuste fino eficiente en parámetros (PEFT), específicamente mediante la incorporación de capas de adaptadores (Adapters) en modelos masivos preentrenados cuya base permanece congelada. También, se explora el entrenamiento de modelos multitarea (ASR + AST) para enriquecer la capacidad del modelo de capturar los fenómenos fonéticos de lenguas indígenas. Se reportan resultados de corridas experimentales para el Mapugúngun y el Nahuatl. Esta investigación busca promover metodologías y modelos abiertos que contribuyan a reducir la brecha tecnológica en lenguas de bajos recursos e impulsar la inclusión de las comunidades hablantes en las tecnologías de voz modernas.</div>
  </div>
</li>
<li class="poster-item">
  <button class="poster-toggle" aria-expanded="false" onclick="this.setAttribute('aria-expanded', this.getAttribute('aria-expanded')==='true'?'false':'true'); this.nextElementSibling.classList.toggle('open')">
    <span class="poster-arrow">&#9654;</span>
    <span class="poster-num">6.</span>
    <span><span class="poster-title-text">Detección de alteraciones de la marcha en video sin marcadores mediante modelos de difusión condicional basados en puntuación (CSDI)</span> — <span class="poster-author">Paula Nicole Barrios</span></span>
  </button>
  <div class="poster-body">
    <div class="poster-affiliation">BiomedLab, Universidad Galileo, Guatemala</div>
    <div class="poster-abstract">La captura de movimiento sin marcadores reduce el costo y el tiempo del análisis de marcha, pero no existen datos normativos grabados con estos sistemas y, además, sus mediciones difieren de las de los sistemas con marcadores. En este estudio piloto armonizamos ambos tipos de datos con un mismo código de procesamiento y entrenamos un modelo de difusión condicional (CSDI) solo con marcha sana de una base pública medida con marcadores (WBDS, 51 adultos). Después lo probamos con 4 adultos sanos grabados con FreeMoCap y tres cámaras comunes, caminando normal y con una simulación que limitaba la flexión de la rodilla. Tras la armonización, la flexión de rodilla y de cadera coincidió con la de los marcadores (r = 0,98–0,99). El CSDI original no dio falsas alarmas en la marcha normal y separó los pasos con restricción de flexión de la rodilla de los normales con un AUROC de 0,97. También identificó la pierna correcta en el 91 % de los pasos y ubicó la anomalía en la fase de balanceo en el 79 %. La versión adaptada del modelo no mejoró la detección (AUROC 0,86). Estos resultados indican que un modelo entrenado solo con marcha sana de laboratorio puede detectar y localizar alteraciones de rodilla en video de bajo costo, lo que justifica probarlo con pacientes.</div>
  </div>
</li>
<li class="poster-item">
  <button class="poster-toggle" aria-expanded="false" onclick="this.setAttribute('aria-expanded', this.getAttribute('aria-expanded')==='true'?'false':'true'); this.nextElementSibling.classList.toggle('open')">
    <span class="poster-arrow">&#9654;</span>
    <span class="poster-num">7.</span>
    <span><span class="poster-title-text">Embeding de grafos para el análisis de cambios metabólicos usando datos de espectometría de masas</span> — <span class="poster-author">César Beltrán Castañón</span></span>
  </button>
  <div class="poster-body">
    <div class="poster-affiliation">Pontificia Universidad Católica del Perú</div>
    <div class="poster-abstract">El análisis metabolómico basado en espectrometría de masas (EM) es una herramienta poderosa, pero presenta sus propios desafíos. El flujo de trabajo de EM implica múltiples pasos antes de su interpretación, lo que se denomina minería de datos. La minería de datos consta de un proceso de dos pasos. Primero, los datos de EM se ordenan, organizan y presentan para su filtrado antes de ser analizados. Segundo, los datos filtrados y reducidos se analizan mediante estadística para eliminar la variabilidad. Esto es particularmente cierto para los estudios metabolómicos no dirigidos basados en EM, que se centran en comprender los cambios de pliegue en las redes metabólicas. Dado que la tarea de filtrar e identificar cambios en un conjunto de datos grande es compleja, se necesitan técnicas automatizadas para la minería de datos metabolómicos no dirigidos basados en EM. El enfoque tradicional basado en estadística tiende a sobrefiltrar los datos brutos, lo que puede resultar en la eliminación de datos relevantes y en la identificación de menos cambios metabolómicos. Esta limitación del enfoque tradicional subraya la necesidad de un nuevo método. En este trabajo, presentamos un nuevo enfoque de aprendizaje profundo que utiliza incrustaciones de nodos (basadas en GNN), incrustaciones de aristas y un algoritmo de detección de anomalías para analizar los datos generados por la metabolómica basada en espectrometría de masas (MS), denominada GEMNA (Graph Embedding-based Metabolomics Network Analysis).</div>
  </div>
</li>
<li class="poster-item">
  <button class="poster-toggle" aria-expanded="false" onclick="this.setAttribute('aria-expanded', this.getAttribute('aria-expanded')==='true'?'false':'true'); this.nextElementSibling.classList.toggle('open')">
    <span class="poster-arrow">&#9654;</span>
    <span class="poster-num">8.</span>
    <span><span class="poster-title-text">SparseCity: Un modelo basado en puntos para la generación de escenas semánticas dispersas a gran escala</span> — <span class="poster-author">Jesus Joan Moises Castillo Jesus</span></span>
  </button>
  <div class="poster-body">
    <div class="poster-affiliation">UTEC, Perú</div>
    <div class="poster-abstract">La generación de escenas urbanas 3D es cada vez más importante para aplicaciones como la simulación de conducción autónoma, la generación de datos sintéticos y los gemelos digitales. Los enfoques existentes suelen representar las escenas mediante rejillas volumétricas densas o representaciones factorizadas, como los triplanos, cuyo costo computacional y de memoria escala con el volumen espacial total, en lugar de hacerlo con el contenido de la escena. Dado que las escenas urbanas son inherentemente dispersas, esto genera una redundancia considerable, ya que la mayor parte de los recursos se destina a representar y procesar espacio vacío. Presentamos SparseCity, un modelo generativo multiescala basado en puntos que opera exclusivamente sobre el espacio ocupado, lo que reduce la complejidad de una función del volumen total a una función del número de puntos ocupados. SparseCity consta de un autoencoder basado en puntos que extrae representaciones latentes multiescala directamente de las regiones ocupadas. Estas representaciones condicionan un modelo de Flow Matching entrenado para generar escenas completas mediante un proceso que avanza de una escala gruesa a una fina. Evaluamos SparseCity en los conjuntos de datos CarlaSC y SemanticKITTI frente a SemCity y SSD, utilizando métricas de calidad generativa (FID, KID e IS) y de calidad semántica (exhaustividad y precisión).</div>
  </div>
</li>
<li class="poster-item">
  <button class="poster-toggle" aria-expanded="false" onclick="this.setAttribute('aria-expanded', this.getAttribute('aria-expanded')==='true'?'false':'true'); this.nextElementSibling.classList.toggle('open')">
    <span class="poster-arrow">&#9654;</span>
    <span class="poster-num">9.</span>
    <span><span class="poster-title-text">Exploración guiada por hipótesis en ambientes secuenciales</span> — <span class="poster-author">Pedro José Caycho Cañari</span></span>
  </button>
  <div class="poster-body">
    <div class="poster-affiliation">UTEC, Perú</div>
    <div class="poster-abstract">Propuesta: Desarrollar un mecanismo de exploración basado en hipótesis, donde el agente: Formula hipótesis sobre las reglas del entorno. Selecciona acciones para comprobarlas. Actualiza sus hipótesis según los resultados. Utiliza lo aprendido para tomar mejores decisiones. Diferenciación: En lugar de explorar simplemente por novedad o recompensa, el agente explora para entender cómo funciona el entorno. Evaluación: Comparar contra PPO, DQN y métodos de exploración como curiosidad, RND y Go- Explore. Se consideran entornos como MiniGrid, BabyAI y ARC-like. Resultados esperados: Menos interacciones para aprender (sample efficiency). Mejor generalización a escenarios desconocidos. Mayor capacidad para descubrir reglas ocultas.</div>
  </div>
</li>
<li class="poster-item">
  <button class="poster-toggle" aria-expanded="false" onclick="this.setAttribute('aria-expanded', this.getAttribute('aria-expanded')==='true'?'false':'true'); this.nextElementSibling.classList.toggle('open')">
    <span class="poster-arrow">&#9654;</span>
    <span class="poster-num">10.</span>
    <span><span class="poster-title-text">AI-IP Core para la estimación de ruido submarino</span> — <span class="poster-author">María Celeste Cebedio</span></span>
  </button>
  <div class="poster-body">
    <div class="poster-affiliation">- ICYTE - Univ. Nac. de Mar del Plata, Argentina</div>
    <div class="poster-abstract">Este trabajo presenta una comparación entre métodos clásicos, variantes de baja complejidad y soluciones basadas en inteligencia artificial (IA) comprimidas para estimar los parámetros del modelo de ruido de clase A de Middleton. Se desarrolla un modelo de IA para la estimación de los parámetros del ruido, con el fin de evaluar los compromisos entre precisión, latencia y eficiencia del hardware. Además, se implementa una red neuronal comprimida y optimizada, diseñada para su implementación en una FPGA. Para su entrenamiento se utiliza un enfoque de destilación de conocimiento, orientado a la optimización para entornos con recursos limitados. Mediante esta metodología, se busca determinar si estas técnicas mejoran el desempeño respecto de los modelos tradicionales. Finalmente, se realizan diversas comparaciones en software y hardware para evaluar el desempeño global del estimador.</div>
  </div>
</li>
<li class="poster-item">
  <button class="poster-toggle" aria-expanded="false" onclick="this.setAttribute('aria-expanded', this.getAttribute('aria-expanded')==='true'?'false':'true'); this.nextElementSibling.classList.toggle('open')">
    <span class="poster-arrow">&#9654;</span>
    <span class="poster-num">11.</span>
    <span><span class="poster-title-text">Development, system design, safety, and performance metrics of a conversational agent for reducing depressive and anxious symptoms based on a large language model: The MHAI study</span> — <span class="poster-author">Gianfranco Centeno Terrazas</span></span>
  </button>
  <div class="poster-body">
    <div class="poster-affiliation">Instituto de Datos e Inteligencia Artificial (IDIA), Perú</div>
    <div class="poster-abstract">Resumen Antecedentes Los agentes conversacionales basados en grandes modelos de lenguaje (LLM) han mostrado una eficacia moderada en la reducción de síntomas depresivos y de ansiedad. Sin embargo, la mayoría de las evaluaciones existentes carecen de transparencia metodológica, dependen de modelos de código cerrado y muestran una estandarización limitada en la evaluación del rendimiento y la seguridad. Objetivo Tenemos dos objetivos de estudio: (1) desarrollar un agente conversacional basado en LLM mediante análisis de diseño de sistemas y pruebas iniciales de funcionalidad, y (2) evaluar su seguridad y rendimiento mediante una evaluación estandarizada en interacciones simuladas controladas centradas en la depresión y ansiedad de dos LLM (GPT-4o y Llama 3.1-8B). Métodos Realizamos un estudio transversal en dos fases. En primer lugar, desarrollamos una plataforma de salud mental que integra un agente conversacional con funcionalidades que incluyen contexto personalizado, módulos terapéuticos preentrenados, herramientas de autoevaluación y un sistema de alerta de emergencia. En segundo lugar, evaluamos las respuestas del agente en interacciones simuladas basándonos en personas de usuario predefinidas para cada LLM. Cuatro evaluadores expertos evaluaron 816 pares de interacción utilizando una escala Likert de 5 puntos que evaluó tono, claridad, precisión del dominio (corrección), robustez, completitud, límites, lenguaje objetivo y seguridad. Además, utilizamos métricas de rendimiento basadas en criterios numéricos como coste, duración de respuesta y número de tokens. Se utilizaron modelos de efectos mixtos para comparar el rendimiento de los LLM y evaluar las interrelaciones de métricas. Resultados Primero, desarrollamos una plataforma web de salud mental utilizando un diseño centrado en el usuario, estructurado en capas frontend, backend y base de datos. El sistema integra chat terapéutico (GPT- 4o y Llama 3.1-8B), evaluaciones psicológicas (PHQ-9, GAD-7), tareas basadas en TCC y un sistema de alerta de emergencia. La plataforma soporta autenticación segura de usuarios, cifrado de datos, acceso multilingüe y seguimiento de sesiones. En segundo lugar, GPT-4o superó a Llama 3.1-8B tanto en métricas de rendimiento basadas en criterios numéricos como en criterios de escala Likert, generando respuestas más largas y léxicamente diversas, usando más tokens y obteniendo puntuaciones más altas en claridad, robustez, completitud, límites y lenguaje objetivo. Sin embargo, tuvo costes más altos, sin diferencias significativas en tono, precisión o seguridad. Conclusión Nuestro estudio presenta un agente conversacional con múltiples funcionalidades y muestra que GPT-4o supera a Llama 3.1-8B en rendimiento, aunque a un coste más alto. Esta plataforma podría utilizarse en futuros ensayos clínicos o estudios de implementación en el mundo real.</div>
  </div>
</li>
<li class="poster-item">
  <button class="poster-toggle" aria-expanded="false" onclick="this.setAttribute('aria-expanded', this.getAttribute('aria-expanded')==='true'?'false':'true'); this.nextElementSibling.classList.toggle('open')">
    <span class="poster-arrow">&#9654;</span>
    <span class="poster-num">12.</span>
    <span><span class="poster-title-text">Evaluación comparativa del rendimiento computacional y la eficiencia energética para Edge AI: Raspberry Pi 5 frente a NVIDIA Jetson Orin Nano en reconocimiento de emociones faciales</span> — <span class="poster-author">Valentina Milagros Chambilla Perca</span></span>
  </button>
  <div class="poster-body">
    <div class="poster-affiliation">Universidad Nacional de San Agustín de Arequipa, Perú</div>
    <div class="poster-abstract">La implementación de modelos de Inteligencia Artificial en dispositivos de borde (Edge AI) permite ejecutar tareas de inferencia localmente, reduciendo la dependencia de servicios en la nube. Sin embargo, seleccionar la plataforma de hardware adecuada requiere evaluar el equilibrio entre rendimiento computacional, consumo energético y recursos disponibles. Este trabajo propone una evaluación comparativa de Raspberry Pi 5 y NVIDIA Jetson Orin Nano para la ejecución de un sistema de reconocimiento de emociones faciales basado en visión por computador. Ambos dispositivos se consideran plataformas de procesamiento para desplegar modelos de inteligencia artificial en entornos con recursos computacionales y energéticos limitados. La comparación se centra en métricas como el tiempo de inferencia, la tasa de procesamiento de imágenes, el uso de CPU y memoria, el consumo energético y la energía requerida por inferencia. Estas métricas permiten analizar las diferencias entre ambas plataformas y comprender cómo sus características de hardware y capacidades de procesamiento influyen en la ejecución de modelos de IA en el borde. El objetivo es identificar las ventajas y limitaciones de cada dispositivo para aplicaciones asistivas portátiles, considerando no solo la velocidad de procesamiento, sino también la eficiencia energética y la viabilidad de su integración en sistemas embebidos. Este estudio busca aportar criterios experimentales para la selección de plataformas Edge AI, contribuyendo al diseño de soluciones inteligentes que equilibren rendimiento, consumo energético y autonomía operativa.</div>
  </div>
</li>
<li class="poster-item">
  <button class="poster-toggle" aria-expanded="false" onclick="this.setAttribute('aria-expanded', this.getAttribute('aria-expanded')==='true'?'false':'true'); this.nextElementSibling.classList.toggle('open')">
    <span class="poster-arrow">&#9654;</span>
    <span class="poster-num">13.</span>
    <span><span class="poster-title-text">Edge AI para el Apoyo a la Segmentación del Abdomen Fetal en Ultrasonido Obstétrico en tiempo real.</span> — <span class="poster-author">Wei-Chung Cheng</span></span>
  </button>
  <div class="poster-body">
    <div class="poster-affiliation">BiomedLab, Universidad Galileo, Guatemala</div>
    <div class="poster-abstract">La evaluación del plano abdominal fetal es un componente fundamental del ultrasonido (US) obstétrico, ya que permite realizar mediciones biométricas esenciales para el seguimiento del crecimiento fetal y facilita la detección temprana de anomalías congénitas (p. ej., gastrosquisis). Sin embargo, este servicio de salud no es de fácil acceso en poblaciones con recursos escasos, por la falta de profesionales con entrenamiento de estudios de US y equipo tecnológico. Este trabajo propone un sistema de segmentación automática del abdomen fetal en imágenes de ultrasonido obstétrico, diseñado para ejecutarse en tiempo real sobre dispositivos con recursos limitados, con el fin de apoyar a proveedores de salud inexperimentados con la adquisición de estudios de US. Se utilizó técnicas de Aprendizaje Profundo para segmentación semántica. Se evaluaron arquitecturas de referencia como U-Net y modelos inspirados en Neural Cellular Automata, optimizados para mantener un equilibrio entre precisión y eficiencia computacional. Los modelos fueron entrenados con imágenes ecográficas anotadas y posteriormente optimizados para inferencia en dispositivos móviles mediante cuantización y poda. Se presentan los resultados comparativos de los modelos evaluados, tanto en el desempeño de segmentación, como la eficiencia computacional, mediante métricas como Dice e IoU; y la latencia y máximo de memoria reservada, respectivamente.</div>
  </div>
</li>
<li class="poster-item">
  <button class="poster-toggle" aria-expanded="false" onclick="this.setAttribute('aria-expanded', this.getAttribute('aria-expanded')==='true'?'false':'true'); this.nextElementSibling.classList.toggle('open')">
    <span class="poster-arrow">&#9654;</span>
    <span class="poster-num">14.</span>
    <span><span class="poster-title-text">Inserción de objetos anómalos en 3DGS para percepción en robótica móvil</span> — <span class="poster-author">Wilbur Naike Chiuyari Veramendi</span></span>
  </button>
  <div class="poster-body">
    <div class="poster-affiliation">Instituto de Ciências Matemáticas e de Computação (ICMC) da Universidade de São Paulo (USP), Brasil</div>
    <div class="poster-abstract">Evaluar la percepción de robots y vehículos autónomos requiere escenas anómalas controlables, que rara vez aparecen en los datos reales. Proponemos un flujo basado en 3D Gaussian Splatting (3DGS), que permite renderizar imagen, profundidad y, con atributos semánticos, segmentación de una misma escena, y que consta de tres etapas: obtener una escena, insertar en ella un objeto anómalo y evaluar la respuesta de los modelos de percepción. Para la primera etapa consideramos dos fuentes: escenas de conducción reales de Waymo reconstruidas con Street Gaussians, y escenas propias capturadas con cámaras RealSense mediante Photo-SLAM, orientadas a un robot móvil. Para la segunda, el objeto se entrena como un 3DGS independiente a partir de imágenes enmascaradas, se escala a dimensiones métricas, se rota (incluidos sus armónicos esféricos), se ubica sobre el terreno y se fusiona con la escena. Presentamos el avance de ambas etapas: la inserción sobre escenas de Waymo, en desarrollo, y un estudio de viabilidad de Photo-SLAM en una NVIDIA Jetson AGX Xavier, donde se procesaron 10–14 de 30 fps, con el tracking limitado por CPU, y se logró un recorrido largo en un solo mapa sin pérdidas de tracking. La tercera etapa evaluará cómo responden modelos de segmentación semántica y de estimación de profundidad a los objetos insertados.</div>
  </div>
</li>
<li class="poster-item">
  <button class="poster-toggle" aria-expanded="false" onclick="this.setAttribute('aria-expanded', this.getAttribute('aria-expanded')==='true'?'false':'true'); this.nextElementSibling.classList.toggle('open')">
    <span class="poster-arrow">&#9654;</span>
    <span class="poster-num">15.</span>
    <span><span class="poster-title-text">Sequías de viento: la presión en superficie no alcanza a explicar las sequías eólicas en Uruguay — la previa a los grafos temporales&quot; Subtítulo: Un caso real de energía renovable que pide Graph Neural Networks</span> — <span class="poster-author">Santiago de Mello</span></span>
  </button>
  <div class="poster-body">
    <div class="poster-affiliation">UTE, Uruguay</div>
    <div class="poster-abstract">1. EL PROBLEMA Uruguay cubre hasta el 100% de su demanda eléctrica con energía eólica. Cuando el viento se detiene durante días, la operación del sistema se vuelve crítica. La pregunta es si se puede anticipar una sequía de viento mirando patrones de presión a nivel del mar (SLP). La respuesta es que sí, pero no alcanza: el patrón de presión no explica por sí solo las sequías. Necesitamos ir más allá, y aquí es donde entran los grafos temporales. 2. LO QUE YA TENEMOS El pipeline actual parte de datos ERA5 de SLP diario (1980–2026), aplica K-means con k=5 para identificar cinco regímenes climáticos recurrentes sobre Sudamérica, calcula el índice SWSI para caracterizar sequías de viento (2018–2026), y luego analiza estadísticamente las diferencias entre días de sequía y días normales mediante test t y chi-cuadrado. Los cinco regímenes identificados son: Régimen 2 (anticiclón sobre el Río de la Plata, 28.1% de los días), Régimen 5 (ciclón al sur de Sudamérica, 25.8%), Régimen 3 (dipolo Atlántico, 17.9%), Régimen 1 (dipolo Pacífico, 14.3%) y Régimen 4 (anticiclón al sur de Sudamérica, 13.9%). Los hallazgos clave son que el Régimen 5 es el más frecuente en días de sequía extrema (SWSI ≤ −2), pero no hay diferencias significativas entre días de sequía y días normales (p &gt; 0.05, test t). Los eventos más extremos (SWSI ≈ −3, junio 2026) se repartieron entre cuatro regímenes distintos. La conclusión parcial es que no existe un único régimen responsable y que la presión en superficie sola no alcanza. 3. EL HALLAZGO PIDE IA Lo que encontramos es que la presión en superficie no explica las sequías de viento. No hay diferencias significativas entre días de sequía y días normales, y los eventos extremos se distribuyen entre varios regímenes. Esto significa que el sistema es más complejo que un simple umbral de presión. Se necesitan modelos que capturen dependencias temporales y multimodales. La estructura de transición entre regímenes ya es un grafo: los regímenes son nodos, las transiciones son aristas con pesos (probabilidades). Aquí es donde entran los grafos temporales. 4. LA PROPUESTA La propuesta es construir un grafo temporal de regímenes climáticos y aplicar Graph Neural Networks para predecir sequías de viento con mayor anticipación. En este grafo, los nodos son los regímenes climáticos, los días, las estaciones y las regiones; las aristas son las transiciones observadas, la similitud sinóptica y las correlaciones; y las features por nodo incluyen anomalías de SLP, viento, temperatura, humedad y persistencia. Los modelos candidatos son GraphSAGE, Graph Attention Networks y grafos temporales como EvolveGCN. Las fases son: construcción del grafo, entrenamiento de la GNN para clasificación de nodos (día con o sin sequía), predicción a 1–7 días, validación contra baseline (K-means más regresión logística) y evaluación con precision, recall, F1 y AUC-ROC. 5. LO QUE YA TENEMOS PARA EMPEZAR Contamos con la serie de SWSI (2018–2026), los cinco regímenes clasificados (1980–2026), la matriz de transición entre regímenes, los composites de anomalías de SLP y la caracterización de sequías en términos de duración, intensidad y severidad. 6. LO QUE BUSCAMOS Este trabajo ya tiene una base sólida: regímenes climáticos identificados, sequías caracterizadas y un hallazgo claro que pide un salto hacia los grafos temporales. Lo que buscamos en esta escuela es conectar con personas que trabajen en Aprendizaje con Grafos, GNN y grafos temporales, para explorar juntos cómo modelar este problema como un grafo temporal multimodal. También nos interesa conectar con gente de Aprendizaje Estadístico, Optimización, IA Confiable y Sociedad, e Interpretabilidad Mecanística, porque el problema toca esos temas. La idea es abrir una línea de colaboración que combine datos del mundo real, energía renovable e IA con grafos. 7. REFERENCIAS PRINCIPALES Andres-Martin et al. (2026). The Standardized Wind Speed Index. Atmospheric Research, 338, 108967. Hersbach et al. (2020). The ERA5 global reanalysis. QJRMS, 146(730), 1999–2049. Lee, Tippett &amp; Polvani (2024). A New Year-Round Weather Regime Classification for North America. J. Climate, 37(1), 39–57. de Mello (2024). Characterization of heat waves in Uruguay. Tesis de maestría, UdelaR–PEDECIBA.</div>
  </div>
</li>
<li class="poster-item">
  <button class="poster-toggle" aria-expanded="false" onclick="this.setAttribute('aria-expanded', this.getAttribute('aria-expanded')==='true'?'false':'true'); this.nextElementSibling.classList.toggle('open')">
    <span class="poster-arrow">&#9654;</span>
    <span class="poster-num">16.</span>
    <span><span class="poster-title-text">Generación determinista de datos mediante mapas dinámicos en espacios latentes de autoencoders</span> — <span class="poster-author">Luciana De Micco</span></span>
  </button>
  <div class="poster-body">
    <div class="poster-affiliation">ICYTE (UNMDP-CONICET), Argentina</div>
    <div class="poster-abstract">Los autoencoders permiten representar datos complejos en espacios de menor dimensión, conocidos como espacios latentes. Estas representaciones pueden utilizarse para generar nuevos datos, aunque para ello es necesario contar con un método que reproduzca adecuadamente su distribución. En este trabajo presentamos un método determinista para generar nuevas muestras a partir del espacio latente de un autoencoder. La propuesta utiliza mapas dinámicos lineales por tramos, construidos a partir de las distribuciones observadas en los datos. Mediante la iteración de estos mapas se obtienen nuevos vectores latentes que pueden ser transformados en datos sintéticos utilizando el decodificador del autoencoder. El procedimiento no requiere incorporar ruido aleatorio ni entrenar una red neuronal adicional. El método se evaluó utilizando datos sintéticos y el conjunto de imágenes MNIST. Los resultados muestran que las muestras generadas conservan las principales características estadísticas de las representaciones originales y permiten obtener imágenes de calidad comparable a las generadas mediante estimación de densidad por kernels (KDE).</div>
  </div>
</li>
<li class="poster-item">
  <button class="poster-toggle" aria-expanded="false" onclick="this.setAttribute('aria-expanded', this.getAttribute('aria-expanded')==='true'?'false':'true'); this.nextElementSibling.classList.toggle('open')">
    <span class="poster-arrow">&#9654;</span>
    <span class="poster-num">17.</span>
    <span><span class="poster-title-text">Desentrelazamiento de la huella individual de los biomarcadores de sueño EEG</span> — <span class="poster-author">Cristina Daiana Duarte</span></span>
  </button>
  <div class="poster-body">
    <div class="poster-affiliation">Instituto de Física del Sur (IFISUR), Universidad Nacional del Sur - CONICET, Argentina</div>
    <div class="poster-abstract">Los registros electroencefalográficos (EEG) contienen información sobre la dinámica neurofisiológica y características individuales de cada sujeto. Esta dualidad representa un desafío para la identificación de biomarcadores, ya que los modelos de aprendizaje automático pueden aprovechar patrones asociados a la identidad individual en lugar de señales fisiológicamente relevantes. En este trabajo se evaluó si los patrones ordinales ponderados generalizados (GWOP), una representación de complejidad estadística que integra información temporal y variaciones de amplitud, permiten clasificar etapas del sueño reduciendo la influencia del sujeto. Se analizaron registros EEG de sueño de 31 sujetos sanos, segmentados en épocas de 30 segundos y representados mediante 3150 características GWOP. La clasificación se realizó con XGBoost utilizando validaciones intra e intersujeto, junto con un análisis de identificación individual. Los resultados mostraron una buena generalización a sujetos no vistos, con una reducción de precisión del 79,2% al 75,8%. El análisis SHAP mostró una alta similitud entre validaciones (ρ de Spearman = 0,998), sugiriendo baja dependencia de información específica del sujeto. Además, GWOP permitió identificar individuos con 63,9% de precisión, evidenciando la preservación de información biométrica EEG. Estos resultados sugieren que la identificación individual y la extracción de biomarcadores pueden coexistir en el análisis EEG.</div>
  </div>
</li>
<li class="poster-item">
  <button class="poster-toggle" aria-expanded="false" onclick="this.setAttribute('aria-expanded', this.getAttribute('aria-expanded')==='true'?'false':'true'); this.nextElementSibling.classList.toggle('open')">
    <span class="poster-arrow">&#9654;</span>
    <span class="poster-num">18.</span>
    <span><span class="poster-title-text">Aproximación de equilibrios de Nash y matrices aleatorias</span> — <span class="poster-author">Mariano Fernández Zaragoza</span></span>
  </button>
  <div class="poster-body">
    <div class="poster-affiliation">FCEN-UBA Departamento de Matemática, Argentina</div>
    <div class="poster-abstract">¿Qué hacemos cuando debemos jugar un juego grande, rápido y repetidas veces? ¿Cómo evaluamos qué tan bien jugamos? ¿Cómo impacta en nuestra decisión la distribución en la que aprendemos a jugar? Retomamos resultados de trabajos anteriores de nuestro grupoa para ver si un modelo de red neuronal converge a los resultados esperados y aprende a jugar juegos aleatorios como predice la teoría.</div>
  </div>
</li>
<li class="poster-item">
  <button class="poster-toggle" aria-expanded="false" onclick="this.setAttribute('aria-expanded', this.getAttribute('aria-expanded')==='true'?'false':'true'); this.nextElementSibling.classList.toggle('open')">
    <span class="poster-arrow">&#9654;</span>
    <span class="poster-num">19.</span>
    <span><span class="poster-title-text">Aprendizaje Profundo para la predicción de núcleos voxelizados de dosis: comparación de arquitecturas convolucionales y basadas en transformers</span> — <span class="poster-author">Santiago Agustín Ferreyra</span></span>
  </button>
  <div class="poster-body">
    <div class="poster-affiliation">FAMAF - UNC, Argentina</div>
    <div class="poster-abstract">La dosimetría interna personalizada en terapia con $^{177}$Lu-PSMA requiere estimar la distribución espacial de dosis absorbida en tejidos heterogéneos. Las simulaciones Monte Carlo (MC) son el estándar de referencia, pero su costo computacional impide el uso clínico rutinario, y los métodos de convolución con Núcleos Voxelizados de Dosis (VDK, *Voxel Dose Kernels*) pierden precisión ante variaciones de densidad y composición. Este trabajo plantea la predicción de VDKs como un problema de regresión volumétrica 3D: dado un *patch* de CT, una red neuronal debe estimar el kernel de dosis correspondiente, reemplazando una simulación MC completa por una única inferencia. Se generó un conjunto de datos de 10.000 pares (*patch* de CT, kernel de dosis) de $31 \times 31 \times 31$ vóxeles (1 mm isotrópico), simulados con FLUKA sobre CT de pacientes reales. Se compararon cuatro arquitecturas: una red convolucional con *Atrous Spatial Pyramid Pooling* (DATROUS4), una U- Net con bloques residuales profundos (DRESUnet) y dos variantes de UNETR (*UNet TRansformers*) de capacidad creciente. El entrenamiento usó validación cruzada de 5 *folds* sobre 9.500 muestras, pérdida MAE y optimizador AdamW. La evaluación se realizó sobre 500 *patches* de test fijo con MAE (mGy/MBq), RMSE, NRMSE y VRAE (*Voxel Relative Absolute Error*), métricas complementarias que capturan tanto el error absoluto como el relativo por vóxel. Las arquitecturas basadas en *transformers* obtuvieron el mejor desempeño: UNETR-Base alcanzó un $\text{MAE} = 5.03 \times 10^{-4}$ mGy/MBq y un $\text{VRAE} = 3.48 \pm 6.35\,\%$, seguida de UNETR-Light con resultados prácticamente equivalentes ($\text{MAE} = 5.08 \times 10^{-4}$ mGy/MBq, $\text{VRAE} = 3.59 \pm 6.35\,\%$). Los errores respecto a la referencia MC se ubicaron entre el $3\,\%$ y el $10\,\%$ según la arquitectura. Los modelos con mecanismos de atención superaron a las redes convolucionales, lo que sugiere que el modelado de dependencias de largo alcance es relevante para capturar el transporte de radiación en medios heterogéneos. Además, al no depender del tamaño de entrada, permiten extender la inferencia a volúmenes completos mediante ventana deslizante. Como trabajo futuro, los kernels predichos se integrarán en un esquema de dosis por convolución y se validarán contra simulaciones MC independientes (OpenGate) sobre distribuciones de actividad SPECT reales.</div>
  </div>
</li>
<li class="poster-item">
  <button class="poster-toggle" aria-expanded="false" onclick="this.setAttribute('aria-expanded', this.getAttribute('aria-expanded')==='true'?'false':'true'); this.nextElementSibling.classList.toggle('open')">
    <span class="poster-arrow">&#9654;</span>
    <span class="poster-num">20.</span>
    <span><span class="poster-title-text">Formalizando la capacidad de contextualización de los Transformers</span> — <span class="poster-author">Demián Fraiman</span></span>
  </button>
  <div class="poster-body">
    <div class="poster-affiliation">Universidad de Buenos Aires, Argentina</div>
    <div class="poster-abstract">La arquitectura Transformer desencadenó una revolución en el procesamiento del lenguaje natural. A diferencia de sus predecesoras, como las redes neuronales recurrentes (RNN), incorpora un mecanismo de atención que permite modelar explícitamente las relaciones contextuales. En este trabajo, utilizando herramientas de transporte óptimo, desarrollamos un marco teórico para analizar la capacidad de los Transformers para aprender relaciones contextuales y caracterizar su poder expresivo.</div>
  </div>
</li>
<li class="poster-item">
  <button class="poster-toggle" aria-expanded="false" onclick="this.setAttribute('aria-expanded', this.getAttribute('aria-expanded')==='true'?'false':'true'); this.nextElementSibling.classList.toggle('open')">
    <span class="poster-arrow">&#9654;</span>
    <span class="poster-num">21.</span>
    <span><span class="poster-title-text">Transformers Global-Local 2.5D con Ponderación de Probabilidad Inversa Continua para la Estimación de Edad Cerebral</span> — <span class="poster-author">Nicolás Fuentes</span></span>
  </button>
  <div class="poster-body">
    <div class="poster-affiliation">Instituto de Tecnologías Nucleares para la Salud | Instituto Balseiro | Comisión Nacional de Energía Atómica (CNEA), Argentina</div>
    <div class="poster-abstract">En resonancia magnética estructural ponderada en T1, la estimación de la brecha de edad cerebral (BAG, del inglés Brain Age Gap), definida como la diferencia entre la edad predicha por el modelo y la edad cronológica (BAG = ŷ - y), cuantifica las desviaciones individuales respecto a las trayectorias neuroanatómicas normativas. Sin embargo, las predicciones suelen verse afectadas por la regresión a la media y por sesgos dependientes de la edad, especialmente cuando los conjuntos de entrenamiento presentan una distribución demográfica marcadamente heterogénea o desbalanceada a lo largo de todo el rango etario. En este trabajo, implementamos una arquitectura Transformer Global-Local 2.5D combinada con ponderación de probabilidad inversa continua basada en estimación de densidad de kernel (KDE-IPW). El modelo entrena tres redes neuronales (una por plano: axial, coronal y sagital) que procesan cinco cortes contiguos integrando el contexto estructural global con características locales detalladas mediante atención cruzada, y ensambla sus predicciones mediante regresión Ridge asignando un peso distinto a cada plano en la estimación final. Como complemento a los ajustes residuales post-hoc convencionales, KDE-IPW pondera la función de pérdida durante el entrenamiento de manera inversamente proporcional a la densidad empírica de edad. Esta estrategia equilibra los gradientes en los intervalos etarios subrepresentados, mejorando la sensibilidad en los extremos de la distribución y aportando una herramienta útil cuando los datos de entrenamiento están demográficamente desbalanceados. En una cohorte de derivación de 7.453 adquisiciones normativas, el ensamble alcanzó un MAE en validación interna de 2,58 años (r = 0,987, R² = 0,974, error absoluto mediano de 1,81 años). En la validación externa en OASIS-3 (n = 813), la incorporación de KDE-IPW redujo la pendiente del sesgo de edad en un 38,2% (de β₁ = -0,110 a -0,068, p = 0,002) y disminuyó la heterocedasticidad residual en un 18,4% (Breusch–Pagan LM = 49,69, p &lt; 0,001). En RRIB (n = 158), la validación externa alcanzó un MAE de 3,89 años (r = 0,961, R² = 0,922). El esquema propuesto demuestra que integrar representaciones Transformer Global-Local 2.5D con ponderación por densidad complementa el control de sesgos demográficos directamente durante la etapa de aprendizaje, preservando la precisión predictiva en cohortes externas.</div>
  </div>
</li>
<li class="poster-item">
  <button class="poster-toggle" aria-expanded="false" onclick="this.setAttribute('aria-expanded', this.getAttribute('aria-expanded')==='true'?'false':'true'); this.nextElementSibling.classList.toggle('open')">
    <span class="poster-arrow">&#9654;</span>
    <span class="poster-num">22.</span>
    <span><span class="poster-title-text">Especialización de modelos de lenguaje pequeños mediante LoRA y GRPO para la generación de SQL geoespacial sobre incidentes delictivos</span> — <span class="poster-author">Jeanpier Miguel Garay Pastrana</span></span>
  </button>
  <div class="poster-body">
    <div class="poster-affiliation">UTEC, Perú</div>
    <div class="poster-abstract">El análisis de incidentes delictivos georreferenciados requiere consultas que combinan filtros temporales, relaciones entre tablas y operaciones espaciales, como proximidad, contención e intersección. Esta complejidad dificulta el acceso a la información por parte de usuarios sin conocimientos de SQL o sistemas de información geográfica. Esta investigación desarrolla y evalúa un sistema Text-to-SQL geoespacial basado en un modelo de lenguaje pequeño, especializado mediante LoRA y aprendizaje por refuerzo con el algoritmo GRPO. El sistema transforma preguntas en español, acompañadas opcionalmente de figuras seleccionadas en un mapa, en consultas ejecutables sobre PostgreSQL y PostGIS. Para ello, se construye un conjunto de datos con diversidad lingüística, distintos niveles de dificultad y consultas orientadas tanto a la visualización cartográfica como al análisis estadístico. El entrenamiento utiliza recompensas verificables basadas en la validez sintáctica y la equivalencia de los resultados obtenidos al ejecutar las consultas. Además, se estudia una recompensa parcial que considera la correspondencia de componentes y operadores SQL con los requisitos de la consulta, buscando proporcionar señales de aprendizaje más informativas. La evaluación distingue consultas visuales y analíticas, aplica criterios estrictos y flexibles de equivalencia y compara distintas configuraciones de entrenamiento. Finalmente, el modelo se integra en una interfaz local que permite formular preguntas, seleccionar múltiples figuras y visualizar los resultados. El trabajo busca aportar una metodología reproducible para especializar modelos pequeños en consultas geoespaciales y facilitar el acceso a estos datos sin depender de servicios externos durante la inferencia.</div>
  </div>
</li>
<li class="poster-item">
  <button class="poster-toggle" aria-expanded="false" onclick="this.setAttribute('aria-expanded', this.getAttribute('aria-expanded')==='true'?'false':'true'); this.nextElementSibling.classList.toggle('open')">
    <span class="poster-arrow">&#9654;</span>
    <span class="poster-num">23.</span>
    <span><span class="poster-title-text">Modelo interactivo de aprendizaje profundo para la restauración cromática de obras de arte</span> — <span class="poster-author">Rosana Garcia Collares</span></span>
  </button>
  <div class="poster-body">
    <div class="poster-affiliation">Universidad de la República, Uruguay</div>
    <div class="poster-abstract">Este trabajo aborda el desafío de restaurar digitalmente la apariencia cromática de imágenes de las obras del artista uruguayo Joaquín Torres García perdidas en el incendio del Museo de Arte Moderno de Río de Janeiro en 1978. Basándose en documentación monocromática heterogénea, el trabajo evalúa las limitaciones de los métodos de colorización totalmente automáticos y utiliza un enfoque híbrido con intervención humana-experta basado en la arquitectura iColoriT. Para adaptar el modelo al dominio del artista, se construyeron conjuntos de datos con diversas características, que abarcan desde un núcleo curado por expertos a partir de obras de Torres García hasta un corpus más amplio que integra diversas fuentes de archivo. Se implementó una estrategia de ajuste fino mediante Adaptación de Bajo Rango (LoRA) para optimizar el Vision Transformer (iColorit), capturando la paleta del artista y preservando las capacidades interactivas del modelo. Los resultados experimentales demuestran que los modelos adaptados con LoRA superan consistentemente al modelo base de iColoriT tanto en métricas cuantitativas (PSNR, LPIPS) como en la fidelidad cualitativa, especialmente en escenarios con escasa guía del usuario. Por último, para los curadores, este trabajo adapta una herramienta de software interactiva que permite a los usuarios tomar muestras de color de imágenes de referencia cromáticas y condicionadas por la luminancia. Esto garantiza restauraciones históricamente y estilísticamente plausibles</div>
  </div>
</li>
<li class="poster-item">
  <button class="poster-toggle" aria-expanded="false" onclick="this.setAttribute('aria-expanded', this.getAttribute('aria-expanded')==='true'?'false':'true'); this.nextElementSibling.classList.toggle('open')">
    <span class="poster-arrow">&#9654;</span>
    <span class="poster-num">24.</span>
    <span><span class="poster-title-text">Logs como lenguaje: una exploración de la fricción silenciosa en servicios digitales</span> — <span class="poster-author">Edgar Sneyder Garcia Morantes</span></span>
  </button>
  <div class="poster-body">
    <div class="poster-affiliation">Nequi, Colombia</div>
    <div class="poster-abstract">Los sistemas digitales registran la interacción de los usuarios como secuencias de eventos (logs), una fuente abundante cuyo potencial para comprender la experiencia de servicio permanece subexplotado. Este trabajo explora un marco que representa la trayectoria de cada usuario como un documento textual y la codifica mediante TF-IDF con n-gramas, lo que permite capturar tanto la frecuencia de las acciones como sus transiciones locales. Sobre esta representación, un agrupamiento no supervisado permite identificar perfiles de comportamiento interpretables que sugieren modos diferenciados de fricción. Su coherencia se contrasta con la evidencia textual expresada por los propios usuarios. El marco se aplicó de forma exploratoria a los registros de una plataforma de servicios digitales de alto volumen en Colombia. Los resultados preliminares indican que el reclamo explícito sería un indicador incompleto de la fricción subyacente, pues una proporción relevante de usuarios con patrones de fricción desiste sin reportarla. Esto apunta a una fricción silenciosa que los canales tradicionales de retroalimentación no capturan. Se trata de una aproximación interpretable y de bajo costo, que no requiere etiquetado extensivo ni modelos secuenciales complejos. Como trabajo futuro se plantea evaluar su capacidad de anticipación temporal y su transferencia a otros dominios.</div>
  </div>
</li>
<li class="poster-item">
  <button class="poster-toggle" aria-expanded="false" onclick="this.setAttribute('aria-expanded', this.getAttribute('aria-expanded')==='true'?'false':'true'); this.nextElementSibling.classList.toggle('open')">
    <span class="poster-arrow">&#9654;</span>
    <span class="poster-num">25.</span>
    <span><span class="poster-title-text">Comparación de métodos para eliminar artefactos musculares asociados a la masticación en señales de EEG</span> — <span class="poster-author">Daniela Belén Garrido González</span></span>
  </button>
  <div class="poster-body">
    <div class="poster-affiliation">Universidad técnica Federico Santa María, Chile</div>
    <div class="poster-abstract">La masticación puede contaminar las señales de EEG con actividad muscular y afectar la interpretación de los resultados. En este estudio se compararon cuatro métodos de limpieza: ASR, filtrado adaptativo por bloques, CCA con rezagos e iCanClean, utilizando referencias EMG de los músculos maseteros cuando correspondía. Se analizaron cinco participantes y se evaluaron la reducción de amplitud y potencia durante la masticación, junto con la similitud y modificación de la señal durante el reposo. La selección de configuraciones se realizó sin utilizar los datos del participante evaluado. Con los criterios definidos, iCanClean no superó de manera consistente a ASR, al filtrado adaptativo ni a la CCA. Aunque redujo la amplitud durante la masticación en una magnitud comparable a otros métodos, también modificó la señal durante el reposo. Por lo tanto, los resultados no respaldan la hipótesis de que iCanClean atenúe mejor los artefactos de masticación y preserve mejor la actividad cerebral. La interpretación está limitada por el reducido número de participantes, el uso exclusivo de referencias de los maseteros y la ausencia de una referencia cerebral independiente.</div>
  </div>
</li>
<li class="poster-item">
  <button class="poster-toggle" aria-expanded="false" onclick="this.setAttribute('aria-expanded', this.getAttribute('aria-expanded')==='true'?'false':'true'); this.nextElementSibling.classList.toggle('open')">
    <span class="poster-arrow">&#9654;</span>
    <span class="poster-num">26.</span>
    <span><span class="poster-title-text">Segmentación Automática Basada en Aprendizaje Profundo de Lesiones PSMA-Ávidas en estudios</span> — <span class="poster-author">PET/CT con 18F-PSMA</span></span>
  </button>
  <div class="poster-body">
    <div class="poster-affiliation">Julián Franco Gelabert FUESMEN, Argentina</div>
    <div class="poster-abstract">Introducción: La identificación y delineación manual de lesiones hipercaptantes de 18F-PSMA en estudios PET/CT es un proceso que demanda tiempo y presenta variabilidad intra e interobservador. El objetivo de este trabajo fue desarrollar, evaluar y validar un segmentador automático de lesiones PSMA-ávidas basado en redes neuronales convolucionales (CNN). Desarrollo: Una CNN U-Net 3D altamente asimétrica fue entrenada con un dataset de estudios PET/CT de cuerpo entero (369 con 18F-PSMA y 228 con 68Ga-PSMA) segmentados de forma manual por expertos. Se realizó una validación externa sobre un conjunto de 98 estudios institucionales los cuales fueron a su vez delineados por médicos nucleares. Resultados: La CNN alcanzó una sensibilidad del 64% para lesiones con diámetros menores a 5 mm y superior al 81% para lesiones de mayor diámetro. La tasa de falsos positivos lesionales por paciente fue de 0.43 focos espurio. La red se mostró conservadora al contornear, con una tendencia a subestimar el volumen tumoral. La CNN aprendió a identificar la captación patológica del PSMA en variedad de estructuras. Conclusiones: Nuestra CNN se posiciona como una herramienta sólida y altamente específica para la delimitación automática de lesiones PSMA-ávida en estudios PET/CT con 18F-PSMA. Su alta sensibilidad, precisión y bajo perfil de FP resultan clínicamente valiosos. La validación externa abre las puertas a un re-entrenamiento con pacientes institucionales, así como una incorporación al flujo de trabajo clínico, mejorando la calidad de los informes médicos del servicio PET de FUESMEN.</div>
  </div>
</li>
<li class="poster-item">
  <button class="poster-toggle" aria-expanded="false" onclick="this.setAttribute('aria-expanded', this.getAttribute('aria-expanded')==='true'?'false':'true'); this.nextElementSibling.classList.toggle('open')">
    <span class="poster-arrow">&#9654;</span>
    <span class="poster-num">27.</span>
    <span><span class="poster-title-text">Aprendizaje de estructura y robustez direccional en redes bayesianas aplicado a series de tiempo macroeconómicas</span> — <span class="poster-author">Daniela Agostina Gonzalez</span></span>
  </button>
  <div class="poster-body">
    <div class="poster-affiliation">CONICET - Universidad Nacional de Córdoba, Argentina</div>
    <div class="poster-abstract">Problema: Dado un conjunto de series de tiempo macroeconómicas, ¿qué relaciones de dependencia existen entre ellas y en qué dirección? El aprendizaje de estructura de redes bayesianas (structure learning) permite inferir un DAG a partir de datos, pero enfrenta dos dificultades en este dominio: la dependencia temporal de las observaciones y la no-identificabilidad de la orientación de los arcos entre variables contemporáneas (estructuras dentro de una misma clase de equivalencia de Markov son indistinguibles a partir de datos observacionales). Proponemos un procedimiento en dos etapas: (i) un algoritmo que selecciona, para cada variable, sus rezagos relevantes dentro de un conjunto candidato, y (ii) el aprendizaje conjunto de la estructura con restricciones temporales (blacklist de arcos hacia el pasado). Para abordar la no-identificabilidad direccional, introducimos la Combined Directional Arc Strength (CDAS), una medida basada en un diseño pareado de block-bootstrap que preserva la dependencia temporal y cuantifica la robustez de la orientación de cada arco bajo configuraciones con y sin restricciones. La comparación entre modelos emplea métricas ordinales de predicción out-of-sample (RPS, error ordinal, adjacent accuracy), independientes de la cardinalidad del modelo. Validación y resultados: aplicamos el método a cuatro especificaciones teóricas de la inflación argentina, contrastando cada grafo teórico con la estructura aprendida. La CDAS distingue de forma consistente los arcos robustos de los no identificados: relaciones intra-temporales mantienen orientaciones estables (CDAS &gt; 0.94) aun sin imponerse por precedencia temporal, mientras que el vínculo dinero-inflación resulta direccionalmente frágil. Los modelos convergen a la misma estructura local predictiva con independencia de su conjunto de variables, y los resultados coinciden con los de métodos econométricos tradicionales (VEC, FAVAR). El marco combina selección de rezagos, structure learning con restricciones temporales y una medida de robustez direccional, ofreciendo una alternativa a los métodos que imponen la estructura causal a priori (p. ej. ordenamientos de Cholesky en VAR). La convergencia con enfoques econométricos establecidos respalda su validez como herramienta de inferencia causal en series de tiempo.</div>
  </div>
</li>
<li class="poster-item">
  <button class="poster-toggle" aria-expanded="false" onclick="this.setAttribute('aria-expanded', this.getAttribute('aria-expanded')==='true'?'false':'true'); this.nextElementSibling.classList.toggle('open')">
    <span class="poster-arrow">&#9654;</span>
    <span class="poster-num">28.</span>
    <span><span class="poster-title-text">DEI en IA para Latinoamérica: No es solo Ética, es Economía.</span> — <span class="poster-author">Claudia Andrea González Inostroza</span></span>
  </button>
  <div class="poster-body">
    <div class="poster-affiliation">Pontificia Universidad Católica de Chile - CENIA</div>
    <div class="poster-abstract">La incorporación de diversidad, equidad e inclusión (DEI) en IA no es solo una exigencia ética, sino una necesidad económica y estratégica para LATAM. Sistemas entrenados con datos ajenos a la región pueden reproducir desigualdades, fallar técnicamente y aumentar riesgos legales. El mercado de IA en LATAM se estima en USD 5.79 mil millones en 2025, creciendo a USD 30.2 mil millones en 2033 (22% anual), pero la región recibe solo 1.12% de la inversión global en IA pese a representar 6.6% del PIB mundial y 8.8% de la población. El sesgo algorítmico tiene costos concretos: 36% de empresas reportó pérdidas por sesgo, con impactos en clientes, empleados, ingresos y gastos legales. Casos como SafeRent (USD 2.275 millones) y las multas del EU AI Act (hasta €35 millones o 7% de ingresos globales) muestran el riesgo regulatorio. A la vez, DEI genera valor: empresas con mayor diversidad de género tienen 39% más probabilidad de mejor rentabilidad; en LATAM, 93% más probabilidad de desempeño financiero superior y 152% más probabilidad de innovar. El 90% de profesionales TI valora la ética en IA al elegir servicios. La pregunta clave no es solo si la IA funciona, sino para quién, quién controla sus datos y quién asume costos y beneficios. DEI debe pasar del discurso a un sistema de gestión que mida sesgos, audite decisiones y repare impactos.</div>
  </div>
</li>
<li class="poster-item">
  <button class="poster-toggle" aria-expanded="false" onclick="this.setAttribute('aria-expanded', this.getAttribute('aria-expanded')==='true'?'false':'true'); this.nextElementSibling.classList.toggle('open')">
    <span class="poster-arrow">&#9654;</span>
    <span class="poster-num">29.</span>
    <span><span class="poster-title-text">Redes inalámbricas definidas por software conscientes del contexto: Un enfoque basado en IA para gestionar la QoS</span> — <span class="poster-author">Dainier González Romero</span></span>
  </button>
  <div class="poster-body">
    <div class="poster-affiliation">Departamento de Ingeniería Eléctrica y de Computadoras. Instituto de Ciencias e Ingeniería de la Computación. Universidad Nacional del Sur, Argentina</div>
    <div class="poster-abstract">Las aplicaciones IoT con requisitos de tiempo real demandan mecanismos de comunicación capaces de garantizar niveles adecuados de Calidad de Servicio (QoS) en entornos inalámbricos dinámicos. Aunque las Software-Defined Wireless Networks (SDWN) ofrecen flexibilidad para gestionar recursos de red, su capacidad de adaptación ante cambios en las condiciones operativas sigue siendo limitada. Este trabajo presenta un modelo de Context-Aware Software-Defined Wireless Network (CA-SDWN) que incorpora inteligencia artificial en el bucle de control de la red para ajustar dinámicamente los parámetros del protocolo de acceso al medio. La propuesta utiliza información contextual para adaptar el comportamiento de la red según las necesidades de tráfico de las aplicaciones IoT. La solución fue implementada y evaluada mediante el simulador NS-3, desarrollándose además una biblioteca de código abierto para facilitar su reutilización. Los experimentos realizados en escenarios dinámicos muestran que el uso de un agente inteligente mejora la adaptación de la red y la predictibilidad de los parámetros de acceso al medio, permitiendo gestionar de manera eficiente diferentes niveles de QoS. Los resultados evidencian que la integración de inteligencia artificial y conciencia de contexto mejora el desempeño de las SDWN basadas en WiFi para aplicaciones IoT con restricciones temporales y requerimientos cambiantes de comunicación.</div>
  </div>
</li>
<li class="poster-item">
  <button class="poster-toggle" aria-expanded="false" onclick="this.setAttribute('aria-expanded', this.getAttribute('aria-expanded')==='true'?'false':'true'); this.nextElementSibling.classList.toggle('open')">
    <span class="poster-arrow">&#9654;</span>
    <span class="poster-num">30.</span>
    <span><span class="poster-title-text">Aprendizaje activo para la clasificación de eventos sonoros mediante representaciones profundas compactas y estrategias de muestreo no redundantes con etiquetas limitadas</span> — <span class="poster-author">Liz Maribel Huancapaza Hilasaca</span></span>
  </button>
  <div class="poster-body">
    <div class="poster-affiliation">Universidad de Sao Paulo y Universidad Nacional de Juliaca, Perú</div>
    <div class="poster-abstract">El Monitoreo Acústico Pasivo (PAM) permite recopilar grandes volúmenes de grabaciones ambientales, pero su etiquetado manual representa un desafío debido al tiempo y conocimiento especializado que requiere. Este trabajo presenta una estrategia de aprendizaje activo denominada CLLL, diseñada para reducir el esfuerzo de anotación mediante la selección de muestras informativas y estructuralmente no redundantes. Se utilizaron siete conjuntos de datos ecoacústicos de aves, anfibios e insectos, representados mediante embeddings profundos de 128 dimensiones obtenidos a partir de once arquitecturas neuronales. La metodología incorpora una inicialización estructurada mediante agrupamiento y un criterio híbrido de selección que combina incertidumbre predictiva (Least Confidence) con medidas de similitud local de primer y segundo orden, calculadas mediante vecinos más cercanos. Durante diez iteraciones de aprendizaje activo, las muestras seleccionadas se incorporaron progresivamente al entrenamiento de un clasificador Random Forest. Se realizaron veinte repeticiones experimentales y se comparó CLLL con estrategias convencionales de selección. Los resultados evidenciaron un desempeño superior al de las estrategias de referencia en los escenarios evaluados, alcanzando resultados comparables al aprendizaje completamente supervisado con menos del 4 % de los datos de entrenamiento etiquetados.</div>
  </div>
</li>
<li class="poster-item">
  <button class="poster-toggle" aria-expanded="false" onclick="this.setAttribute('aria-expanded', this.getAttribute('aria-expanded')==='true'?'false':'true'); this.nextElementSibling.classList.toggle('open')">
    <span class="poster-arrow">&#9654;</span>
    <span class="poster-num">31.</span>
    <span><span class="poster-title-text">Controladores neuronales robustos basados en la física para redes de distribución activas a gran escala</span> — <span class="poster-author">Miguel Angel Huerta Quian</span></span>
  </button>
  <div class="poster-body">
    <div class="poster-affiliation">Universidad Técnica Federico Santa María, Chile</div>
    <div class="poster-abstract">Las redes eléctricas modernas se caracterizan cada vez más por una elevada penetración de la generación distribuida (DG) y de los recursos renovables, lo que introduce variabilidad e incertidumbre que suponen un reto para la estabilidad y la eficiencia en tiempo real. Las estrategias de control existentes, basadas en la optimización centralizada o distribuida, a menudo se enfrentan a limitaciones computacionales o requieren un conocimiento completo del sistema. Este trabajo propone un controlador de red neuronal basada en la física (PINN) que integra la física del sistema en un agente inteligente, generando políticas operativas interpretables para la DG local y transfiriendo de forma coherente los puntos de consigna globales a acciones de control locales. El enfoque se evalúa en los sistemas IEEE de 4, 34 y 123 buses, incluyendo el funcionamiento fuera de la muestra durante varios días. Los resultados muestran que, en comparación con los métodos más avanzados, el método propuesto logra menores violaciones de tensión y menores costes operativos, un despacho más suave de la potencia activa y reactiva, y un rendimiento robusto y físicamente coherente en condiciones de incertidumbre.</div>
  </div>
</li>
<li class="poster-item">
  <button class="poster-toggle" aria-expanded="false" onclick="this.setAttribute('aria-expanded', this.getAttribute('aria-expanded')==='true'?'false':'true'); this.nextElementSibling.classList.toggle('open')">
    <span class="poster-arrow">&#9654;</span>
    <span class="poster-num">32.</span>
    <span><span class="poster-title-text">Estabilidad dinámica y regulación bioinspirada en redes neuronales desenrolladas para la reconstrucción de resonancia magnética cerebral</span> — <span class="poster-author">Renzo Abel Loayza Carrasco</span></span>
  </button>
  <div class="poster-body">
    <div class="poster-affiliation">Prestamype, Perú</div>
    <div class="poster-abstract">Esta investigación propone analizar la estabilidad dinámica de redes neuronales desenrolladas (Unrolled Neural Networks) aplicadas a la reconstrucción de imágenes de resonancia magnética cerebral multibobina, modelando sus iteraciones como sistemas dinámicos discretos. Desde la perspectiva de la dinámica no lineal, se plantea estudiar la influencia de distintos hiperparámetros sobre el comportamiento de estas arquitecturas. Se distinguirá la estabilidad del entrenamiento, mediante el análisis de la evolución de la función de pérdida, de la estabilidad del proceso iterativo de reconstrucción, mediante el estudio de Jacobianos y la propagación de perturbaciones. Como aporte diferenciador, se propone explorar mecanismos de regulación adaptativa inspirados en la homeostasis neuronal, principio biológico mediante el cual las neuronas regulan su actividad dentro de rangos funcionales. Se investigará si la incorporación de mecanismos de autorregulación en las actualizaciones aprendidas permite mejorar la estabilidad dinámica y la robustez de las reconstrucciones frente a perturbaciones, en comparación con arquitecturas convencionales y estrategias adaptativas de referencia. La evaluación experimental se plantea utilizando el conjunto de datos fastMRI de resonancia magnética cerebral multibobina, considerando diferentes condiciones de submuestreo y métricas de calidad de reconstrucción como PSNR y SSIM, además de indicadores de estabilidad dinámica y sensibilidad a perturbaciones. Se espera que esta investigación contribuya a comprender la relación entre estabilidad, aprendizaje profundo y regulación bioinspirada, explorando cómo principios de la neurociencia computacional pueden orientar el desarrollo de arquitecturas neuronales más robustas para la resolución de problemas inversos en neuroimagen.</div>
  </div>
</li>
<li class="poster-item">
  <button class="poster-toggle" aria-expanded="false" onclick="this.setAttribute('aria-expanded', this.getAttribute('aria-expanded')==='true'?'false':'true'); this.nextElementSibling.classList.toggle('open')">
    <span class="poster-arrow">&#9654;</span>
    <span class="poster-num">33.</span>
    <span><span class="poster-title-text">Campo del Capital Espacial</span> — <span class="poster-author">Abril Margonari</span></span>
  </button>
  <div class="poster-body">
    <div class="poster-affiliation">CONICET-UNC, Argentina</div>
    <div class="poster-abstract">El campo del capital espacial es una magnitud global y dinámica que representa la acumulación y distribución del capital fijo en el entorno construido, emergiendo de la interacción espacio-temporal entre su materialidad y su valorización. Este campo no es estático: fluctúa y se modifica continuamente, y sus variaciones pueden rastrearse a través de categorías como magnitud, temporalidad, valor, tipología, localización, uso y morfología. Mi tesis doctoral propone un modelo territorial probabilístico basado en GeoAI, software libre y datos abiertos (Python, scikit-learn, GeoPandas, Google Buildings V3) para simular los estados de este sistema a través del tiempo y comprender las dinámicas de creación y destrucción del capital espacial en contextos latinoamericanos, donde estas representaciones raramente integran la práctica del planeamiento regional. La Escuela de Primavera en Deep Learning representa la oportunidad de incorporar técnicas como CNN, mecanismos de atención y autoencoders para escalar el modelo hacia representaciones más ricas, alineadas con la frontera de los World Models y la inteligencia espacial.</div>
  </div>
</li>
<li class="poster-item">
  <button class="poster-toggle" aria-expanded="false" onclick="this.setAttribute('aria-expanded', this.getAttribute('aria-expanded')==='true'?'false':'true'); this.nextElementSibling.classList.toggle('open')">
    <span class="poster-arrow">&#9654;</span>
    <span class="poster-num">34.</span>
    <span><span class="poster-title-text">Análisis de Sensibilidad de Evaluation Awareness en Grandes Modelos de Lenguaje</span> — <span class="poster-author">María Marino</span></span>
  </button>
  <div class="poster-body">
    <div class="poster-affiliation">UBA, Argentina</div>
    <div class="poster-abstract">¿Qué pistas usa un modelo para reconocer que está siendo evaluado? Usando linear probes sobre activaciones de ocho modelos open-weights (0.5B a 72B parámetros), encontramos que el conflicto ético es la dimensión que más correlaciona con la representación de evaluation awareness.</div>
  </div>
</li>
<li class="poster-item">
  <button class="poster-toggle" aria-expanded="false" onclick="this.setAttribute('aria-expanded', this.getAttribute('aria-expanded')==='true'?'false':'true'); this.nextElementSibling.classList.toggle('open')">
    <span class="poster-arrow">&#9654;</span>
    <span class="poster-num">35.</span>
    <span><span class="poster-title-text">Evaluación de la eficiencia de inferencia en modelos de lenguaje grandes: comparación entre PyTorch y ONNX Alfredo Enrique Mercado Rios</span> — <span class="poster-author">Tecnológico de Costa Rica</span></span>
  </button>
  <div class="poster-body">
    <div class="poster-abstract">Los modelos de lenguaje de gran tamaño (LLMs) requieren importantes recursos computacionales durante su inferencia, lo que motiva la búsqueda de estrategias para mejorar su eficiencia. Este trabajo presenta una evaluación experimental del rendimiento de tres modelos de lenguaje: Gemma- 7B, Phi-3-Medium y Llama-3.1-8B, comparando su ejecución en PyTorch y ONNX Runtime. Los experimentos se realizaron utilizando una GPU NVIDIA L40S del clúster de supercomputación Kabré, manteniendo una precisión FP16. Mediante NVIDIA Nsight Compute se analizaron métricas como el tiempo de inferencia, el rendimiento computacional (GFLOP/s) y la intensidad aritmética, complementadas con pruebas estadísticas para identificar diferencias significativas. Los resultados muestran que ONNX logró reducir la latencia de inferencia hasta un 27,6 % e incrementar el rendimiento computacional hasta un 48,3 % respecto a PyTorch. Estas mejoras evidencian el potencial de las optimizaciones del entorno de ejecución para aprovechar eficientemente los recursos de GPU. El estudio destaca la importancia de evaluar el rendimiento computacional y las tecnologías de ejecución al desarrollar estrategias para el despliegue eficiente de modelos de lenguaje.</div>
  </div>
</li>
<li class="poster-item">
  <button class="poster-toggle" aria-expanded="false" onclick="this.setAttribute('aria-expanded', this.getAttribute('aria-expanded')==='true'?'false':'true'); this.nextElementSibling.classList.toggle('open')">
    <span class="poster-arrow">&#9654;</span>
    <span class="poster-num">36.</span>
    <span><span class="poster-title-text">Reglas de partición para Random Survival Forests bajo riesgos no proporcionales</span> — <span class="poster-author">Francisca Molina Jorquera</span></span>
  </button>
  <div class="poster-body">
    <div class="poster-affiliation">Universidad Adolfo Ibáñez, Chile</div>
    <div class="poster-abstract">Los Random Survival Forests predicen el tiempo hasta la ocurrencia de un evento, como la muerte o recaída de un paciente o la falla de un equipo. Cada árbol divide los datos usando, por defecto, el estadístico log-rank, que pierde potencia cuando los riesgos no son proporcionales, por ejemplo cuando un tratamiento es peor al comienzo y mejor después. Este trabajo adapta como regla de partición el log-rank ponderado combinado de Ditzhaus y Friedrich (2020), que agrega varias funciones de peso al estadístico original, y la compara con reglas basadas en distancias entre curvas de supervivencia, como las de tipo Cramér–von Mises. Todas las reglas se implementaron en el motor en C del paquete randomForestSRC y se evaluaron en conjuntos de datos simulados, con funciones de supervivencia conocidas, y en datos reales. Los resultados preliminares muestran un rendimiento comparable al log-rank clásico y ventajas en escenarios donde los riesgos se cruzan.</div>
  </div>
</li>
<li class="poster-item">
  <button class="poster-toggle" aria-expanded="false" onclick="this.setAttribute('aria-expanded', this.getAttribute('aria-expanded')==='true'?'false':'true'); this.nextElementSibling.classList.toggle('open')">
    <span class="poster-arrow">&#9654;</span>
    <span class="poster-num">37.</span>
    <span><span class="poster-title-text">Enrutamiento por Afinidad de Prefijo Adaptado a GPUs Heterogéneas para Agentes LLM en HPC Académico</span> — <span class="poster-author">Jose Luis Alejandro Muñoz Zevallos</span></span>
  </button>
  <div class="poster-body">
    <div class="poster-affiliation">Universidad de Ingeniería y Tecnología, Perú</div>
    <div class="poster-abstract">El serving de LLMs suele ser retador debido a que no solo necesitamos preocuparnos por el modelo de lenguaje, sino que también tenemos que tomar en cuenta la KV-caché generada por los mecanismos de atención. Para esto, las técnicas actuales buscan enrutar las peticiones de los usuarios por afinidad de sesión, dirigiendo las peticiones de una misma conversación al mismo servidor para reutilizar el contexto ya procesado y así mejorar la latencia y la reutilización de la KV- caché. Estas técnicas han sido validadas casi exclusivamente en centros de datos con GPUs homogéneas y conexiones de alta velocidad entre ellas. Los clústeres HPC académicos suelen funcionar bajo una realidad distinta, ya que manejan GPUs de capacidades muy desiguales, sin interconexión rápida y bajo restricciones de colas con tiempos límite. Creemos que, en un entorno como este, la afinidad de sesión sin ajustes puede resultar contraproducente, al fijar conversaciones completas en los equipos de menor capacidad y degradar severamente los tiempos de respuesta de un subconjunto de usuarios, aunque el rendimiento promedio del sistema parezca adecuado. Debido a esto, proponemos una política de enrutamiento que preserve la afinidad de sesión como criterio principal, pero que incorpore un mecanismo de reasignación consciente de la capacidad de cada equipo cuando mantener esa afinidad resulte perjudicial. Trabajos recientes en la literatura ya demuestran que este fenómeno ocurre en entornos homogéneos de alto desempeño, lo cual confirma la validez del mecanismo, pero ningún estudio lo ha evaluado todavía bajo condiciones de heterogeneidad severa y restricciones propias de los clústeres académicos.</div>
  </div>
</li>
<li class="poster-item">
  <button class="poster-toggle" aria-expanded="false" onclick="this.setAttribute('aria-expanded', this.getAttribute('aria-expanded')==='true'?'false':'true'); this.nextElementSibling.classList.toggle('open')">
    <span class="poster-arrow">&#9654;</span>
    <span class="poster-num">38.</span>
    <span><span class="poster-title-text">Fenotipado de infecciones fúngicas en plantas de tomate por medio de imágenes multiespectrales</span> — <span class="poster-author">Bruno Muschietti</span></span>
  </button>
  <div class="poster-body">
    <div class="poster-affiliation">Laboratorio de Inteligencia Artificial Aplicada - ICC, Argentina</div>
    <div class="poster-abstract">La detección temprana de enfermedades en plantas representa una tarea fundamental para el control de los cultivos. Con esta finalidad, la tecnología multiespectral se ha consolidado como una poderosa herramienta para detectar cambios leves en la fisiología de las hojas. Debido a los fenómenos intracelulares producto de la infección, la variación de la reflectancia del espectro electromagnético emerge como un indicativo temprano del desarrollo de lesiones, como las manchas necróticas. Es por esto que nos propusimos explorar el alcance y resultados de esta metodología en condiciones de laboratorio con el objetivo de trasladarla, en un futuro, a campo abierto. Para ello, fue necesario elaborar un sistema integral que incluyó: i) el diseño de un setup experimental no convencional con materiales comerciales, ii) la confección de un método de procesamiento de las imágenes crudas hasta obtener los recortes de los folíolos, iii) la selección de características calculadas sobre los valores espectrales, y iv) la implementación de modelos de machine learning como RF y SVM para clasificar los folíolos infectados. Con este procedimiento alcanzamos un F1-score de 85% y un recall de casi el 70% de los folíolos infectados, incluso con lesiones casi imperceptibles, utilizando una perspectiva a nivel del dosel vegetal.</div>
  </div>
</li>
<li class="poster-item">
  <button class="poster-toggle" aria-expanded="false" onclick="this.setAttribute('aria-expanded', this.getAttribute('aria-expanded')==='true'?'false':'true'); this.nextElementSibling.classList.toggle('open')">
    <span class="poster-arrow">&#9654;</span>
    <span class="poster-num">39.</span>
    <span><span class="poster-title-text">Adaptación de dominio y diversidad de variedades en la traducción automática neuronal bidireccional entre el aimara y el español</span> — <span class="poster-author">Mariela Melissa Nina Capujra</span></span>
  </button>
  <div class="poster-body">
    <div class="poster-affiliation">Universidade Federal de São Paulo (UNIFESP), Brasil</div>
    <div class="poster-abstract">Introducción El aimara es una lengua indígena hablada en Bolivia, Perú y Chile que presenta importantes desafíos para la traducción automática neuronal debido a la escasez de corpus paralelos, su riqueza morfológica y la diversidad regional y de géneros textuales. Objetivo Evaluar cómo la adaptación de dominio y la combinación de datos de distintas procedencias y variedades regionales influyen en la calidad de la traducción automática bidireccional entre el español y el aimara. Metodología Se utilizó el modelo NLLB-200-distilled-600M, previamente ajustado con un corpus bíblico de 35.009 pares de oraciones. Se construyó un corpus adicional de 24.047 pares paralelos procedentes de materiales educativos, médicos, periodísticos, conversacionales y recursos web asociados a Bolivia, Perú, Chile y fuentes de origen mixto. Se aplicó ajuste fino mediante descongelamiento progresivo de capas y se incorporaron pares de oraciones invertidos para permitir la traducción en ambas direcciones. Los modelos se evaluaron mediante BLEU, chrF++, TER y METEOR. Resultados El modelo específico entrenado con el subconjunto de origen mixto obtuvo los mejores resultados entre las configuraciones evaluadas, alcanzando 66,19 puntos de chrF++ para la traducción español→aimara y 68,35 para aimara→español, con 1.524 pares de entrenamiento. El modelo combinado, entrenado con 18.275 pares, obtuvo 38,58 y 52,25 puntos de chrF++, respectivamente. En la evaluación global, el modelo combinado superó al modelo de referencia bíblico en chrF++ en los seis subconjuntos evaluados y en ambas direcciones. Conclusiones Los resultados muestran que la adaptación con datos de distintas fuentes mejora el rendimiento respecto al modelo de referencia. La composición y diversidad de los datos parecen influir en la calidad de la traducción, aunque se necesitan experimentos adicionales para determinar sus efectos específicos. Persisten dificultades en las variedades con menor representación, especialmente en los datos asociados a Perú y Chile. Como trabajo futuro, se propone ampliar los corpus paralelos e incorporar evaluaciones con hablantes nativos. Palabras clave: traducción automática neuronal; aimara; español; adaptación de dominio; lenguas de bajos recursos; diversidad de datos.</div>
  </div>
</li>
<li class="poster-item">
  <button class="poster-toggle" aria-expanded="false" onclick="this.setAttribute('aria-expanded', this.getAttribute('aria-expanded')==='true'?'false':'true'); this.nextElementSibling.classList.toggle('open')">
    <span class="poster-arrow">&#9654;</span>
    <span class="poster-num">40.</span>
    <span><span class="poster-title-text">EscribeLab: potenciando la producción escrita en educación media de Uruguay</span> — <span class="poster-author">Ana Clara Nóbile González</span></span>
  </button>
  <div class="poster-body">
    <div class="poster-affiliation">Ceibal, Uruguay</div>
    <div class="poster-abstract">EscribeLab es una plataforma educativa que integra inteligencia artificial generativa para acompañar el proceso de escritura de textos argumentativos en estudiantes de educación media. La herramienta integra modelos de lenguaje de gran escala (LLM), instrucciones configurables y rúbricas de evaluación para ofrecer apoyos conversacionales y retroalimentación contextualizada en las distintas etapas del proceso de escritura. Su diseño busca promover la reflexión y la autonomía de los estudiantes, evitando que la IA sustituya la producción escrita y manteniendo al docente como figura central del proceso de enseñanza y aprendizaje. El proyecto, ganador de los Fondos Concursables de la Organización de Estados Iberoamericanos (OEI), se desarrolló en el marco de una intervención educativa que combinó la implementación de EscribeLab con instancias de formación y acompañamiento docente para su incorporación en el aula. La intervención fue evaluada mediante un ensayo controlado aleatorizado (RCT), con grupos de tratamiento y control, en el que participaron más de 1.000 estudiantes de educación media. Los resultados evidenciaron un efecto positivo sobre las habilidades de escritura de los estudiantes.</div>
  </div>
</li>
<li class="poster-item">
  <button class="poster-toggle" aria-expanded="false" onclick="this.setAttribute('aria-expanded', this.getAttribute('aria-expanded')==='true'?'false':'true'); this.nextElementSibling.classList.toggle('open')">
    <span class="poster-arrow">&#9654;</span>
    <span class="poster-num">41.</span>
    <span><span class="poster-title-text">Inteligencia artificial explicable para el diagnóstico dermatoscópico de cáncer de piel</span> — <span class="poster-author">Amanda Noris Hernández</span></span>
  </button>
  <div class="poster-body">
    <div class="poster-affiliation">Universidad de La Habana, Cuba</div>
    <div class="poster-abstract">Este póster presenta el proyecto DERMA-UH como un ecosistema integral que reúne diversas aplicaciones, versiones registradas y múltiples modelos de clasificación automática para el diagnóstico de cáncer de piel. Entre los clasificadores desarrollados en DERMA-UH se incluyen un ensembler de tres redes neuronales, un modelo basado en arquitectura Transformer, un clasificador XGBoost y un modelo de IA explicable (XAI). La adopción clínica de modelos de aprendizaje automático en dermatología está limitada por su naturaleza de «caja negra»: los dermatólogos desconfían de predicciones que no pueden interpretar. Para abordar esto, el modelo XAI presenta un sistema multimodal que combina un clasificador XGBoost entrenado sobre la base ISIC con tres modalidades de explicación: numérica, mediante valores SHAP (TreeSHAP) que cuantifican la relevancia de cada característica; visual, resaltando rasgos clínicos como bordes irregulares y velo azulado mediante procesamiento de imágenes; y textual, generada con un modelo de lenguaje biomédico (BioGPT) potenciado por Generación Aumentada por Recuperación (RAG) y alineada con criterios diagnósticos estándar (regla ABCDE). La validación con 68 dermatólogos, usando el marco Co-12, mostró que el sistema es percibido como relevante, comprensible y confiable, incluso por especialistas con conocimientos limitados en IA. El trabajo evidencia cómo la explicabilidad multimodal puede cerrar la brecha entre la interpretabilidad técnica y la práctica clínica, y abre líneas hacia mayor interactividad y validación a mayor escala.</div>
  </div>
</li>
<li class="poster-item">
  <button class="poster-toggle" aria-expanded="false" onclick="this.setAttribute('aria-expanded', this.getAttribute('aria-expanded')==='true'?'false':'true'); this.nextElementSibling.classList.toggle('open')">
    <span class="poster-arrow">&#9654;</span>
    <span class="poster-num">42.</span>
    <span><span class="poster-title-text">Desarrollo y validación de un modelo de IA para la clasificación automática de raquitismo</span> — <span class="poster-author">Ulises Ombrosi</span></span>
  </button>
  <div class="poster-body">
    <div class="poster-affiliation">ICC - UBA, Argentina</div>
    <div class="poster-abstract">El raquitismo es una enfermedad metabólica que afecta al desarrollo y la mineralización del tejido óseo durante la etapa pediátrica. Su diagnóstico suele apoyarse en la evaluación clínica, bioquímica y, principalmente, radiológica, donde las radiografías de muñeca resultan ser una de las herramientas más utilizadas para la identificación de afectaciones características de la enfermedad. En este contexto, los avances recientes en aprendizaje profundo aplicados a imágenes abren nuevas posibilidades para el desarrollo de sistemas de clasificación automáticos de la enfermedad, para contribuir al correcto diagnóstico de la misma. En este trabajo, se llevó adelante la conformación de un conjunto de datos de radiografías de muñecas sanas y enfermas, para el posterior desarrollo de los modelos de clasificación, y se diseñó un modelo de detección automática de la región de interés pertinente para la misma. Para la clasificación se siguieron tres enfoques: Redes neuronales convolucionales, modelos fundacionales pre-entrenados y prompting zero-shot a un VLM de dominio médico, siendo el segundo enfoque el que mejores resultados arrojó.</div>
  </div>
</li>
<li class="poster-item">
  <button class="poster-toggle" aria-expanded="false" onclick="this.setAttribute('aria-expanded', this.getAttribute('aria-expanded')==='true'?'false':'true'); this.nextElementSibling.classList.toggle('open')">
    <span class="poster-arrow">&#9654;</span>
    <span class="poster-num">43.</span>
    <span><span class="poster-title-text">FusionAR-KB: Una base de conocimiento multicapa para la caracterización de arquitecturas específicas de transcritos y la interpretación clínica de fusiones génicas en cáncer.</span> — <span class="poster-author">Daniela Orschanski</span></span>
  </button>
  <div class="poster-body">
    <div class="poster-affiliation">Fundacion para el Progreso de la Medicina, Argentina</div>
    <div class="poster-abstract">Introducción: Las fusiones génicas constituyen importantes mecanismos oncogénicos y biomarcadores de relevancia clínica para el diagnóstico, pronóstico y tratamiento dirigido del cáncer. Si bien su detección se incorpora cada vez más a la práctica clínica, los recursos disponibles se centran principalmente en catalogar eventos de fusión entre pares de genes, sin integrar de manera sistemática información transcriptómica, estructural y clínica. Esta limitación dificulta la interpretación de sus consecuencias biológicas y terapéuticas. Métodos: FusionAR-KB es una base de conocimiento que integra información genómica, estructural y clínica obtenida a partir de 1.420 muestras de secuenciación de ARN (RNA-seq), provenientes de 25 cohortes que abarcan 14 categorías de cáncer. Se reconstruyeron arquitecturas de fusión específicas de transcritos para caracterizar la diversidad de puntos de ruptura (breakpoints), el potencial codificante, el marco de lectura y la conservación de dominios proteicos. Asimismo, se evaluó la relevancia clínica de las fusiones mediante la integración de evidencia disponible en la base de datos CIViC. Resultados: FusionAR-KB permitió reconstruir arquitecturas específicas de transcritos para 72.700 fusiones génicas únicas. Se observó que el 7,5 % presentó múltiples arquitecturas definidas por distintas combinaciones de puntos de ruptura y transcritos, mientras que el 36 % generó configuraciones funcionales diferentes, con potencial para modificar el marco de lectura, la capacidad codificante o la conservación de dominios proteicos. En términos generales, el 45,7 % de las fusiones conservó potencial codificante, el 3,6 % involucró genes asociados a quinasas y solo el 0,4 % correspondió a fusiones con relevancia clínica documentada. Se identificaron 205 pacientes portadores de fusiones génicas clínicamente relevantes, incluidos 41 pacientes con fusiones potencialmente susceptibles de tratamiento dirigido que no estaban reportadas en CIViC para los tipos tumorales correspondientes. Este hallazgo pone de manifiesto oportunidades terapéuticas que exceden la evidencia actualmente recopilada en las bases de conocimiento disponibles. Además, FusionAR-KB permite investigar asociaciones entre la carga de fusiones tumorales (Tumor Fusion Burden, TFB) y los desenlaces clínicos de los pacientes. Conclusiones: Mediante la integración de arquitecturas transcriptómicas, consecuencias funcionales predichas, características estructurales y evidencia clínica en un marco unificado, FusionAR-KB transforma los catálogos tradicionales de fusiones génicas en un recurso que facilita su interpretación en el contexto de la oncología de precisión. Esta herramienta contribuye a la identificación de biomarcadores, la priorización de estrategias terapéuticas y el desarrollo de investigaciones traslacionales en cáncer, contemplando la diversidad de poblaciones y tipos tumorales.</div>
  </div>
</li>
<li class="poster-item">
  <button class="poster-toggle" aria-expanded="false" onclick="this.setAttribute('aria-expanded', this.getAttribute('aria-expanded')==='true'?'false':'true'); this.nextElementSibling.classList.toggle('open')">
    <span class="poster-arrow">&#9654;</span>
    <span class="poster-num">44.</span>
    <span><span class="poster-title-text">Modelamiento del control neuronal del ritmo locomotor en Aplysia californica mediante redes neuronales artificiales</span> — <span class="poster-author">Ayelen Oyarzo Pérez</span></span>
  </button>
  <div class="poster-body">
    <div class="poster-affiliation">Universidad de Chile</div>
    <div class="poster-abstract">Resumen del póster: La locomoción es una función motora fundamental en animales invertebrados y vertebrados, e incluye comportamientos como caminar, nadar o arrastrarse. Estos movimientos son generados por circuitos neuronales llamados Generadores de Patrones Centrales, capaces de producir actividad motora rítmica de forma autónoma. Sin embargo, aún no se comprende completamente cómo estos circuitos controlan el ritmo locomotor, una propiedad que emerge de la interacción colectiva de redes neuronales. Este trabajo estudia la dinámica colectiva de la red neuronal biológica que genera la locomoción en Aplysia californica, una babosa marina cuyo circuito locomotor se concentra en el ganglio pedal. Para ello, se utilizan registros experimentales de actividad neuronal y del output motor, junto con redes neuronales recurrentes entrenadas para reproducir la señal motora del ganglio. El objetivo no es únicamente construir un modelo predictivo, sino comparar la dinámica interna del modelo artificial con la de la red biológica. A partir de una metodología de interpretable machine learning e ingeniería inversa, se busca estudiar cómo el modelo representa al sistema original y qué aspectos de su dinámica pueden ayudar a comprender el control del ritmo locomotor. Estos avances pueden contribuir al desarrollo futuro de tecnologías biomédicas, como interfaces cerebro-máquina.</div>
  </div>
</li>
<li class="poster-item">
  <button class="poster-toggle" aria-expanded="false" onclick="this.setAttribute('aria-expanded', this.getAttribute('aria-expanded')==='true'?'false':'true'); this.nextElementSibling.classList.toggle('open')">
    <span class="poster-arrow">&#9654;</span>
    <span class="poster-num">45.</span>
    <span><span class="poster-title-text">Renderizado inverso térmico autosupervisado a partir de una única imagen hiperespectral infrarroja de onda larga</span> — <span class="poster-author">Fabian Perez</span></span>
  </button>
  <div class="poster-body">
    <div class="poster-affiliation">Universidad Industrial de Santander, Colombia</div>
    <div class="poster-abstract">Las imágenes hiperespectrales en el infrarrojo de onda larga (LWIR) entrelazan la temperatura de los objetos, la emisividad espectral, la distancia y la radiación descendente reflejada en una única medición. Recuperar estos componentes físicos constituye un problema inverso altamente mal planteado, en el que distintas combinaciones de ellos pueden reproducir espectros prácticamente idénticos. Históricamente, este problema se ha abordado tratando sus componentes físicos por separado, y solo recientemente algunos métodos han comenzado a estimarlos de manera conjunta. Sin embargo, estas formulaciones siguen operando píxel a píxel, lo que limita su capacidad para aprovechar la estructura espacial y semántica compartida en la escena. Para superar esta limitación, presentamos un método de renderizado inverso térmico autosupervisado que, a partir de un único cubo hiperespectral LWIR y una caracterización atmosférica, recupera la temperatura, la emisividad y la profundidad. Denominamos a esta descomposición TeD, la cual extiende la separación clásica al incorporar la profundidad como una tercera incógnita. En nuestro enfoque, una red neuronal predice los componentes físicos y un modelo diferenciable de transferencia radiativa los utiliza para reconstruir el cubo observado. El entrenamiento se guía mediante la reconstrucción, junto con restricciones físicas y geométricas complementarias. Una restricción física que no requiere etiquetas aprovecha la característica espectral del ozono a 9,6 μm para ordenar los píxeles según su contribución de radiación del cielo reflejada, orientando así la descomposición en regiones dominadas por la reflexión. Por su parte, una red preentrenada de estimación monocular de profundidad proporciona información sobre la geometría relativa de la escena sin imponer una profundidad métrica. Una evaluación exhaustiva sobre conjuntos de datos hiperespectrales LWIR simulados y reales, que abarcan diversas condiciones atmosféricas, horas del día, puntos de vista, ubicaciones, sensores y niveles de ruido, demuestra mejoras consistentes frente a los métodos del estado del arte. Nuestro código estará disponible públicamente.</div>
  </div>
</li>
<li class="poster-item">
  <button class="poster-toggle" aria-expanded="false" onclick="this.setAttribute('aria-expanded', this.getAttribute('aria-expanded')==='true'?'false':'true'); this.nextElementSibling.classList.toggle('open')">
    <span class="poster-arrow">&#9654;</span>
    <span class="poster-num">46.</span>
    <span><span class="poster-title-text">RIVA Challenge Interpretado: los conceptos detrás de una red de detección y clasificación de células en alta resolución</span> — <span class="poster-author">Silvano René Picard</span></span>
  </button>
  <div class="poster-body">
    <div class="poster-affiliation">FCEyN-UBA, Argentina</div>
    <div class="poster-abstract">La interpretabilidad mecanicista mediante Sparse Autoencoders (SAEs) ha demostrado ser eficaz para aislar conceptos monosemánticos en modelos de lenguaje y visión. En este trabajo evaluamos y comparamos cinco variantes de sparse autoencoders —Top-K SAE, Matching Pursuit SAE (MP- SAE), Orthogonal Matching Pursuit SAE (OMP-SAE), Relaxed-Archetypal SAE (RA-SAE) y Block Sparse Featurizers— integrados sobre las activaciones intermedias del Feature Pyramid Network (FPN) de una Faster-RCNN entrenada en el dataset RIVA. A través de un protocolo de evaluación cuantitativo exhaustivo, analizamos el compromiso entre reconstrucción, esparsidad y degeneración del diccionario utilizando métricas de fidelidad ($R^2$, L2 loss promedio, L2 loss relativa promedio), métricas de dispersión e inactividad (l1, epsilon- sparsity, índice de hoyer, códigos muertos), y propiedades geométricas del espacio latente (dictionary collinearity, hungarian loss y cosine hungarian loss para consistencia y alineación de diccionarios). Complementamos estos resultados cuantitativos con un análisis cualitativo profundo empleando las herramientas de visualización de activaciones de la librería overcomplete, lo que nos permite inspeccionar mapas de calor semánticos y posiblemente detectar la emergencia de características visuales monosemánticas en el backbone.</div>
  </div>
</li>
<li class="poster-item">
  <button class="poster-toggle" aria-expanded="false" onclick="this.setAttribute('aria-expanded', this.getAttribute('aria-expanded')==='true'?'false':'true'); this.nextElementSibling.classList.toggle('open')">
    <span class="poster-arrow">&#9654;</span>
    <span class="poster-num">47.</span>
    <span><span class="poster-title-text">Mermaid-LM: generación de diagramas mediante especialización eficiente de un modelo de lenguaje compacto</span> — <span class="poster-author">Elide Eduardo Portocarrero Burga</span></span>
  </button>
  <div class="poster-body">
    <div class="poster-affiliation">La Universidad Nacional de la Amazonía Peruana, Perú</div>
    <div class="poster-abstract">Introducción: La especialización de modelos de lenguaje para tareas específicas sigue siendo un desafío cuando los recursos computacionales son limitados. Mermaid-LM estudia la posibilidad de adaptar un modelo pequeño para generar diagramas a partir de descripciones en lenguaje natural. Para ello, se utiliza Mermaid, un lenguaje específico de dominio (DSL) que permite representar estructuras mediante código. El trabajo se centra en tres tipos de diagramas: flujo, mapas mentales y líneas de tiempo. Materiales y métodos: Se utilizó TinyLlama-1.1B-Chat, un modelo de aproximadamente 1.100 millones de parámetros, adaptado mediante Low-Rank Adaptation (LoRA) y cuantización de cuatro bits. Se preparó un corpus de 411 pares de instrucciones y diagramas, con 137 ejemplos por categoría. De ellos, 328 se destinaron al entrenamiento, 41 a validación y 42 se reservaron para pruebas. El entrenamiento se realizó con dos GPU NVIDIA Tesla T4. El sistema también incorpora un mecanismo de verificación sintáctica y corrección iterativa que permite generar nuevas respuestas cuando se detectan errores. Para evaluar su funcionamiento, se prepararon por separado 99 solicitudes de inferencia, distribuidas equitativamente entre los tres tipos de diagramas. Resultados: El modelo produjo 75 diagramas sintácticamente válidos en el primer intento (75,8 %). Tras aplicar el mecanismo de corrección, se obtuvieron 83 diagramas válidos (83,8 %), con un promedio de 1,42 iteraciones por solicitud. Los resultados fueron diferentes según la estructura solicitada: 66,7 % de validez en diagramas de flujo, 97,0 % en mapas mentales y 87,9 % en líneas de tiempo. Estas diferencias permiten identificar los diagramas de flujo como la categoría con mayores dificultades dentro de la evaluación realizada. Conclusiones: Los resultados muestran que un modelo compacto puede especializarse para generar código Mermaid utilizando un conjunto reducido de ejemplos y técnicas de ajuste fino eficientes en parámetros. Sin embargo, la validez sintáctica no garantiza que los diagramas representen correctamente todas las relaciones descritas en las instrucciones. Como continuación de esta investigación, se plantea evaluar la fidelidad semántica y comparar tanto la calidad de generación como el costo computacional frente a otras estrategias de adaptación.</div>
  </div>
</li>
<li class="poster-item">
  <button class="poster-toggle" aria-expanded="false" onclick="this.setAttribute('aria-expanded', this.getAttribute('aria-expanded')==='true'?'false':'true'); this.nextElementSibling.classList.toggle('open')">
    <span class="poster-arrow">&#9654;</span>
    <span class="poster-num">48.</span>
    <span><span class="poster-title-text">Completitud del reporte, calidad metodológica y riesgo de sesgo en estudios de modelos de inteligencia artificial para la predicción diagnóstica clínica con datos de población peruana: Una revisión sistemática metodológica</span> — <span class="poster-author">Judith Cristina Quiñones Inga</span></span>
  </button>
  <div class="poster-body">
    <div class="poster-affiliation">Universidad Científica del Sur - Grupo de Investigación &quot;CIPHER-LAC&quot;, Perú</div>
    <div class="poster-abstract">Resumen Objetivos del estudio: Evaluar la completitud del reporte, la calidad metodológica del desarrollo o actualización y el riesgo de sesgo de las evaluaciones del desempeño de modelos de inteligencia artificial para la predicción diagnóstica clínica individual estudiados con datos de población peruana, así como analizar las características metodológicas y de publicación asociadas con la completitud del reporte. Metodología: Se realizará un estudio metodológico observacional mediante métodos de revisión sistemática. Se incluirán artículos originales completos publicados en revistas con revisión por pares que informen el desarrollo, la actualización o la evaluación del desempeño de modelos de inteligencia artificial destinados a realizar una predicción diagnóstica clínica individual con datos de población peruana. Se buscará desde el inicio de la indización en MEDLINE, Embase, Scopus, Web of Science Core Collection, IEEE Xplore, SciELO Citation Index y la Biblioteca Virtual en Salud, complementadas mediante el rastreo de referencias y citas. Dos revisores seleccionarán los estudios y extraerán los datos de forma independiente. La completitud del reporte se evaluará por artículo mediante TRIPOD+AI, la calidad metodológica por modelo y el riesgo de sesgo por evaluación del desempeño mediante PROBAST+AI. CLAIM 2024 y TRIPOD-LLM se aplicarán complementariamente cuando corresponda. Los resultados se resumirán descriptivamente y las características asociadas con la completitud se explorarán mediante regresión fraccional. Palabras clave: Inteligencia Artificial; Modelos de Aprendizaje Predictivo; Sesgo; Diagnóstico; Revisión Sistemática.</div>
  </div>
</li>
<li class="poster-item">
  <button class="poster-toggle" aria-expanded="false" onclick="this.setAttribute('aria-expanded', this.getAttribute('aria-expanded')==='true'?'false':'true'); this.nextElementSibling.classList.toggle('open')">
    <span class="poster-arrow">&#9654;</span>
    <span class="poster-num">49.</span>
    <span><span class="poster-title-text">Selección Espectral para Redes con Heterofilia</span> — <span class="poster-author">PEDRO RAIGORODSKY</span></span>
  </button>
  <div class="poster-body">
    <div class="poster-affiliation">Universidad de la República, Uruguay</div>
    <div class="poster-abstract">Las redes neuronales espectrales sobre grafos filtran las señales según el espectro del Laplaciano del grafo. Los filtros polinomiales habituales son suaves y les cuesta aislar bandas de frecuencia estrechas, algo importante en grafos heterófilos, donde los nodos conectados suelen pertenecer a clases distintas. CayleyNets (Levie et al., 2018) introdujeron filtros basados en la transformada de Cayley del Laplaciano, que tiene módulo uno y es estable, pero centran toda la selección en el origen del espectro. Nosotros desplazamos la transformada, de modo que cada término tiene su propio centro y ancho de banda, ambos aprendidos, y combinamos varios de ellos. Así el filtro puede posicionarse en cualquier banda del espectro, y equivale a un filtro de polos (resolvente) normalizado. Lo usamos como reemplazo directo del paso de agregación en una arquitectura estándar de paso de mensajes, sin cambiar nada más. En el benchmark Roman-empire supera de forma consistente a GraphSAGE y GCN en todas las particiones, con hasta cuatro veces menos parámetros. Además, los filtros aprendidos son interpretables: permiten detectar rangos espectrales en los que la red se enfoca.</div>
  </div>
</li>
<li class="poster-item">
  <button class="poster-toggle" aria-expanded="false" onclick="this.setAttribute('aria-expanded', this.getAttribute('aria-expanded')==='true'?'false':'true'); this.nextElementSibling.classList.toggle('open')">
    <span class="poster-arrow">&#9654;</span>
    <span class="poster-num">50.</span>
    <span><span class="poster-title-text">Monitoreo de fauna silvestre con imágenes de drones</span> — <span class="poster-author">Agustín Roca</span></span>
  </button>
  <div class="poster-body">
    <div class="poster-affiliation">Universidad de San Andrés, Argentina</div>
    <div class="poster-abstract">Este trabajo estudia el uso de drones y deep learning para la detección de fauna silvestre en su hábitat natural. Como la identificación tradicional requiere mano de obra entrenada, lo cual es costoso en recursos y tiempo, hay una necesidad de soluciones más eficientes. Aprovechando imágenes aéreas de alta resolución, técnicas de visión por computadora son utilizadas para automatizar el proceso de identificación de cérvidos en dos proyectos en Buenos Aires. El primer proyecto, Proyecto Pantano, involucra al ciervo de los pantanos en el Delta del Paraná, mientras el segundo, Wildlife Monitoring Bots (WiMoBo), se enfoca en el venado de las pampas en el Parque Nacional Campos del Tuyú. Se entrenaron distintos modelos YOLO estudiando distintos parámetros y técnicas de augmentación de datos. Los resultados muestran que el modelo identifica correctamente el ciervo de los pantanos con alto grado de accuracy y hay indicios en su aplicabilidad en el venado de las pampas, aunque con algunas limitaciones. Este trabajo no solo ayuda a los esfuerzos de conservación actuales pero también muestra el potencial de integrar IA con drones para mejorar el monitoreo de fauna silvestre y prácticas de conservación.</div>
  </div>
</li>
<li class="poster-item">
  <button class="poster-toggle" aria-expanded="false" onclick="this.setAttribute('aria-expanded', this.getAttribute('aria-expanded')==='true'?'false':'true'); this.nextElementSibling.classList.toggle('open')">
    <span class="poster-arrow">&#9654;</span>
    <span class="poster-num">51.</span>
    <span><span class="poster-title-text">Implementación en FPGA de un Algoritmo Genético para la Estimación de Parámetros de Ruido impulsivo Middleton Clase A.</span> — <span class="poster-author">Ezequiel Dario Rodriguez</span></span>
  </button>
  <div class="poster-body">
    <div class="poster-affiliation">ICYTE-FACULTAD DE INGENIERIA (UNMDP), Argentina</div>
    <div class="poster-abstract">Este trabajo presenta el diseño e implementación en FPGA de un estimador de parámetros para ruido impulsivo Middleton Clase A mediante Algoritmos Genéticos (GA). Orientado a sistemas embebidos de tiempo real, el sistema formula la estimación minimizando la diferencia entre la función de distribución acumulada excedida empírica y la teórica. Evaluando variantes de GA en aritmética de punto fijo con operadores optimizados por manipulación de bits, se logra una precisión comparable al punto flotante pero con menor complejidad en hardware, demostrando alta eficiencia y adaptabilidad para aplicaciones en FPGA.</div>
  </div>
</li>
<li class="poster-item">
  <button class="poster-toggle" aria-expanded="false" onclick="this.setAttribute('aria-expanded', this.getAttribute('aria-expanded')==='true'?'false':'true'); this.nextElementSibling.classList.toggle('open')">
    <span class="poster-arrow">&#9654;</span>
    <span class="poster-num">52.</span>
    <span><span class="poster-title-text">Modelos de inteligencia artificial explicable para la clasificación de células cervicales con cambios subvisibles asociados al VPH utilizando imágenes de citología en base Liquida: integración de características radiómicas y valores SHAP</span> — <span class="poster-author">Mariangel Del carmen Rodriguez Leones</span></span>
  </button>
  <div class="poster-body">
    <div class="poster-affiliation">Doctorado en Ciencias e Ingeniería para la Salud, Facultad de Medicina, Ingeniería y Ciencias, Universidad de Valparaiso, Chile</div>
    <div class="poster-abstract">El cáncer de cuello uterino (CC) es la cuarta neoplasia maligna más frecuente entre las mujeres a nivel mundial. Aunque la prueba de Papanicolaou ha reducido la mortalidad en aproximadamente un 70%, su limitada sensibilidad y especificidad siguen planteando desafíos importantes. La citología en base liquida (LBC) mejora la calidad de la muestra; sin embargo, su interpretación todavía depende de un análisis manual y subjetivo. Este estudio tuvo como objetivo evaluar el rendimiento de modelos de inteligencia artificial explicable (XAI) para clasificar células cervicales con cambios subvisibles asociados a la infección por VPH a partir del análisis de imágenes de LBC. Se entrenó el modelo Mask R-CNN para la segmentación a nivel de instancia de células cervicales, lo que permitió generar un conjunto de datos de células individuales. Se extrajeron características radiómicas del núcleo y del citoplasma, seguidas de una selección de características mediante regresión Lasso y Random Forest (RF). Posteriormente, se evaluaron los clasificadores K-NN, SVM y RF. El modelo Mask R-CNN demostró un rendimiento de segmentación robusto en células superpuestas, alcanzando una mAP del 55,4 % y un AJI del 82,9 %. Entre los modelos de aprendizaje automático, SVM obtuvo el mejor rendimiento, con una sensibilidad del 95,2 % y una especificidad del 97,4 %. Los valores SHAP revelaron que las decisiones de clasificación estuvieron determinadas principalmente por características de textura y forma nuclear. Estos resultados destacan el potencial de los enfoques basados en XAI para apoyar el diagnóstico precoz del cáncer de cuello uterino y la toma de decisiones clínicas.</div>
  </div>
</li>
<li class="poster-item">
  <button class="poster-toggle" aria-expanded="false" onclick="this.setAttribute('aria-expanded', this.getAttribute('aria-expanded')==='true'?'false':'true'); this.nextElementSibling.classList.toggle('open')">
    <span class="poster-arrow">&#9654;</span>
    <span class="poster-num">53.</span>
    <span><span class="poster-title-text">Comparación de estrategias de selección de variables y regularización en clasificación con n ≪ p: análisis exploratorio en características derivadas de EEG</span> — <span class="poster-author">Merling Sabater Ramírez</span></span>
  </button>
  <div class="poster-body">
    <div class="poster-affiliation">Universidad de La Habana, Cuba</div>
    <div class="poster-abstract">Se estudia la discriminación entre dos grupos (Control, n=10; GR1, n=15) a partir de 339,760 características derivadas de EEG, que representan el cambio antes y después de una intervención. Con p ≫ n, la elección de la estrategia de selección y la forma de validarla condicionan las conclusiones. Se compararon cinco pipelines de reducción de dimensionalidad (filtros ANOVA, varianza e información mutua, seguidos de LASSO o Random Forest) y se evaluaron tres enfoques con SVM lineal y LOOCV: PCA por bloques (11 componentes, exactitud 0.96), SVM con L1 (0.92) y SVM con MRMR y L1 (1.0). Se identificaron de forma recurrente las bandas Delta (1–4 Hz) y Gamma (30–45 Hz). Como la preselección de variables usó a todos los sujetos, estas cifras pueden estar infladas. Se repitió la comparación con toda la selección dentro de cada fold del LOOCV, e incluyendo seis métodos: SVM lineal, SVM RBF, SVM-L1, RFE-SVM, group lasso por bloques y kernels múltiples (MKL). Se añadieron un test de permutación de etiquetas, estabilidad por submuestreo y poda de variables correlacionadas. Sin poda, los seis métodos alcanzan una balanced accuracy de 0.97–1.00. Con poda por correlación (|r| &gt; 0.8), el SVM lineal, el RBF y el RFE bajan a 0.68–0.78, mientras que group lasso, MKL y L1 se mantienen en 0.97–1.00. El group lasso es el más estable y selecciona de forma consistente la potencia Delta y la razón HighBeta/Gamma. A nivel de variable individual, la selección es poco estable: es más fiable informar la importancia por bloque. Limitaciones n = 25 sin validación externa, variables muy redundantes y efectos grandes que requieren descartar artefactos</div>
  </div>
</li>
<li class="poster-item">
  <button class="poster-toggle" aria-expanded="false" onclick="this.setAttribute('aria-expanded', this.getAttribute('aria-expanded')==='true'?'false':'true'); this.nextElementSibling.classList.toggle('open')">
    <span class="poster-arrow">&#9654;</span>
    <span class="poster-num">54.</span>
    <span><span class="poster-title-text">Transformers guiados por atención humana: integración de eye-tracking para mejorar el entrenamiento de modelos de lenguaje</span> — <span class="poster-author">Tomás Schmidt Liermann</span></span>
  </button>
  <div class="poster-body">
    <div class="poster-affiliation">UBA-LIAA, Argentina</div>
    <div class="poster-abstract">Estudiamos cómo incorporar señales de lectura humana, obtenidas mediante la atención humana, al entrenamiento de modelos de lenguaje en español. Para lograr esto utilizamos a BETO y exploramos dos estrategias: Primero una rama auxiliar guiada por el orden de las fijaciones oculares y segundo máscaras de atención basadas en tiempos de lectura. Evaluamos los modelos en inferencia textual y detección de discurso de odio. Sobre los resultados, las mejoras fueron pequeñas y no sistemáticas, con resultados favorables en ciertas configuraciones para la tarea de detección de odio .</div>
  </div>
</li>
<li class="poster-item">
  <button class="poster-toggle" aria-expanded="false" onclick="this.setAttribute('aria-expanded', this.getAttribute('aria-expanded')==='true'?'false':'true'); this.nextElementSibling.classList.toggle('open')">
    <span class="poster-arrow">&#9654;</span>
    <span class="poster-num">55.</span>
    <span><span class="poster-title-text">SpatialChain: Un Benchmark para Auditar la Fidelidad del Razonamiento Espacial en VLMs</span> — <span class="poster-author">Rafael Teixeira Sousa</span></span>
  </button>
  <div class="poster-body">
    <div class="poster-affiliation">Centro de Excelência em Inteligência Artificial - CEIA, Brasil</div>
    <div class="poster-abstract">Los modelos de visión y lenguaje (VLMs) con capacidad de razonamiento alcanzan una precisión cada vez mayor en benchmarks espaciales. Sin embargo, una respuesta final correcta no permite determinar si el modelo realmente razonó sobre las relaciones espaciales o si aprovechó un atajo lingüístico. Para hacer observable esta distinción, presentamos SpatialChain, un conjunto de datos compuesto por 28.350 ejemplos de entrenamiento y 899 de prueba, en el que cada pregunta espacial de GQA está asociada a una cadena de razonamiento fundamentada en su grafo de escena y conservada únicamente cuando su respuesta coincide con la verdad de referencia simbólica (symbolic ground truth). A partir de estas cadenas, proponemos un protocolo de evaluación que mide la calidad del razonamiento de un modelo con respecto al grafo de escena, independientemente de su respuesta final. En este protocolo, definimos un atajo (shortcut) como una respuesta correcta cuya cadena de razonamiento no está fundamentada en las relaciones requeridas por la pregunta. Validamos esta medida utilizando 198 ejemplos anotados por humanos. La aplicación del protocolo a nueve VLMs con capacidad de razonamiento revela comportamientos que las métricas tradicionales de precisión no permiten identificar. Cuatro modelos alcanzan una precisión de al menos el 79 %, pero recurren a atajos en el 39 % o más de los ejemplos de prueba. Estos atajos se manifiestan de dos maneras: reformulando la pregunta o describiendo la escena sin resolver la relación espacial solicitada. La calidad de las cadenas de razonamiento permite predecir la corrección de las respuestas dentro de siete de los nueve modelos, pero no al comparar diferentes modelos entre sí. Además, las preguntas que requieren múltiples pasos de razonamiento (multi-hop) no presentan mayor dificultad que aquellas de un solo paso (single-hop), lo que sugiere que la principal limitación se encuentra en la percepción de relaciones individuales y no en su composición. Finalmente, el ajuste fino supervisado (Supervised Fine-Tuning, SFT) con SpatialChain mejora el rendimiento de Qwen3-VL-8B en 6,2 puntos porcentuales dentro del dominio de evaluación y reduce su tasa de atajos al 22 %. No obstante, también intensifica el sesgo hacia respuestas afirmativas (yes-bias) y especializa el estilo de las respuestas, en detrimento del rendimiento en benchmarks externos.</div>
  </div>
</li>
<li class="poster-item">
  <button class="poster-toggle" aria-expanded="false" onclick="this.setAttribute('aria-expanded', this.getAttribute('aria-expanded')==='true'?'false':'true'); this.nextElementSibling.classList.toggle('open')">
    <span class="poster-arrow">&#9654;</span>
    <span class="poster-num">56.</span>
    <span><span class="poster-title-text">El drift representacional domina la degradación de decodificadores entre sesiones en la corteza visual primaria del ratón</span> — <span class="poster-author">Santiago Tobio</span></span>
  </button>
  <div class="poster-body">
    <div class="poster-affiliation">Mercadolibre, Universidad de San Andrés, Argentina</div>
    <div class="poster-abstract">Las representaciones neuronales de un mismo estímulo cambian a lo largo de los días aun cuando la conducta se mantiene estable, un fenómeno conocido como drift representacional. Esto genera un problema concreto: un decodificador entrenado en una sesión pierde desempeño al aplicarse en otra. La pregunta es cuánto de esa pérdida refleja un cambio real del código neuronal y cuánto se debe a factores más triviales. Usé el dataset Visual Behavior 2P del Allen Institute: 32 ratones, imágenes de calcio de dos fotones en V1 y 8 imágenes naturales presentadas durante una tarea de detección de cambio. Sobre esos datos entrené decodificadores de identidad del estímulo (regresión logística, MLP y Conv1D). Dentro de una misma sesión, el estímulo se decodifica con una exactitud mediana del 85% en 204 sesiones. Las representaciones temporales superan a las estáticas por unos 8,6 puntos porcentuales, y los modelos lineales son los mejores en aproximadamente la mitad de las sesiones, lo que indica que el código es mayormente linealmente separable. Para el caso entre sesiones propongo una descomposición telescópica de la pérdida, medida en bits mediante V-información (información predictiva usable). Tiene tres términos: (i) la restricción a las neuronas rastreadas entre sesiones, (ii) los cambios de escala o ganancia en la entrada y (iii) el drift residual. El drift residual explica alrededor del 60% de la degradación, la pérdida de neuronas cerca del 32% y los cambios de ganancia cerca del 9%. Por lo tanto, la caída de los decodificadores no se explica principalmente por el recambio de neuronas ni por cambios de ganancia, sino por una reorganización del código poblacional. El enfoque ofrece una forma cuantitativa, en bits, de separar las fuentes de inestabilidad en los modelos de lectura neuronal.</div>
  </div>
</li>
<li class="poster-item">
  <button class="poster-toggle" aria-expanded="false" onclick="this.setAttribute('aria-expanded', this.getAttribute('aria-expanded')==='true'?'false':'true'); this.nextElementSibling.classList.toggle('open')">
    <span class="poster-arrow">&#9654;</span>
    <span class="poster-num">57.</span>
    <span><span class="poster-title-text">Evaluación de monitores de control de IA con costos de error asimétricos</span> — <span class="poster-author">Juan Ignacio Tollo</span></span>
  </button>
  <div class="poster-body">
    <div class="poster-affiliation">Muttdata, Argentina</div>
    <div class="poster-abstract">Más allá de las métricas de ranking: proper scoring rules y costo esperado</div>
  </div>
</li>
<li class="poster-item">
  <button class="poster-toggle" aria-expanded="false" onclick="this.setAttribute('aria-expanded', this.getAttribute('aria-expanded')==='true'?'false':'true'); this.nextElementSibling.classList.toggle('open')">
    <span class="poster-arrow">&#9654;</span>
    <span class="poster-num">58.</span>
    <span><span class="poster-title-text">Evaluación de arquitecturas CNN preentrenadas en U- Net para la segmentación de nódulos pulmonares mediante aprendizaje por transferencia</span> — <span class="poster-author">IVAR VARGAS BELIZARIO</span></span>
  </button>
  <div class="poster-body">
    <div class="poster-affiliation">UNIVERSIDAD NACIONAL DE JULIACA, Perú</div>
    <div class="poster-abstract">La segmentación automática de nódulos pulmonares en imágenes de tomografía computarizada (TC) constituye un desafío relevante en el análisis de imágenes médicas debido a la variabilidad en el tamaño, la morfología y los límites de las lesiones. Las arquitecturas de aprendizaje profundo, particularmente U-Net, han demostrado potencial para abordar tareas de segmentación mediante la integración de características semánticas y espaciales. Este trabajo propone evaluar el desempeño de diferentes arquitecturas de redes neuronales convolucionales (CNN) preentrenadas, utilizadas como codificadores (encoders) dentro de U-Net, para la segmentación de nódulos pulmonares. La metodología contempla la incorporación de arquitecturas como ResNet, MobileNet y EfficientNet, cuyos pesos preentrenados serán adaptados mediante técnicas de aprendizaje por transferencia (transfer learning) y ajuste fino (fine-tuning). Se desarrollará un protocolo experimental comparativo bajo condiciones homogéneas de entrenamiento, preprocesamiento y evaluación, con el propósito de analizar la influencia de cada codificador en la calidad de las máscaras de segmentación. El desempeño se evaluará mediante métricas como el coeficiente Dice y la intersección sobre la unión (IoU), complementadas con un análisis visual de las segmentaciones obtenidas. Asimismo, se considerarán aspectos relacionados con la complejidad computacional y la eficiencia de los modelos. Esta investigación busca identificar las ventajas y limitaciones de diferentes codificadores CNN preentrenados integrados en U-Net y contribuir al desarrollo de estrategias de segmentación de imágenes médicas basadas en aprendizaje profundo.</div>
  </div>
</li>
<li class="poster-item">
  <button class="poster-toggle" aria-expanded="false" onclick="this.setAttribute('aria-expanded', this.getAttribute('aria-expanded')==='true'?'false':'true'); this.nextElementSibling.classList.toggle('open')">
    <span class="poster-arrow">&#9654;</span>
    <span class="poster-num">59.</span>
    <span><span class="poster-title-text">Aprendizaje automático para la estratificación longitudinal del riesgo en atención primaria de salud</span> — <span class="poster-author">KEIKO SAHORI VEINTIMILLA CARRION</span></span>
  </button>
  <div class="poster-body">
    <div class="poster-affiliation">Universidad de Valparaíso, Chile</div>
    <div class="poster-abstract">Este estudio propone un enfoque basado en aprendizaje automático para predecir la inasistencia a citas médicas en la atención primaria de salud. Se analizaron 156.897 citas correspondientes a 37.759 pacientes de 14 establecimientos de salud de Valparaíso, Chile, integrando información clínica, sociodemográfica e historial de atenciones. Se evaluaron distintos algoritmos de aprendizaje automático. Los resultados permitieron identificar factores asociados a la inasistencia, como el historial de citas perdidas y el tiempo transcurrido desde la última atención. Este enfoque busca contribuir a la identificación anticipada de pacientes con mayor riesgo de inasistencia, facilitando estrategias de seguimiento y una gestión más eficiente de los recursos sanitarios.</div>
  </div>
</li>
<li class="poster-item">
  <button class="poster-toggle" aria-expanded="false" onclick="this.setAttribute('aria-expanded', this.getAttribute('aria-expanded')==='true'?'false':'true'); this.nextElementSibling.classList.toggle('open')">
    <span class="poster-arrow">&#9654;</span>
    <span class="poster-num">60.</span>
    <span><span class="poster-title-text">Evaluación comparativa de arquitecturas de aprendizaje automático para el estudio termodinámico de la inclusión molecular en ciclodextrinas</span> — <span class="poster-author">Nicolás Andrés Villagrán dos Santos</span></span>
  </button>
  <div class="poster-body">
    <div class="poster-affiliation">Universidad de Buenos Aires. Facultad de Ciencias Exactas y Naturales. Departamento de Química Inorgánica, Analítica y Química Física, Argentina</div>
    <div class="poster-abstract">La encapsulación molecular en ciclodextrinas (CDs) es un proceso complejo siendo la evaluación de las interacciones intermoleculares fundamental en el diseño y optimización de sistemas para las industrias alimentaria y farmacéutica. Este trabajo tuvo como objetivo el desarrollo de un modelo predictivo para el cambio en energía libre de Gibbs (ΔG) asociado al proceso de inclusión molecular. Se evaluaron tres posibles arquitecturas de aprendizaje automático: XGBoost, regresión de procesos gaussianos (GPR) y transformers (aprendizaje por transferencia empleando CHEMBERTa) sobre un conjunto de datos empíricos aplicando RDKit en Python para calcular descriptores moleculares. Mientras que el modelo con transformers presentó dilución de atención con estructuras moleculares complejas y GPR tuvo dificultades con la variabilidad inherente a los descriptores moleculares, XGBoost logró la mayor capacidad predictiva. Se implementó posteriormente un análisis no supervisado de clasificación basado en valores SHAP de los descriptores moleculares, que agrupó a los compuestos encapsulados y a las CDs en diferentes familias de acuerdo a las interacciones intermoleculares más relevantes. Este trabajo permitiría reducir las emisiones de CO2 en más del 90% en comparación a métodos experimentales clásicos, mostrándose como una herramienta interpretable, predictiva y eficaz para mejorar la sostenibilidad de los procesos químicos.</div>
  </div>
</li>
<li class="poster-item">
  <button class="poster-toggle" aria-expanded="false" onclick="this.setAttribute('aria-expanded', this.getAttribute('aria-expanded')==='true'?'false':'true'); this.nextElementSibling.classList.toggle('open')">
    <span class="poster-arrow">&#9654;</span>
    <span class="poster-num">61.</span>
    <span><span class="poster-title-text">Memoria regulatoria ante alteraciones de los estados cromatínicos: aprendizaje profundo y clustering de genes asociados a TADs</span> — <span class="poster-author">David Weinstein Barriga</span></span>
  </button>
  <div class="poster-body">
    <div class="poster-affiliation">Universidad del Desarrollo, Chile</div>
    <div class="poster-abstract">La organización tridimensional del genoma establece regiones denominadas dominios de asociación topológica (TADs), que delimitan los contactos entre promotores y elementos reguladores. Sin embargo, su alteración no siempre produce respuestas transcripcionales inmediatas, lo que plantea la existencia de una memoria regulatoria transitoria. Para caracterizar esta memoria y su relación con la arquitectura cromatínica, se integraron datos públicos de Micro-C, ChIP-seq, mNET-seq y RNA-seq de células madre embrionarias de ratón sometidas a depleción de RAD21 (Hsieh et al., 2022; GSE178982). Se utilizó un modelo Latent Ordinary Differential Equation (Latent ODE) para analizar la persistencia regulatoria y caracterizar respuestas diferidas, incorporando los intervalos entre mediciones. Se aplicó clustering para agrupar genes según sus perfiles de respuesta y examinar su relación con contactos enhancer– promotor, límites de TADs y reguladores transcripcionales. Se empleó Principal Component Analysis (PCA) como referencia para comparar las representaciones obtenidas mediante aprendizaje profundo. Esta investigación permitirá evaluar los efectos del desacople entre arquitectura cromatínica y regulación génica sobre la respuesta transcripcional, e identificar regiones genómicas que mantienen su actividad regulatoria tras la perturbación.</div>
  </div>
</li>
<li class="poster-item">
  <button class="poster-toggle" aria-expanded="false" onclick="this.setAttribute('aria-expanded', this.getAttribute('aria-expanded')==='true'?'false':'true'); this.nextElementSibling.classList.toggle('open')">
    <span class="poster-arrow">&#9654;</span>
    <span class="poster-num">62.</span>
    <span><span class="poster-title-text">Menos anotaciones, desempeño comparable: aprendizaje auto-supervisado para clasificar planos de ultrasonido fetal</span> — <span class="poster-author">Gema Alexandra Zambrano Zambrano</span></span>
  </button>
  <div class="poster-body">
    <div class="poster-affiliation">Escuela Superior Politécnica del Litoral, Ecuador</div>
    <div class="poster-abstract">1. Motivación Entrenar modelos de clasificación de ultrasonido fetal requiere miles de imágenes anotadas por especialistas. En regiones con recursos limitados, esos especialistas escasean, y eso frena el acceso al diagnóstico prenatal automatizado. 2. Pregunta de investigación ¿Cuántas anotaciones permite ahorrar el preentrenamiento auto- supervisado (SSL), y su beneficio se mantiene fuera del dominio de entrenamiento? 3. Métodos *Datos: Fetal Planes DB (7.129 imágenes, 896 pacientes) y NatalIA PBF-US1 (1.246 imágenes, 90 estudios en fantoma). *Preentrenamiento sin etiquetas: SimCLR (ResNet-50, contrastivo) y MAE (ViT-S/16, enmascarado). *Fine Tunning: del 10 % al 100 % de los pacientes etiquetados, con fracciones anidadas a nivel de paciente. *Experimentos control: inicialización ImageNet y aleatoria. *Evaluación: conjunto de prueba oficial de Fetal Planes DB y validación cruzada de 5 particiones en NatalIA. 4. Resultado principal *SimCLR con 70 % de datos etiquetados iguala a un modelo ResNet-50 pre entrenado con ImageNet con 100 % de datos etiquetados: Macro F1 score:94,23 frente a 93,43. *SimCLR con 10 % de datos etiquetados supera a un modelo ResNet-50 con pesos aleatorio con 100 % de datos etiquetados: Macro F1 score: 90,09 frente a 87,63. *MAE con 100 % de datos etiquetados obtiene Macro F1 score de 87,72, sin ventaja estadistísticamente significativa sobre el entrenamiento desde cero. 5. Transferencia a un dominio externo *SimCLR ( Macro F1 score: 79,33 ± 6,08) e ImageNet ( Macro F1 score: 78,87 ± 8,07) son estadísticamente equivalentes (p = 0,92). *Ambos superan al modelo aleatorio ( Macro F1 score: 58,31 ± 10,49; p = 0,004). *La columna, un plano ausente en Fetal Planes DB, alcanza F1 score = 0,73. *El fémur es el plano más afectado (F1 score 0,89 -&gt;0,54): 22 de 46 imágenes se confunden con “sin plano”. 6. Limitaciones *SimCLR parte de pesos ImageNet y MAE de inicialización aleatoria. La comparación entre ambos mezcla arquitectura y objetivo de preentrenamiento. *NatalIA son barridos de un fantoma fetal realizados por operadores no expertos, no estudios en pacientes. 7. Conclusiones *SimCLR reduce en 30 % los pacientes etiquetados necesarios sin perder desempeño frente a ImageNet. *En un dominio externo, el preentrenamiento mantiene una ventaja amplia sobre el entrenamiento desde cero. *Reducir la dependencia de anotadores expertos acerca el diagnóstico prenatal automatizado a contextos con pocos especialistas. ** Trabajo en curso, se están ampliando los experimentos**</div>
  </div>
</li>
</ul>

<br>

<p>
  Si querés ver el programa de la edición anterior, podés visitar la <a href="/2025/schedule.html">página de la edición 2025</a>.
</p>