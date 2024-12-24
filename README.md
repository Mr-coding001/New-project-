<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Temperature Converter</title>
    <style>
    </style>
</head>

<body>
    <div class="container">
        <h1>Temperature Converter</h1>
        <div class="converter">
            <input type="number" id="inputTemp" placeholder="Enter temperature" />
            <select id="inputUnit">
                <option value="celsius">Celsius</option>
                <option value="fahrenheit">Fahrenheit</option>
                <option value="kelvin">Kelvin</option>
            </select>
            <button onclick="convertTemperature()">Convert</button>
        </div>

        <div class="result">
            <p id="outputCelsius">Celsius: </p>
            <p id="outputFahrenheit">Fahrenheit: </p>
            <p id="outputKelvin">Kelvin: </p>
        </div>
    </div>
    </script>
</body>

</html>
