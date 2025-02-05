# EVADO
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Evaluación Docente</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <h1>Agregar Nuevo Usuario</h1>
    <form  id="usuarios"  method="post">
      <div class="form-group">
          <label for="username">Nombre de Usuario</label>
          <input type="text" id="username" name="username" required>
      </div>
      <div class="form-group">
          <label for="password">Contraseña</label>
          <input type="password" id="password" name="password" required>
      </div>
      <div class="form-group">
          <label for="nombre_completo">Nombre Completo</label>
          <input type="text" id="nombre_completo" name="nombre_completo" required>
      </div>
      <button type="submit">Agregar Usuario</button>
  </form>

  <h1>Evaluación Docente</h1>
  <form id="evaluationForm">
      <div id="questionsContainer">
          <div class="question">
              <label for="question1">1. Cumple con la actividad académica sin superposición horaria.</label><br>
              <select id="question1" name="question1" required>
                  <option value="">Seleccione una opción</option>
                  <option value="No aplica">No aplica</option>
                  <option value="1. Nunca">1. Nunca</option>
                  <option value="2. A veces">2. A veces</option>
                  <option value="3. Siempre">3. Siempre</option>
              </select>
          </div>

          <div class="question">
            <label for="question2">2. Cumple con el horario establecido para la atención al estudiantado (horas de consulta).</label><br>
            <select id="question2" name="question2" required>
              <option value="">Seleccione una opción</option>
              <option value="No aplica">No aplica</option>
              <option value="1. Nunca">1. Nunca</option>
              <option value="2. A veces">2. A veces</option>
              <option value="3. Siempre">3. Siempre</option>
          </select>
          </div>
          
          <div class="question">
            <label for="question3">3. Comunica sus ideas de forma clara y precisa.</label><br>
            <select id="question3" name="question3" required>
              <option value="">Seleccione una opción</option>
              <option value="No aplica">No aplica</option>
              <option value="1. Nunca">1. Nunca</option>
              <option value="2. A veces">2. A veces</option>
              <option value="3. Siempre">3. Siempre</option>
          </select>
      </div>
          
          <div class="question">
            <label for="question4">4. Favorece situaciones de diálogo con sus colegas.</label><br>
            <select id="question4" name="question4" required>
              <option value="">Seleccione una opción</option>
              <option value="No aplica">No aplica</option>
              <option value="1. Nunca">1. Nunca</option>
              <option value="2. A veces">2. A veces</option>
              <option value="3. Siempre">3. Siempre</option>
          </select>
      </div>
          
          <div class="question">
            <label for="question5">5. Coordina y organiza con otras/os docentes las acciones pertinentes a la labor académica.</label><br>
            <select id="question5" name="question5" required>
              <option value="">Seleccione una opción</option>
              <option value="No aplica">No aplica</option>
              <option value="1. Nunca">1. Nunca</option>
              <option value="2. A veces">2. A veces</option>
              <option value="3. Siempre">3. Siempre</option>
          </select>
      </div>
          
          <div class="question">
            <label for="question6">6. Coordina y organiza con el personal administrativo las acciones pertinentes a labor académica.</label><br>
            <select id="question6" name="question6" required>
              <option value="">Seleccione una opción</option>
              <option value="No aplica">No aplica</option>
              <option value="1. Nunca">1. Nunca</option>
              <option value="2. A veces">2. A veces nunca</option>
              <option value="3. Siempre">3. Siempre</option>
          </select>
      </div>
          
          <div class="question">
            <label for="question7">7. Si corresponde, asiste a las Asambleas de la unidad académica cuando se le convoca.</label><br>
            <select id="question7" name="question7" required>
              <option value="">Seleccione una opción</option>
              <option value="No aplica">No aplica</option>
              <option value="1. Nunca">1. Nunca</option>
              <option value="2. A veces">2. A veces</option>
              <option value="3. Siempre">3. Siempre</option>
          </select>
      </div>
          
          <div class="question">
            <label for="question8">8. Participa activamente en comisiones, cuando se le convoca a formar parte de ellas.</label><br>
            <select id="question8" name="question8" required>
              <option value="">Seleccione una opción</option>
              <option value="No aplica">No aplica</option>
              <option value="1. Nunca">1. Nunca</option>
              <option value="2. A veces">2. A veces</option>
              <option value="3. Siempre">3. Siempre</option>
          </select>
      </div>
          
          <div class="question">
            <label for="question9">9. Colabora con la búsqueda de soluciones a problemas del estudiantado de la unidad académica o de la institución.</label><br>
            <select id="question9" name="question9" required>
              <option value="">Seleccione una opción</option>
              <option value="No aplica">No aplica</option>
              <option value="1. Nunca">1. Nunca</option>
              <option value="2. A veces">2. A veces</option>
              <option value="3. Siempre">3. Siempre</option>
          </select>
      </div>
          
          <div class="question">
            <label for="question10">10. Muestra apertura y respeto a la diversidad de criterios.</label><br>
            <select id="question10" name="question10" required>
              <option value="">Seleccione una opción</option>
              <option value="No aplica">No aplica</option>
              <option value="1. Nunca">1. Nunca</option>
              <option value="2. A veces">2. A veces</option>
              <option value="3. Siempre">3. Siempre</option>
          </select>
      </div>
          
          <div class="question">
            <label for="question11">11. En materia de evaluación, cumple con lo establecido en el Reglamento de Régimen Académico Estudiantil.</label><br>
            <select id="question11" name="question11" required>
              <option value="">Seleccione una opción</option>
              <option value="No aplica">No aplica</option>
              <option value="1. Nunca">1. Nunca</option>
              <option value="2. A veces">2. A veces</option>
              <option value="3. Siempre">3. Siempre</option>
          </select>
      </div>
          
          <div class="question">
            <label for="question12">12. Da trámite a reclamos y solicitudes debidamente presentados por el estudiantado.</label><br>
            <select id="question12" name="question12" required>
              <option value="">Seleccione una opción</option>
              <option value="No aplica">No aplica</option>
              <option value="1. Nunca">1. Nunca</option>
              <option value="2. A veces">2. Casi nunca</option>
              <option value="3. Siempre">3. A veces</option>
          </select>
      </div>
          
          <div class="question">
            <label for="question13">13. Cumple con las órdenes, instrucciones o circulares del superior/a jerárquico/a, emitidas dentro de su ámbito de competencia.</label><br>
            <select id="question13" name="question13" required>
              <option value="">Seleccione una opción</option>
              <option value="No aplica">No aplica</option>
              <option value="1. Nunca">1. Nunca</option>
              <option value="2. A veces">2. A veces</option>
              <option value="3. Siempre">3. Siempre</option>
          </select>
      </div>
          
          <div class="question">
            <label for="question14">14. Cuando es posible, implementa mejoras al curso a partir de que logra identificar las fortalezas y debilidades de este.</label><br>
            <select id="question14" name="question14" required>
              <option value="">Seleccione una opción</option>
              <option value="No aplica">No aplica</option>
              <option value="1. Nunca">1. Nunca</option>
              <option value="2. A veces">2. A veces</option>
              <option value="3. Siempre">3. Siempre</option>
          </select>
      </div>
          
          <div class="question">
            <label for="question15">15. Durante el desarrollo de actividades académicas e institucionales, respeta la integridad física o psicológica de las personas.</label><br>
            <select id="question15" name="question15" required>
              <option value="">Seleccione una opción</option>
              <option value="No aplica">No aplica</option>
              <option value="1. Nunca">1. Nunca</option>
              <option value="2. A veces">2. A veces</option>
              <option value="3. Siempre">3. Siempre</option>
          </select>
      </div>
          
          <div class="question">
            <label for="question16">16. Actúa con equidad de género, etnia, credo religioso e ideología.</label><br>
            <select id="question16" name="question16" required>
              <option value="">Seleccione una opción</option>
              <option value="No aplica">No aplica</option>
              <option value="1. Nunca">1. Nunca</option>
              <option value="2. A veces">2. A veces</option>
              <option value="3. Siempre">3. Siempre</option>
          </select>
      </div>
          
          <div class="question">
            <label for="question17">17. Respeta los derechos del estudiantado, según se estipula en los diferentes reglamentos.</label><br>
            <select id="question17" name="question17" required>
              <option value="">Seleccione una opción</option>
              <option value="No aplica">No aplica</option>
              <option value="1. Nunca">1. Nunca</option>
              <option value="2. A veces">2. A veces</option>
              <option value="3. Siempre">3. Siempre</option>
          </select>
      </div>
          
          <div class="question">
            <label for="question18">18. Cuando corresponde, cumple con las obligaciones y responsabilidades inherentes como profesor/a consejero/a.</label><br>
            <select id="question18" name="question18" required>
              <option value="">Seleccione una opción</option>
              <option value="No aplica">No aplica</option>
              <option value="1. Nunca">1. Nunca</option>
              <option value="2. A veces">2. A veces</option>
              <option value="3. Siempre">3. Siempre</option>
          </select>
      </div>
          
          <div class="question">
              <label for="question19">19. En resumen, utilizando una escala de 1 a 10, donde 1 es la nota más baja y 10 la más alta. ¿Qué nota le pondría a la labor académica desarrollada por esta persona en cuanto al ejercicio de la docencia?</label><br>
              <select id="question19" name="question19" required>
                  <option value="">Seleccione una opción</option>
                  <option value="1">1</option>
                  <option value="2">2</option>
                  <option value="3">3</option>
                  <option value="4">4</option>
                  <option value="5">5</option>
                  <option value="6">6</option>
                  <option value="7">7</option>
                  <option value="8">8</option>
                  <option value="9">9</option>
                  <option value="10">10</option>
              </select>
          </div>
      </div>
      <button type="submit">Guardar Evaluación</button>
  </form>
  <script src="logica.js"></script>
</body>
</html>
