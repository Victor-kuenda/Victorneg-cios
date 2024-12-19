
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Victor Negócios - Venda de Carros</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            color: #333;
        }
        header {
            background-color: #4CAF50;
            color: white;
            padding: 20px;
            text-align: center;
        }
        nav {
            text-align: center;
            background: #333;
            padding: 10px;
        }
        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-size: 18px;
        }
        nav a:hover {
            text-decoration: underline;
        }
        section {
            padding: 20px;
        }
        .banner {
            background: url('https://via.placeholder.com/1200x400') no-repeat center;
            background-size: cover;
            height: 400px;
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            font-size: 30px;
            font-weight: bold;
        }
        .services, .contact {
            background-color: #f9f9f9;
            margin-top: 20px;
            padding: 20px;
            border-radius: 8px;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Victor Negócios</h1>
        <p>Especialistas em Venda e Auxílio de Carros</p>
    </header>
    <nav>
        <a href="#services">O que Oferecemos</a>
        <a href="#cars">Carros Disponíveis</a>
        <a href="#contact">Contato</a>
    </nav>
    <section class="banner">
        Encontre o Carro Perfeito com a Victor Negócios
    </section>
    <section id="services" class="services">
        <h2>O que Oferecemos</h2>
        <ul>
            <li>Venda de carros novos e seminovos</li>
            <li>Auxílio na venda do seu carro com tráfego pago</li>
            <li>Financiamento e arrendamento</li>
        </ul>
    </section>
    <section id="cars">
        <h2>Carros Disponíveis</h2>
        <p>Confira algumas opções:</p>
        <ul>
            <li>Ford EcoSport 2020 - R$ 70.000</li>
            <li>Chevrolet Onix 2019 - R$ 60.000</li>
            <li>Fiat Argo 2021 - R$ 65.000</li>
        </ul>
    </section>
    <section id="contact" class="contact">
        <h2>Contato</h2>
        <p>Entre em contato para mais informações:</p>
        <p>Email: contato@victornegocios.com</p>
        <p>Telefone/WhatsApp: (99) 99999-9999</p>
    </section>
    <footer>
        &copy; 2024 Victor Negócios. Todos os direitos reservados.
    </footer>
</body>
</html>

