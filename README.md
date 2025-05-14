<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Staff Page</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f4f4f4;
      margin: 0;
      padding: 0;
    }

    header {
      background-color: #333;
      color: #fff;
      padding: 20px 0;
      text-align: center;
    }

    .container {
      width: 90%;
      max-width: 1000px;
      margin: 20px auto;
    }

    h2 {
      text-align: center;
      margin-top: 40px;
    }

    .staff-section {
      display: flex;
      justify-content: space-around;
      flex-wrap: wrap;
    }

    .staff-member {
      background-color: #fff;
      border: 1px solid #ddd;
      border-radius: 8px;
      width: 30%;
      margin: 10px;
      padding: 15px;
      text-align: center;
      box-shadow: 2px 2px 5px rgba(0,0,0,0.1);
    }

    .staff-member img {
      width: 100%;
      height: auto;
      border-radius: 8px;
    }

    .uniform-section {
      display: flex;
      justify-content: space-around;
      flex-wrap: wrap;
      margin-top: 40px;
    }

    .uniform-section img {
      width: 30%;
      border-radius: 8px;
      box-shadow: 2px 2px 5px rgba(0,0,0,0.1);
    }
  </style>
</head>
<body>
  <header>
    <h1>Our Staff</h1>
  </header>

  <div class="container">
    <h2>Meet the Team</h2>
    <div class="staff-section">
      <div class="staff-member">
        <img src="/mnt/data/DD143A92-13E8-42D4-B99A-4CB05D8DB9AD.jpeg" alt="Ben">
        <h3>Ben</h3>
        <p>Creative Lead</p>
      </div>
      <div class="staff-member">
        <img src="/mnt/data/55E76CB0-7890-470F-BD78-8D30A59BB771.jpeg" alt="Max">
        <h3>Max</h3>
        <p>Technical Director</p>
      </div>
      <div class="staff-member">
        <img src="/mnt/data/341D2D3D-562C-4BEB-B3DC-32276BD8639F.jpeg" alt="Gabriel">
        <h3>Gabriel</h3>
        <p>Event Coordinator</p>
      </div>
    </div>

    <h2>Uniform Examples</h2>
    <div class="uniform-section">
      <!-- Add uniform images here -->
      <img src="uniform1.jpg" alt="Uniform 1">
      <img src="uniform2.jpg" alt="Uniform 2">
      <img src="uniform3.jpg" alt="Uniform 3">
    </div>
  </div>
</body>
</html>

