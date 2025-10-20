---
layout: page
permalink: /schedule/
title: Programa
description: La escuela se dará en el Aula Magna del Pabellón 1 (Universidad de Buenos Aires), entre el 20 de octubre y el 24 de octubre 2025.
nav: true
nav_order: 2
---

<style>
  .schedule-wrapper {
    width: 100%;
    overflow-x: auto;
  }
  
  .schedule-static {
    border-collapse: collapse !important;
    width: 100% !important;
    text-align: center !important;
    pointer-events: none !important;
  }
  
  .schedule-static * {
    pointer-events: auto !important;
    cursor: default !important;
  }
  
  .schedule-static tr {
    display: table-row !important;
    visibility: visible !important;
    opacity: 1 !important;
    height: auto !important;
  }
  
  .schedule-static td,
  .schedule-static th {
    display: table-cell !important;
    padding: 8px !important;
    border: 1px solid #ddd !important;
  }
  
  .schedule-static .header {
    background-color: rgb(215, 215, 215) !important;
    border-top: 1pt solid white !important;
    border-bottom: 1pt solid black !important;
  }
  
  .schedule-static .header th:first-child {
    border-top-left-radius: 10px;
  }
  
  .schedule-static .header th:last-child {
    border-top-right-radius: 10px;
  }
  
  .schedule-static tr.alt-row {
    background-color: rgb(240, 240, 240) !important;
  }
</style>

<div class="schedule-wrapper">
  <table class="schedule-static">
    <thead>
      <tr class="header">
        <th style="width: 15%;">Horario</th>
        <th style="width: 17%;">Lunes<br>20 de octubre</th>
        <th style="width: 17%;">Martes<br>21 de octubre</th>
        <th style="width: 17%;">Miércoles<br>22 de octubre</th>
        <th style="width: 17%;">Jueves<br>23 de octubre</th>
        <th style="width: 17%;">Viernes<br>24 de octubre</th>
      </tr>
    </thead>
    <tbody>
      <!-- 09:00 - 10:30 -->
      <tr class="alt-row">
        <td>09:00 - 10:30</td>
        <td>Apertura<br>"Pre-entrenamiento de grandes modelos de lenguaje" (Omar Florez)</td>
        <td>"Métricas de evaluación de sistemas de clasificación: costo esperado, proper scoring rules y calibración" (Luciana Ferrer)</td>
        <td>"Metodos Bayesianos y de aprendizaje para problemas inversos en procesamiento de imágenes" (Andrés Almansa)</td>
        <td>"Aprendizaje autosupervisado para problemas inversos" (Julián Tachella)</td>
        <td>"Transporte Óptimo Computacional" (Marco Cuturi)</td>
      </tr>
      <!-- 10:30 - 10:50 -->
      <tr>
        <td>10:30 - 10:50</td>
        <td><i>Coffee Break</i></td>
        <td><i>Coffee Break</i></td>
        <td><i>Coffee Break</i></td>
        <td><i>Coffee Break</i></td>
        <td><i>Coffee Break</i></td>
      </tr>
      <!-- 10:50 - 12:00 -->
      <tr class="alt-row">
        <td>10:50 - 12:00</td>
        <td>"Pre-entrenamiento de grandes modelos de lenguaje" (Omar Florez)</td>
        <td>"Métricas de evaluación de sistemas de clasificación: costo esperado, proper scoring rules y calibración" (Luciana Ferrer)</td>
        <td>"Metodos Bayesianos y de aprendizaje para problemas inversos en procesamiento de imágenes" (Andrés Almansa)</td>
        <td>"Aprendizaje autosupervisado para problemas inversos" (Julián Tachella)</td>
        <td>"Transporte Óptimo Computacional" (Marco Cuturi)</td>
      </tr>
      <!-- 12:00 - 13:30 -->
      <tr>
        <td>12:00 - 13:30</td>
        <td><i>Almuerzo</i></td>
        <td><i>Almuerzo</i></td>
        <td><i>Almuerzo</i></td>
        <td><i>Almuerzo</i></td>
        <td><i>Almuerzo / Tiempo libre</i></td>
      </tr>
      <!-- 13:30 - 15:00 -->
      <tr class="alt-row">
        <td>13:30 - 15:00</td>
        <td>"Optimización para aprendizaje automático" (Victoria Peterson)</td>
        <td>"Modelos de difusión para la generación de video" (José Lezama)</td>
        <td>"Cuantificación de incertidumbre en variables continuas" (Marcelo Pereyra)</td>
        <td>"Un enfoque ML a la neurociencia" (Demian Wasserman)</td>
        <td></td>
      </tr>
      <!-- 15:00 - 15:20 -->
      <tr>
        <td>15:00 - 15:20</td>
        <td><i>Coffee Break</i></td>
        <td><i>Coffee Break</i></td>
        <td><i>Coffee Break</i></td>
        <td><i>Coffee Break</i></td>
        <td></td>
      </tr>
      <!-- 15:20 - 16:30 -->
      <tr class="alt-row">
        <td>15:20 - 16:30</td>
        <td>"Optimización para aprendizaje automático" (Victoria Peterson)</td>
        <td>"Modelos de difusión para la generación de video" (José Lezama)</td>
        <td>"AI para descubrimiento de vulnerabilidades de ciberseguridad" (Martin Arjovsky)</td>
        <td>"Un enfoque ML a la neurociencia" (Demian Wasserman)</td>
        <td></td>
      </tr>
      <!-- 16:30 - 17:30 -->
      <tr>
        <td>16:30 - 17:30</td>
        <td><i>Sesión de posters</i></td>
        <td><i>Sesión de posters</i></td>
        <td></td>
        <td></td>
        <td></td>
      </tr>
      <!-- 17:30 - 19:00 -->
      <tr class="alt-row">
        <td>17:30 - 19:00</td>
        <td><i>Cocktail de bienvenida</i></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
      </tr>
    </tbody>
  </table>
</div>

<script>
  // Ejecutar después de que todo esté cargado
  window.addEventListener('load', function() {
    setTimeout(function() {
      const table = document.querySelector('.schedule-static');
      if (table) {
        // Remover todos los event listeners clonando la tabla
        const newTable = table.cloneNode(true);
        table.parentNode.replaceChild(newTable, table);
        
        // Forzar visibilidad de todas las filas
        newTable.querySelectorAll('tr').forEach(function(row) {
          row.style.display = 'table-row';
          row.style.visibility = 'visible';
          row.style.opacity = '1';
        });
      }
    }, 100);
  });
</script>