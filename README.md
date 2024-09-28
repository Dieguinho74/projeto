<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Consultoria Pro - Sua Plataforma de Consultoria</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="logo">
            <h1>Consultoria Pro</h1>
        </div>
        <nav>
            <ul>
                <li><a href="#funcionalidades">Funcionalidades</a></li>
                <li><a href="#navegacao">Como Navegar</a></li>
                <li><a href="#clientes">Depoimentos</a></li>
                <li><a href="#contato">Contato</a></li>
            </ul>
        </nav>
    </header>

    <section class="hero">
        <div class="content">
            <h2>A Solução Completa para Consultorias</h2>
            <p>Agende reuniões, gere relatórios e tenha tudo o que precisa para gerenciar seus projetos em um só lugar.</p>
            <a href="#" class="cta-button">Comece Agora</a>
        </div>
        <div class="image">
            <img src="consultoria-app-mockup.png" alt="Mockup do App Consultoria">
        </div>
    </section>

    <section id="funcionalidades">
        <h2>Funcionalidades do App</h2>
        <div class="features">
            <div class="feature">
                <h3>Agendamento de Consultorias</h3>
                <p>Marque reuniões com nossos consultores a qualquer momento, diretamente pelo app.</p>
            </div>
            <div class="feature">
                <h3>Chat em Tempo Real</h3>
                <p>Converse com especialistas para tirar suas dúvidas e acompanhar o progresso dos projetos.</p>
            </div>
            <div class="feature">
                <h3>Relatórios Personalizados</h3>
                <p>Acompanhe o desenvolvimento do seu projeto com relatórios claros e objetivos.</p>
            </div>
            <div class="feature">
                <h3>Área do Cliente</h3>
                <p>Veja o andamento dos seus projetos, visualize documentos e faça pagamentos diretamente pelo app.</p>
            </div>
        </div>
    </section>

    <section id="navegacao">
        <h2>Como Navegar no App</h2>
        <div class="steps">
            <div class="step">
                <h3>Passo 1: Crie sua Conta</h3>
                <p>Registre-se com suas informações para ter acesso à área do cliente.</p>
            </div>
            <div class="step">
                <h3>Passo 2: Agende uma Consultoria</h3>
                <p>Escolha o horário que melhor se encaixa e marque uma reunião com o consultor especializado.</p>
            </div>
            <div class="step">
                <h3>Passo 3: Acompanhe o Projeto</h3>
                <p>Receba atualizações em tempo real e comunique-se diretamente com seu consultor pelo chat.</p>
            </div>
            <div class="step">
                <h3>Passo 4: Visualize Relatórios</h3>
                <p>Tenha acesso a relatórios personalizados com os detalhes e resultados do seu projeto.</p>
            </div>
        </div>
    </section>

    <section id="clientes">
        <h2>Depoimentos de Nossos Clientes</h2>
        <div class="testimonials">
            <div class="testimonial">
                <p>"A Consultoria Pro mudou a maneira como gerenciamos nossos projetos. Tudo é simples e rápido!"</p>
                <span>- Maria Silva, CEO de Empresa X</span>
            </div>
            <div class="testimonial">
                <p>"Nunca foi tão fácil acompanhar o progresso dos projetos com relatórios em tempo real."</p>
                <span>- João Santos, Diretor na Empresa Y</span>
            </div>
        </div>
    </section>

    <footer id="contato">
        <p>© 2024 Consultoria Pro. Todos os direitos reservados.</p>
        <!-- Botão de compartilhamento via WhatsApp -->
        <p>Compartilhe nosso site no WhatsApp: <a href="https://wa.me/?text=Confira%20a%20Consultoria%20Pro:%20https://www.consultoriapro.com" target="_blank">Clique aqui</a></p>
    </footer>

    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        header {
            background-color: #0044cc;
            padding: 20px;
            color: white;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        nav ul {
            list-style: none;
            display: flex;
            gap: 15px;
        }

        nav ul li a {
            color: white;
            text-decoration: none;
        }

        .hero {
            display: flex;
            justify-content: space-between;
            padding: 50px;
            background-color: #f5f5f5;
        }

        .hero h2 {
            font-size: 2.5em;
            margin-bottom: 20px;
        }

        .cta-button {
            background-color: #007bff;
            color: white;
            padding: 10px 20px;
            text-decoration: none;
            border-radius: 5px;
        }

        #funcionalidades, #navegacao {
            padding: 50px;
            background-color: #fff;
        }

        .features, .steps {
            display: flex;
            gap: 20px;
            justify-content: space-around;
        }

        .feature, .step {
            max-width: 300px;
        }

        .screenshots, .testimonials {
            display: flex;
            justify-content: space-around;
            padding: 50px;
        }

        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 20px;
        }
    </style>
</body>
</html>
