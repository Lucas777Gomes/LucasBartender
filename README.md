# LucasBartender
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Lucas Gomes</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #000; /* Preto para simular o terno */
            color: #fff; /* Texto branco para contraste */
        }
        header {
            text-align: center;
            padding: 20px;
            background-color: #111; /* Preto mais suave para o cabeçalho */
            border-bottom: 1px solid #555; /* Para dar um detalhe ao estilo */
        }
        header h1 {
            color: #fff;
            font-size: 2.5em;
            letter-spacing: 3px; /* Para dar um toque mais elegante */
        }
        header p {
            color: #ccc;
            font-size: 1.2em;
        }
        main {
            margin: 20px;
            padding: 20px;
            background-color: #222; /* Tom mais escuro para o conteúdo */
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.3);
        }
        .social-icons {
            position: fixed;
            top: 50%;
            right: 0;
            transform: translateY(-50%);
            display: flex;
            flex-direction: column;
        }
        .social-icons a {
            display: block;
            margin: 10px;
            width: 40px;
            height: 40px;
            background-color: #f44336; /* Vermelho para simular o suspensório */
            color: #fff;
            text-align: center;
            line-height: 40px;
            border-radius: 50%;
            transition: all 0.3s;
            text-decoration: none;
        }
        .social-icons a:hover {
            width: 60px;
            height: 60px;
            line-height: 60px;
            background-color: #f1f1f1; /* Efeito de cor clara ao passar o mouse */
            color: #333;
        }
        section {
            margin: 40px auto;
            max-width: 900px;
        }
        section h2 {
            text-align: center;
            color: #fff;
            font-size: 2em;
        }
        .portfolio {
            display: grid;
            grid-template-columns: repeat(4, 1fr);
            gap: 20px;
        }
        .portfolio .image-container {
            position: relative;
            width: 100%;
        }
        .portfolio img {
            width: 100%;
            height: auto;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            transition: transform 0.3s ease;
        }
        .portfolio img:hover {
            transform: scale(1.05);
        }
        .recipe {
            position: absolute;
            bottom: 0;
            left: 0;
            right: 0;
            background: rgba(0, 0, 0, 0.7);
            color: white;
            padding: 15px;
            font-size: 0.9em;
            display: none;
            border-radius: 0 0 8px 8px;
        }
        .image-container:hover .recipe {
            display: block;
        }
        .about-me {
            text-align: center;
            background-color: #333; /* Fundo escuro para destacar */
            padding: 20px;
            border-radius: 8px;
        }
        .about-me p {
            font-size: 1.2em;
            line-height: 1.6;
            color: #ccc; /* Cor mais clara para o texto */
        }
        .professional {
            background-color: #333;
            padding: 20px;
            border-radius: 8px;
            margin-top: 40px;
        }
        .professional p {
            color: #ccc;
            font-size: 1.2em;
            line-height: 1.6;
            text-align: center;
        }
    </style>
</head>
<body>
    <header>
        <h1>Lucas Gomes</h1>
        <p>Coquetelaria Clássica</p>
    </header>
    <main>
        <h2>Meu Portfólio</h2>
        <p>Aqui você encontrará uma seleção dos meus melhores coquetéis clássicos.</p>

        <section>
            <h2>Coquetéis Clássicos</h2>
            <div class="portfolio">
                <div class="image-container">
                    <img src="file:///C:/Users/pc2023/Desktop/Lucas%20bar/negroni_novo.jpg.jpeg" alt="Negroni">
                    <div class="recipe">
                        <strong>Negroni</strong><br>
                        30 ml Gin<br>
                        30 ml Vermute Rosso<br>
                        30 ml Campari<br>
                        Gelo e laranja para decorar
                    </div>
                </div>
                <div class="image-container">
                    <img src="https://via.placeholder.com/300x200?text=Boulevardier" alt="Boulevardier">
                    <div class="recipe">
                        <strong>Boulevardier</strong><br>
                        30 ml Bourbon<br>
                        30 ml Vermute Rosso<br>
                        30 ml Campari<br>
                        Gelo e casca de laranja
                    </div>
                </div>
                <div class="image-container">
                    <img src="https://via.placeholder.com/300x200?text=Martini" alt="Martini">
                    <div class="recipe">
                        <strong>Martini</strong><br>
                        60 ml Gin<br>
                        10 ml Vermute Seco<br>
                        Gelo e azeitona
                    </div>
                </div>
                <div class="image-container">
                    <img src="https://via.placeholder.com/300x200?text=Old+Fashioned" alt="Old Fashioned">
                    <div class="recipe">
                        <strong>Old Fashioned</strong><br>
                        50 ml Bourbon<br>
                        1 cubo de açúcar<br>
                        2 dashes de Angostura<br>
                        Gelo e casca de laranja
                    </div>
                </div>
                <div class="image-container">
                    <img src="https://via.placeholder.com/300x200?text=Margarita" alt="Margarita">
                    <div class="recipe">
                        <strong>Margarita</strong><br>
                        50 ml Tequila<br>
                        30 ml Cointreau<br>
                        20 ml Suco de limão<br>
                        Gelo e sal para a borda do copo
                    </div>
                </div>
                <div class="image-container">
                    <img src="https://via.placeholder.com/300x200?text=Manhattan" alt="Manhattan">
                    <div class="recipe">
                        <strong>Manhattan</strong><br>
                        50 ml Bourbon<br>
                        25 ml Vermute Doce<br>
                        2 dashes de Angostura<br>
                        Cereja para decorar
                    </div>
                </div>
                <div class="image-container">
                    <img src="https://via.placeholder.com/300x200?text=Whiskey+Sour" alt="Whiskey Sour">
                    <div class="recipe">
                        <strong>Whiskey Sour</strong><br>
                        50 ml Bourbon<br>
                        30 ml Suco de limão<br>
                        20 ml Xarope de açúcar<br>
                        Clara de ovo (opcional)
                    </div>
                </div>
                <div class="image-container">
                    <img src="https://via.placeholder.com/300x200?text=Mint+Julep" alt="Mint Julep">
                    <div class="recipe">
                        <strong>Mint Julep</strong><br>
                        60 ml Bourbon<br>
                        8 folhas de hortelã<br>
                        1 colher de chá de açúcar<br>
                        Gelo triturado
                    </div>
                </div>
                <div class="image-container">
                    <img src="https://via.placeholder.com/300x200?text=Sazerac" alt="Sazerac">
                    <div class="recipe">
                        <strong>Sazerac</strong><br>
                        50 ml Rye whiskey<br>
                        1 cubo de açúcar<br>
                        2 dashes de Peychaud's Bitters<br>
                        Absinto para revestir o copo
                    </div>
                </div>
                <div class="image-container">
                    <img src="https://via.placeholder.com/300x200?text=Tom+Collins" alt="Tom Collins">
                    <div class="recipe">
                        <strong>Tom Collins</strong><br>
                        50 ml Gin<br>
                        30 ml Suco de limão<br>
                        15 ml Xarope de açúcar<br>
                        Água com gás
                    </div>
                </div>
                <div class="image-container">
                    <img src="https://via.placeholder.com/300x200?text=Mai+Tai" alt="Mai Tai">
                    <div class="recipe">
                        <strong>Mai Tai</strong><br>
                        30 ml Rum escuro<br>
                        30 ml Rum claro<br>
                        15 ml Licor de amêndoa<br>
                        10 ml Suco de limão<br>
                        Xarope de groselha
                    </div>
                </div>
                <div class="image-container">
                    <img src="https://via.placeholder.com/300x200?text=Caipirinha" alt="Caipirinha">
                    <div class="recipe">
                        <strong>Caipirinha</strong><br>
                        50 ml Cachaça<br>
                        1 limão<br>
                        2 colheres de chá de açúcar<br>
                        Gelo
                    </div>
                </div>
            </div>
        </section>

        <!-- Seção sobre mim -->
        <section class="about-me">
            <h2>Sobre Mim</h2>
            <p>Olá, sou Lucas Gomes, bartender especializado em coquetéis clássicos e autorais. Minha paixão pela coquetelaria começou há [X anos] e, desde então, venho experimentando, criando e compartilhando minha arte. Com uma formação em [Formação] e experiência em diversos bares renomados, meu objetivo é sempre proporcionar experiências únicas para meus clientes.</p>
        </section>

        <!-- Seção profissional -->
        <section class="professional">
            <h2>Serviços Profissionais</h2>
            <p>Trabalho em eventos e festas, trazendo toda a minha experiência em coquetelaria clássica e autoral para oferecer momentos memoráveis aos meus clientes. Se você está planejando uma festa ou evento especial, posso criar uma experiência personalizada e única para os seus convidados.</p>
        </section>
    </main>

    <div class="social-icons">
        <a href="https://www.instagram.com/seu_perfil" title="Instagram">I</a> <!-- Substitua o link do Instagram aqui -->
        <a href="https://wa.me/SeuNumero" title="WhatsApp">W</a> <!-- Substitua o link do WhatsApp aqui -->
    </div>
</body>
</html>
