# Task2
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Support Button</title>
  <style>
    
    #supportButton {
      background-color: #4CAF50;
      color: white;
      font-size: 18px;
      padding: 10px 20px; 
      border: none; 
      border-radius: 5px; 
      cursor: pointer; 
    }
  </style>
</head>
<body>

  <button id="supportButton" onclick="showAlert()">Get Support</button>

  <script>

    function showAlert() {
      alert("Support is on the way!");
    }
  </script>

</body>
</html>
