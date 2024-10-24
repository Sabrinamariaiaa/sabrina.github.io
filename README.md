<!DOCTYPE html>
<html lang="sv">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fiktivt Sminkmärke</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background-color: #FFC0CB;
            color: #333;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #800020;
            color: white;
            padding: 20px;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
            font-size: 18px;
        }
        .hero {
            background-image: url('hero-image.jpg');
            background-size: cover;
            background-position: center;
            height: 600px;
            display: flex;
            justify-content: center;
            align-items: center;
            color: white;
            text-align: center;
        }
        .hero h1 {
            font-size: 48px;
        }
        .product-grid {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 20px;
            padding: 50px;
        }
        .product {
            background-color: #fff;
            padding: 20px;
            border: 1px solid #ddd;
            text-align: center;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 20px;
        }
    </style>
</head>
<body>

<header>
    <div class="logo">Fiktivt Sminkmärke</div>
    <nav>
        <a href="#">Produkter</a>
        <a href="#">Om Oss</a>
        <a href="#">Blogg</a>
        <a href="#">Kontakt</a>
    </nav>
</header>

<div class="hero">
    <h1>Upptäck Skönheten I Detaljerna</h1>
    <button>Shoppa Nu</button>
</div>

<section class="product-grid">
    <div class="product">
        <img src="lipstick.jpg" alt="Läppstift">
        <h2>Läppstift</h2>
        <p>Pris: 199 kr</p>
        <button>Lägg i kundvagn</button>
