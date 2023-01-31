# Calculator
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="style.css" />
    <title>Calculator</title>
  </head>

  <body>
    <div class="container">
      <div class="calculator dark">
        <div class="theme-toggler active">
          <i class="toggler-icon"></i>
        </div>
        <div class="display-screen">
          <div id="display"></div>
        </div>
        <div class="buttons">
          <table>
            <tr>
              <td><button class="btn-operator" id="clear">C</button></td>
              <td><button class="btn-operator" id="/">&divide;</button></td>
              <td><button class="btn-operator" id="*">&times;</button></td>
              <td><button class="btn-operator" id="backspace">Del</button></td>
            </tr>
            <tr>
              <td><button class="btn-number" id="7">7</button></td>
              <td><button class="btn-number" id="8">8</button></td>
              <td><button class="btn-number" id="9">9</button></td>
              <td><button class="btn-operator" id="-">-</button></td>
            </tr>
            <tr>
              <td><button class="btn-number" id="4">4</button></td>
              <td><button class="btn-number" id="5">5</button></td>
              <td><button class="btn-number" id="6">6</button></td>
              <td><button class="btn-operator" id="+">+</button></td>
            </tr>
            <tr>
              <td><button class="btn-number" id="1">1</button></td>
              <td><button class="btn-number" id="2">2</button></td>
              <td><button class="btn-number" id="3">3</button></td>
              <td rowspan="2">
                <button class="btn-equal" id="equal">=</button>
              </td>
            </tr>
            <tr>
              <td><button class="btn-operator" id="(">(</button></td>
              <td><button class="btn-number" id="0">0</button></td>
              <td><button class="btn-operator" id=")">)</button></td>
            </tr>
          </table>
        </div>
      </div>
    </div>
    <script src="script.js"></script>
  </body>
</html>
