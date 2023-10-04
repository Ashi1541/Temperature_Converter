# Temperature_Converter
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Temperature Converter</title>
    <link rel="stylesheet" href="temp.css" />
  </head>
  <body>
    <div class="container">
      <h1 class="heading">Temperature Converter</h1>
      <div class="temp-container">
        <label for="Celcius">Celcius</label>
        <input
          onchange="computeTemp(event)"
          type="number"
          name="Celcius"
          id="Celcius"
          class="Celcius"
          placeholder="Enter Temperature"
        />
      </div>
      <div class="temp-container">
        <label for="Fahrenheit">Fahrenheit</label>
        <input
          onchange="computeTemp(event)"
          type="number"
          name="Fahrenheit"
          id="Fahrenheit"
          class="Fahrenheit"
          placeholder="Enter Temperature"
        />
      </div>
      <div class="temp-container">
        <label for="Kelvin">Kelvin</label>
        <input
          onchange="computeTemp(event)"
          type="number"
          name="Kelvin"
          id="Kelvin"
          class="Kelvin"
          placeholder="Enter Temperature"
        />
      </div>
    </div>

    <script src="temp.js"></script>
  </body>
</html>
