<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <title>Two Buttons</title>
    <style>
      body {
        display: flex;
        justify-content: center;
        align-items: center;
        height: 100vh;
        background-color: #f5f5f5;
        font-family: Arial, sans-serif;
      }
      .container {
        text-align: center;
      }
      .button {
        padding: 15px 30px;
        margin: 10px;
        font-size: 18px;
        background-color: #007bff;
        color: white;
        border: none;
        border-radius: 10px;
        cursor: pointer;
        transition: background-color 0.3s;
      }
      .button:hover {
        background-color: #0056b3;
      }
    </style>
  </head>
  <body>
    <div class="container">
      <button class="button" onclick="location.href='Batch 1.html'">
        Batch 1
      </button>
      <button class="button" onclick="location.href='Batch 2.html'">
        Batch 2
      </button>
    </div>
  </body>
</html>
