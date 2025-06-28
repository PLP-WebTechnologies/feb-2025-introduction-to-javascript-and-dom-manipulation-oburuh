<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DOM Manipulation</title>
    <style>
        #container {
            margin-top: 20px;
            border: 1px;
            padding: 10px;
        }
    </style>
</head>
<body>
    <h1 id="heading">This is my heading</h1>
    <button id="changeTextBtn">Change Text</button>

    <p id="styleText">This is text that changes dynamically upon clicking!</p>
    <button id="changeStyleBtn">Change Color</button>

    <div id="container">
        <p id="removable">This paragraph can be removed.</p>
    </div>
    <button id="addBtn">Add Paragraph</button>
    <button id="removeBtn">Remove Paragraph</button>

    <script src="script.js"></script>   
</body>
</html>
