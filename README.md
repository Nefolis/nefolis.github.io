<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Leaderboard</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #121212;
      color: #ffffff;
      text-align: center;
      padding: 50px;
    }
    h1 {
      color: #facc15;
    }
    table {
      margin: auto;
      border-collapse: collapse;
      width: 90%;
      max-width: 600px;
      background: #1f1f1f;
      border-radius: 10px;
      overflow: hidden;
    }
    th, td {
      padding: 15px;
      border-bottom: 1px solid #333;
    }
    th {
      background-color: #2d2d2d;
      color: #facc15;
    }
    tr:hover {
      background-color: #333;
    }
    footer {
      margin-top: 50px;
      color: #777;
      font-size: 0.9em;
    }
  </style>
</head>
<body>
  <h1>🏆 Game Leaderboard</h1>
  <table>
    <thead>
      <tr>
        <th>Rank</th>
        <th>Player</th>
        <th>Score</th>
      </tr>
    </thead>
    <tbody>
      <tr><td>1</td><td>PlayerOne</td><td>150</td></tr>
      <tr><td>2</td><td>PlayerTwo</td><td>120</td></tr>
      <tr><td>3</td><td>PlayerThree</td><td>100</td></tr>
      <tr><td>4</td><td>PlayerFour</td><td>90</td></tr>
      <tr><td>5</td><td>PlayerFive</td><td>75</td></tr>
    </tbody>
  </table>

  <footer>
    Powered by GitHub Pages
  </footer>
</body>
</html>
