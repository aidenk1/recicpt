---
layout: default
permalink: /home
title: homepage
---
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Homepage</title>
    <style>
        body {
            background: linear-gradient(45deg, #000000, #2c2c2e);
            height: 100vh;
            font-family: 'Montserrat', sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            flex-direction: column;
            color: white;
        }

        .container {
            display: flex;
            flex-direction: column;
            align-items: center;
        }

        input[type="text"] {
            padding: 10px;
            border-radius: 5px;
            border: none;
            margin-bottom: 20px;
            width: 300px;
            font-size: 16px;
        }

        button {
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            background-color: #4CAF50;
            color: white;
            font-size: 16px;
            cursor: pointer;
            transition: background-color 0.3s ease;
        }

        button:hover {
            background-color: #45a049;
        }
    </style>
</head>

<body>

    <div class="container">
        <h1>Welcome to Recipe Search</h1>
        <input type="text" placeholder="Search for recipes...">
        <button onclick="searchRecipes()">Search</button>
        <a href="upload.html"><button>Upload Your Own Recipe</button></a>
    </div>

    <script>
        function searchRecipes() {
            // Implement search logic here
            console.log("Searching for recipes...");
        }
    </script>

</body>

</html>
