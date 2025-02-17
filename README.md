<!DOCTYPE html>
<html>
<head>
    <title></title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
            padding: 20px;
            background-color: #f4f4f4;
        }
        .container {
            max-width: 400px;
            margin: auto;
            background: white;
            padding: 20px;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        label {
            font-weight: bold;
        }
        input, button {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
        }
        button {
            background-color: #28a745;
            color: white;
            border: none;
        }
    </style>
</head>
<body>
    <div class="container">
        <h2></h2>
        <form>
            <label for="name">:</label>
            <input type="text" id="name" name="name" required>
            
            <label for="book">:</label>
            <input type="text" id="book" name="book" required>
            
            <button type="submit"></button>
        </form>
    </div>
</body>
</html>

