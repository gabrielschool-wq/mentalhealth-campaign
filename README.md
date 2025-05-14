<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pizza Palace</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #fff8f0;
            color: #333;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #ff6347;
            color: white;
            text-align: center;
            padding: 1rem;
        }

        nav {
            background-color: #ffa07a;
            padding: 0.5rem;
            text-align: center;
        }

        nav a {
            color: white;
            margin: 0 1rem;
            text-decoration: none;
        }

        section {
            padding: 2rem;
        }

        h2 {
            color: #ff6347;
        }

        .staff-member {
            display: inline-block;
            text-align: center;
            margin: 1rem;
        }

        .staff-member img {
            width: 200px;
            height: 200px;
            object-fit: cover;
            border-radius: 10px;
            border: 2px solid #ff6347;
        }

        .uniform-img {
            width: 300px;
            height: auto;
            border-radius: 10px;
            border: 2px solid #ff6347;
        }

        footer {
            background-color: #ff6347;
            color: white;
            text-align: center;
            padding: 1rem;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>

<body>
    <header>
        <h1>Welcome to Pizza Palace</h1>
    </header>

    <nav>
        <a href="#about">About</a>
        <a href="#staff">Staff</a>
        <a href="#uniform">Uniform</a>
    </nav>

    <section id="about">
        <h2>About Us</h2>
        <p>Pizza Palace is your go-to spot for the best pizza in town. We combine fresh ingredients, traditional recipes,
            and excellent service to bring you a delightful dining experience.</p>
    </section>

    <section id="staff">
        <h2>Meet Our Staff</h2>
        <div class="staff-member">
            <img src="/mnt/data/DD143A92-13E8-42D4-B99A-4CB05D8DB9AD.jpeg" alt="Ben with cat ears">
            <p>Ben</p>
        </div>
        <div class="staff-member">
            <img src="/mnt/data/55E76CB0-7890-470F-BD78-8D30A59BB771.jpeg" alt="Max with glasses">
            <p>Max</p>
        </div>
        <div class="staff-member">
            <img src="/mnt/data/341D2D3D-562C-4BEB-B3DC-32276BD8639F.jpeg" alt="Gabriel with clown makeup">
            <p>Gabriel</p>
        </div>
    </section>

    <section id="uniform">
        <h2>Uniform</h2>
        <p>Our team wears comfortable and professional uniforms that represent our fun and friendly environment. Here is an example:</p>
        <img src="/mnt/data/341D2D3D-562C-4BEB-B3DC-32276BD8639F.jpeg" alt="Gabriel uniform example" class="uniform-img">
    </section>

    <footer>
        <p>&copy; 2025 Pizza Palace. All rights reserved.</p>
    </footer>
</body>

</html>
