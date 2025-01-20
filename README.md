<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Красивый текст</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            background-color: #f0f0f0;
        }
        #text-container {
            background-color: red;
            color: white;
            font-size: 2rem;
            padding: 20px 40px;
            border-radius: 15px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
            text-align: center;
            display: none; /* скрываем изначально */
        }
    </style>
</head>
<body>
    <div id="text-container">Это красивый текст на красном фоне!</div>

    <script>
        // Показываем текст через секунду
        setTimeout(() => {
            const textContainer = document.getElementById('text-container');
            textContainer.style.display = 'block';
        }, 1000);
    </script>
</body>
</html>
