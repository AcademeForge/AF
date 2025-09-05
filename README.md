
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Redirect Page</title>
  <style>
    /* General reset */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      background: linear-gradient(135deg, #f8f9fa, #e9ecef);
      font-family: 'Inter', sans-serif;
      color: #333;
    }

    .card {
      background: white;
      padding: 3rem 4rem;
      border-radius: 20px;
      box-shadow: 0 10px 25px rgba(0,0,0,0.08);
      text-align: center;
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }

    .card:hover {
      transform: translateY(-5px);
      box-shadow: 0 15px 35px rgba(0,0,0,0.12);
    }

    h2 {
      font-size: 1.8rem;
      margin-bottom: 1rem;
      font-weight: 600;
      color: #222;
    }

    p {
      font-size: 1rem;
      margin-bottom: 2rem;
      color: #666;
    }

    button {
      background: #007bff;
      color: white;
      border: none;
      padding: 14px 32px;
      font-size: 1rem;
      font-weight: 500;
      border-radius: 50px;
      cursor: pointer;
      transition: all 0.3s ease;
      box-shadow: 0 5px 15px rgba(0,123,255,0.2);
    }

    button:hover {
      background: #0056b3;
      box-shadow: 0 8px 20px rgba(0,86,179,0.35);
      transform: translateY(-2px);
    }

    button:active {
      transform: translateY(0);
      box-shadow: 0 5px 12px rgba(0,86,179,0.25);
    }
  </style>
</head>
<body>
  <div class="card">
    <h2>You’re about to continue</h2>
    <p>Click below to proceed to the destination.</p>
    <button onclick="window.location.href='https://academeforge.github.io/AcademeForge/'">
      Continue →
    </button>
  </div>
</body>
</html>