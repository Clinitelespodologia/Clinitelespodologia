<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sticky Header Example</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            font-family: Arial, sans-serif;
        }

        header {
            background-color: #333;
            color: #fff;
            padding: 10px 0;
            position: sticky;
            top: 0;
            z-index: 100;
        }

        .container {
            max-width: 800px;
            margin: 20px auto;
            padding: 0 20px;
        }

        /* Add some styles for content to create scrolling effect */
        p {
            line-height: 1.6;
            margin-bottom: 20px;
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <h1>My Sticky Header</h1>
        </div>
    </header>

    <div class="container">
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla ac libero id orci vestibulum semper.</p>
        <!-- Add more content here -->
    </div>

    <script>
        // JavaScript for additional functionality can be added here
    </script>
</body>
</html>
