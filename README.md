<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Trivia Neoclásica</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f2f2f2;
      text-align: center;
      padding: 30px;
    }
    .quiz-container {
      background: white;
      padding: 20px;
      border-radius: 15px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.2);
      max-width: 600px;
      margin: auto;
    }
    h1 {
      color: #333;
    }
    .question {
      font-size: 20px;
      margin: 20px 0;
    }
    .option {
      background: #e0e0e0;
      padding: 10px;
      margin: 8px;
      border-radius: 10px;
      cursor: pointer;
      transition: 0.3s;
    }
    .option:hover {
      background: #d6d6d6;
    }
    .correct {
      background: #a5d6a7 !important;
    }
    .wrong {
      background: #ef9a9a !important;
    }
    #next-btn {
      margin-top: 20px;
      padding: 10px 20px;
      border: none;
      border-radius: 10px;
      background: #4caf50;
      color: white;
      font-size: 16px;
      cursor: pointer;
      display: none;
    }
    #result {
      font-size: 22px;
      font-weight: bold;
      margin-top: 20px;
    }
  </style>
</head>
<body>
  <div class="quiz-container">
    <h1>🎭 Trivia Neoclásica</h1>
    <div id="quiz">
      <div id="question" class="question"></div>
      <div id="options"></div>
