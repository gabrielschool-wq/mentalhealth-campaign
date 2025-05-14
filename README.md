<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Camp Info</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f9f9f9;
      margin: 0;
      padding: 0;
    }
    header {
      background-color: #005792;
      color: white;
      padding: 20px;
      text-align: center;
    }
    section {
      padding: 20px;
    }
    h2 {
      color: #005792;
    }
    .staff {
      display: flex;
      flex-wrap: wrap;
      justify-content: space-around;
    }
    .staff-member {
      background: white;
      border: 1px solid #ddd;
      border-radius: 8px;
      margin: 10px;
      padding: 10px;
      width: 250px;
      box-shadow: 2px 2px 5px rgba(0,0,0,0.1);
      text-align: center;
    }
    .staff-member img {
      width: 100%;
      border-radius: 8px;
    }
    .uniform-section {
      display: flex;
      flex-wrap: wrap;
      justify-content: space-around;
      margin-top: 40px;
    }
    .uniform-section img {
      width: 30%;
      border-radius: 8px;
      box-shadow: 2px 2px 5px rgba(0,0,0,0.1);
      margin: 10px;
    }
  </style>
</head>
<body>
  <header>
    <h1>Camp Overview</h1>
  </header>
  <section>
    <h2>Meet the Staff</h2>
    <div class="staff">
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
  </section>
  <section>
    <h2>Uniform Examples</h2>
    <div class="uniform-section">
      <img src="uniform1.jpg" alt="Uniform 1">
      <img src="uniform2.jpg" alt="Uniform 2">
      <img src="uniform3.jpg" alt="Uniform 3">
    </div>
  </section>
</body>
</html>
