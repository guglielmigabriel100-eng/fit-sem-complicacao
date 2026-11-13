# fit-sem-complicacao
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <title>Fit Sem Complicação</title>

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: Arial, Helvetica, sans-serif;
      background: #f6faf7;
      color: #1f2937;
      line-height: 1.6;
    }

    header {
      background: linear-gradient(135deg, #166534, #22c55e);
      color: white;
      padding: 70px 20px;
      text-align: center;
    }

    header h1 {
      font-size: 42px;
      margin-bottom: 15px;
    }

    header p {
      font-size: 19px;
      max-width: 650px;
      margin: auto;
    }

    .btn {
      display: inline-block;
      margin-top: 25px;
      padding: 15px 28px;
      background: white;
      color: #166534;
      text-decoration: none;
      font-weight: bold;
      border-radius: 10px;
      transition: 0.2s;
    }

    .btn:hover {
      transform: scale(1.03);
    }

    section {
      max-width: 1000px;
      margin: auto;
      padding: 55px 20px;
    }

    .intro {
      text-align: center;
    }

    .intro h2,
    .content h2 {
      font-size: 30px;
      color: #166534;
      margin-bottom: 15px;
    }

    .intro p {
      max-width: 750px;
      margin: auto;
      font-size: 17px;
    }

    .cards {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 20px;
      margin-top: 35px;
    }

    .card {
      background: white;
      padding: 28px 20px;
      border-radius: 15px;
      box-shadow: 0 5px 18px rgba(0,0,0