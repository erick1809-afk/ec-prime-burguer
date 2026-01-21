<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title> EC PRIME BURGER | O Sabor Raiz</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <style>
        /* Cores e Estilo Geral */
        :root {
            --vermelho: #cc0000;
            --amarelo: #ffcc00;
            --escuro: #1a1a1a;
            --branco: #ffffff;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            padding: 0;
            background-color: var(--escuro);
            color: var(--branco);
        }

        header {
            background-color: var(--vermelho);
            padding: 20px;
            text-align: center;
            border-bottom: 5px solid var(--amarelo);
        }

        .logo h1 {
            margin: 0;
            font-size: 2.5em;
            color: var(--amarelo);
            text-shadow: 2px 2px #000;
        }

        /* Banner Principal */
        .hero {
            padding: 60px 20px;
            text-align: center;
            background: linear-gradient(rgba(0,0,0,0.7), rgba(0,0,0,0.7)), url('https://images.unsplash.com/photo-1571091718767-18b5b1457add?ixlib=rb-1.2.1&auto=format&fit=crop&w=1352&q=80');
            background-size: cover;
            background-position: center;
        }

        .hero h2 {
            font-size: 2em;
            color: var(--amarelo);
        }

        /* Seção Cardápio */
        .cardapio {
            padding: 40px 20px;
            max-width: 800px;
            margin: auto;
        }

        .cardapio h3 {
            text-align: center;
            color: var(--amarelo);
            font-size: 2em;
            border-bottom: 2px solid var(--vermelho);
            padding-bottom: 10px;
        }

        .item-burger {
            display: flex;
            justify-content: space-between;
            align-items: center;
            background: #2a2a2a;
            margin: 15px 0;
            padding: 15px;
            border-radius: 8px;
            border-left: 5px solid var(--amarelo);
        }

        .detalhes h4 {
            margin: 0;
            color: var(--amarelo);
            font-size: 1.3em;
        }

        .detalhes p {
            margin: 5px 0 0;
            font-size: 0.9em;
            color: #ccc;
        }

        .preco {
            font-weight: bold;
            color: var(--branco);
            font-size: 1.2em;
        }

        /* Botão WhatsApp Fixo */
        .btn-whatsapp {
            position: fixed;
            bottom: 30px;
            right: 30px;
            background-color: #25d366;
            color: white;
            padding: 15px 25px;
            border-radius: 50px;
            text-decoration: none;
            font-weight: bold;
            box-shadow: 0 4px 10px rgba(0,0,0,0.3);
            display: flex;
            align-items: center;
            gap: 10px;
            z-index: 1000;
            transition: transform 0.3s;
        }

        .btn-whatsapp:hover {
            transform: scale(1.1);
        }

        footer {
            text-align: center;
            padding: 30px;
            font-size: 0.8em;
            color: #888;
        }
    </style>
</head>
<body>

    <header>
        <div class="logo">
            <h1>EC PRIME BURGER</h1>
        </div>
    </header>

    <section class="hero">
        <h2>O melhor burger da região feito para você!</h2>
        <p>Ingredientes selecionados e sabor inigualável.</p>
    </section>

    <section class="cardapio">
        <h3>🍔 Nosso Cardápio</h3>

        <div class="item-burger">
            <div class="detalhes">
                <h4>Prime Salad</h4>
                <p>Pão brioche, blend 160g, queijo prato, alface, tomate e maionese da casa.</p>
            </div>
            <div class="preco">R$ 28,00</div>
        </div>

        <div class="item-burger">
            <div class="detalhes">
                <h4>Prime Bacon</h4>
                <p>Pão brioche, blend 160g, muito bacon crocante e cheddar cremoso.</p>
            </div>
            <div class="preco">R$ 32,00</div>
        </div>

        <div class="item-burger">
            <div class="detalhes">
                <h4>Prime Double</h4>
                <p>2 blends de 160g, dobro de queijo e cebola caramelizada.</p>
            </div>
            <div class="preco">R$ 42,00</div>
        </div>
    </section>

    <footer>
        &copy; 2024 EC PRIME BURGER - Todos os direitos reservados.
    </footer>

    <a href="https://wa.me/81997710825?text=Olá! Gostaria de fazer um pedido." class="btn-whatsapp" target="_blank">
        <i class="fab fa-whatsapp"></i> Peça pelo WhatsApp
    </a>

</body>
</html>
