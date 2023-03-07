<!DOCTYPE html>
<html>
  <head>
    <meta charset="UTF-8" />
    <title>React Tic-tac-toe</title>
    <link rel="stylesheet" href="styles.css" />
    <!-- Don't use this in production: -->
    <script src="https://unpkg.com/@babel/standalone/babel.min.js"></script>
  </head>

  <body>
    <h1>React Tic-tac-toe</h1>

    <!-- You will put our React component inside this div. -->
    <div id="root"></div>

    <!-- Load React. -->
    <script src="https://unpkg.com/react/umd/react.development.js" crossorigin></script>
    <script src="https://unpkg.com/react-dom/umd/react-dom.development.js" crossorigin></script>

    <!-- Load our React component. -->
    <script src="tictactoe.jsx" defer type="text/babel"></script>
  </body>
</html>
