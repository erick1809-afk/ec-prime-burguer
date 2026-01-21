<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>EC PRIME BURGER | Experiência Gourmet</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <style>
        /* Estilo Moderno e Minimalista */
        :root {
            --primaria: #ffca28; /* Dourado */
            --secundaria: #d32f2f; /* Vermelho Profundo */
            --fundo: #0a0a0a;
            --card: #161616;
            --texto: #f5f5f5;
        }

        body {
            font-family: 'Inter', sans-serif;
            margin: 0;
            background-color: var(--fundo);
            color: var(--texto);
            line-height: 1.6;
        }

        /* Cabeçalho Flutuante */
        header {
            padding: 30px 20px;
            text-align: center;
            background: linear-gradient(to bottom, #1a1a1a, transparent);
        }

        .logo-box h1 {
            margin: 0;
            letter-spacing: 4px;
            font-size: 1.8rem;
            color: var(--primaria);
            text-transform: uppercase;
        }

        /* Banner de Impacto */
        .hero {
            height: 40vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            background: linear-gradient(rgba(0,0,0,0.6), rgba(0,0,0,0.6)), url('https://images.unsplash.com/photo-1586816001966-79b736744398?auto=format&fit=crop&w=1000&q=80');
            background-size: cover;
            background-position: center;
            border-bottom: 2px solid var(--secundaria);
        }

        /* Cardápio Estilo Lista Gourmet */
        .menu-container {
            padding: 40px 20px;
            max-width: 600px;
            margin: auto;
        }

        .menu-title {
            text-align: center;
            color: var(--primaria);
            font-size: 1.5rem;
            margin-bottom: 40px;
            text-transform: uppercase;
            border-left: 4px solid var(--secundaria);
            border-right: 4px solid var(--secundaria);
            display: inline-block;
            width: 100%;
            box-sizing: border-box;
        }

        .burger-card {
            background: var(--card);
            padding: 20px;
            margin-bottom: 20px;
            border-radius: 12px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            transition: 0.3s;
            border: 1px solid #222;
        }

        .info h3 {
            margin: 0;
            color: var(--primaria);
            font-size: 1.2rem;
        }

        .info p {
            margin: 8px 0 0;
            font-size: 0.85rem;
            color: #aaa;
        }

        .price {
            font-size: 1.1rem;
            font-weight: bold;
            color: var(--texto);
        }

        /* CTA WhatsApp */
        .whatsapp-fixed {
            position: fixed;
            bottom: 25px;
            left: 50%;
            transform: translateX(-50%);
            background-color: #25d366;
            color: #fff;
            padding: 16px 32px;
            border-radius: 100px;
            text-decoration: none;
            font-weight: bold;
            box-shadow: 0 10px 20px rgba(0,0,0,0.4);
            display: flex;
            align-items: center;
            gap: 12px;
            width: 80%;
            max-width: 300px;
            justify-content: center;
        }

        footer {
            text-align: center;
            padding: 80px 20px 120px;
            font-size: 0.7rem;
            letter-spacing: 1px;
            color: #444;
        }
    </style>
</head>
<body>

    <header>
        <div class="logo-box">
            <h1>EC PRIME</h1>
        </div>
    </header>

    <section class="hero">
        <p style="color: var(--primaria); margin-bottom: 0;">ARTESANAL & SUCULENTO</p>
        <h2 style="margin-top: 5px; font-size: 2.2rem;">BURGER REAL</h2>
    </section>

    <div class="menu-container">
        <span class="menu-title">Seleção Prime</span>

        <div class="burger-card">
            <div class="info">
                <h3>Smash Original</h3>
                <p>Pão australiano, 2 carnes de 80g, queijo cheddar e cebola caramelizada.</p>
            </div>
            <div class="price">R$ 26</div>
        </div>

        <div class="burger-card">
            <div class="info">
                <h3>Prime Gorgon</h3>
                <p>Pão brioche, blend 160g, creme de gorgonzola e rúcula fresca.</p>
            </div>
            <div class="price">R$ 34</div>
        </div>

        <div class="burger-card">
            <div class="info">
                <h3>The Boss</h3>
                <p>Pão brioche, 2 blens de 160g, bacon prime e molho especial.</p>
            </div>
            <div class="price">R$ 45</div>
        </div>
    </div>

    <footer>
        &copy; 2024 EC PRIME BURGER | QUALIDADE EM CADA MORDIDA
    </footer>

    <a href="https://wa.me/5581997710825?text=Quero um Burger Prime!" class="whatsapp-fixed" target="_blank">
        <i class="fab fa-whatsapp"></i> FAZER PEDIDO
    </a>

</body>
</html>
