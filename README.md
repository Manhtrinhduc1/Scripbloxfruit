<!DOCTYPE html>
<html>
<head>
  <title>Blox Fruits Menu</title>
  <style>
    body {
      background-color: #121212;
      font-family: Arial, sans-serif;
      color: white;
      text-align: center;
      padding-top: 50px;
    }
    .menu {
      background: #1f1f1f;
      padding: 20px;
      border-radius: 15px;
      width: 300px;
      margin: auto;
      box-shadow: 0 0 15px rgba(0, 255, 255, 0.2);
    }
    button {
      background: #00bcd4;
      border: none;
      padding: 10px 20px;
      margin: 10px;
      border-radius: 8px;
      color: white;
      font-size: 16px;
      cursor: pointer;
    }
    button:hover {
      background: #008c9e;
    }
  </style>
</head>
<body>

  <div class="menu">
    <h2>Blox Fruits Menu</h2>
    <button onclick="alert('Farm Level Activated')">Auto Farm</button><br>
    <button onclick="alert('Boss Raid Activated')">Start Raid</button><br>
    <button onclick="alert('Fruit Spawn Scan')">Scan for Fruit</button><br>
    <button onclick="alert('Settings Opened')">Settings</button>
  </div>

</body>
</html>
