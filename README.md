<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Simple HTML Page</title>
    <style>
        /* CSS Styling */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            display: flex;
            flex-direction: column;
            min-height: 100vh;
            background-color: #f4f4f9;
        }

        header {
            background-color: #4CAF50;
            color: white;
            padding: 1em;
            text-align: center;
        }

        main {
            flex: 1;
            padding: 2em;
            text-align: center;
        }

        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 1em;
            position: relative;
            bottom: 0;
            width: 100%;
        }

        h1 {
            color: #333;
        }

        p {
            color: #666;
            line-height: 1.6;
        }

        a {
            color: #4CAF50;
            text-decoration: none;
        }

        a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>

    <header>
        <h1>Welcome to My Simple Page</h1>
    </header>
<h1>Mrutunjaya Senapati</h1>
    <main>
        <h2>About This Page</h2>
        <p>This is a simple HTML page styled with CSS. It includes a header, a main content section, and a footer.</p>
        <p>Feel free to <a href="#">explore more</a> or modify this template as needed.</p>
    </main>

    <footer>
        &copy; 2024 Simple HTML Page. All rights reserved.
    </footer>

</body>
</html>
