# Temp.html
This is a temperature measurement
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Temperature Measurement</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
        }

        #temperature-display {
            font-size: 24px;
            margin: 20px;
        }
    </style>
</head>
<body>
    <h1>Temperature Measurement</h1>

    <div id="temperature-display">
        Temperature: <span id="temperature">N/A</span> °C
    </div>

    <button onclick="measureTemperature()">Measure Temperature</button>

    <script>
        function measureTemperature() {
            // Simulate temperature measurement (you can replace this with actual measurement logic)
            const temperatureValue = Math.floor(Math.random() * 30) + 10; // Random temperature between 10°C and 39°C

            // Display the measured temperature
            const temperatureDisplay = document.getElementById('temperature');
            temperatureDisplay.textContent = temperatureValue;
        }
    </script>
</body>
</html>
