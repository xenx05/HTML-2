# HTML-2
<!DOCTYPE html>
<html lang="ca">
<head>
  <meta charset="UTF-8">
  <title>Contingut del Llibre</title>
  <style>
    table {
      border-collapse: collapse;
      width: 70%;
      margin: 20px auto;
    }
    caption {
      font-size: 1.5em;
      margin-bottom: 10px;
      font-weight: bold;
    }
    th, td {
      border: 1px solid #333;
      padding: 8px;
      text-align: center;
    }
    thead {
      background-color: #f2f2f2;
    }
    tfoot {
      background-color: #e0e0e0;
      font-style: italic;
    }
  </style>
</head>
<body>

  <table>
    <caption>Taula de Contingut</caption>

    <!-- Definim amplàries de columnes -->
    <colgroup>
      <col style="width:15%">
      <col style="width:55%">
      <col style="width:30%">
    </colgroup>

    <!-- Capçalera de la taula -->
    <thead>
      <tr>
        <th colspan="3">Contingut del Llibre</th>
      </tr>
      <tr>
        <th>Capítol</th>
        <th>Títol del Capítol</th>
        <th>Pàgines</th>
      </tr>
    </thead>

    <!-- Cos de la taula -->
    <tbody>
      <!-- Capítol 1 amb dues seccions -->
      <tr>
        <td rowspan="2">1</td>
        <td>Introducció a la Història</td>
        <td>1-10</td>
      </tr>
      <tr>
        <td>Context Històric</td>
        <td>11-20</td>
      </tr>

      <!-- Capítol 2 amb una sola secció -->
      <tr>
        <td>2</td>
        <td>Els primers pobladors</td>
        <td>21-35</td>
      </tr>

      <!-- Capítol 3 amb tres seccions -->
      <tr>
        <td rowspan="3">3</td>
        <td>El naixement de les ciutats</td>
        <td>36-45</td>
      </tr>
      <tr>
        <td>L’arquitectura</td>
        <td>46-55</td>
      </tr>
      <tr>
        <td>La societat urbana</td>
        <td>56-65</td>
      </tr>

      <!-- Capítol 4 (només una fila) -->
      <tr>
        <td>4</td>
        <td>La cultura clàssica</td>
        <td>66-80</td>
      </tr>
    </tbody>

    <!-- Peu de la taula -->
    <tfoot>
      <tr>
        <td colspan="3">Fi de la taula de contingut</td>
      </tr>
    </tfoot>
  </table>

</body>
</html>

