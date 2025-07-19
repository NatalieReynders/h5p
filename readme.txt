<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Interactieve H5P</title>
    https://cdn.jsdelivr.net/npm/h5p-standalone@1.3.0/dist/main.bundle.js
    https://cdn.jsdelivr.net/npm/h5p-standalone@1.3.0/dist/styles.css
    <style>
        body {
            font-family: Arial, sans-serif;
            padding: 20px;
        }
        #h5p-container {
            width: 100%;
            max-width: 800px;
            margin: auto;
        }
    </style>
</head>
<body>
    <h1>Mijn H5P Interactieve Content</h1>
    <div id="h5p-container"></div>

    <script>
        new H5PStandalone.H5P(document.getElementById('h5p-container'), 'image-hotspots-75790.h5p');
    </script>
</body>
</html>
