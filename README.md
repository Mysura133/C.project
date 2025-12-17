# C.project
portfolio project
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Increment by 3 Counter</title>
    
    <!-- CSS is placed inside <style> tags in the <head> -->
    <style>
        body {
            font-family: Arial, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            background-color: #f0f2f5;
        }
        .container {
            text-align: center;
            background: white;
            padding: 2.5rem;
            border-radius: 12px;
            box-shadow: 0 8px 16px rgba(0, 0, 0, 0.1);
        }
        h1 { color: #444; }
        #counter-display {
            font-size: 4rem;
            font-weight: bold;
            color: #28a745; /* Green color for the count */
            margin: 1rem 0;
        }
        button {
            padding: 12px 24px;
            font-size: 1.1rem;
            background-color: #28a745;
            color: white;
            border: none;
            border-radius: 6px;
            cursor: pointer;
            transition: background 0.3s;
        }
        button:hover { background-color: #218838; }
    </style>
</head>
<body>

    <!-- HTML Structure -->
    <div class="container">
        <h1>Add +3 Counter</h1>
        <p id="counter-display">0</p>
        <button id="count-btn">Add 3</button>
    </div>

    <!-- JavaScript is placed inside <script> tags at the end of the <body> -->
    <script>
        let count = 0;
        const display = document.getElementById('counter-display');
        const button = document.getElementById('count-btn');

        button.addEventListener('click', () => {
            // Increment logic: adds 3 instead of 1
            count += 3; 
            display.textContent = count;
        });
    </script>

</body>
</html>
