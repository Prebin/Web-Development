#HTML

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hover Me!</title>
    <link rel="stylesheet" href="button.css" </head>

<body>
    <button>Hover Me</button>
</body>
</html>


#CSS

body {
    font-family: 'Roboto', sans-serif;
    display: flex;
    align-items: center;
    justify-content: center;
    height: 100vh;
    background-color: #151b29;
}

button {
    background: none;
    background-color: purple;
    border: 2px solid;
    padding: 1em 2em;
    font-size: 1em;
    transition: color 0.25s, border-color 0.25s, transform 0.25s;
}

button:hover {
    border-color: #f1ff5c;
    color: white;
    box-shadow: 0 0.5em 0.5em -0.4em;
    transform: translateY(-0.25em);
    cursor: pointer;