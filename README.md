<!DOCTYPE html>
<html>

<head>
    <head>
        <!-- ... outros elementos do cabeçalho ... -->
        <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css"
            integrity="sha384-..." crossorigin="anonymous">
    </head>
    
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Rafaela Carneiro Advogada - Escritório de Advocacia</title>
  
    <style>
        body {

             

            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #20303a;
            background-image: url('https://img.freepik.com/fotos-premium/estatua-da-justica-com-martelo-e-livro_157125-14226.jpg?w=740');
            background-size: cover;
            background-blur: 10px;
        }

        .header {
            background-color: #20303a;
            color: #ffffff;
            text-align: center;
            padding: 10px;
            border-radius: 0 0 20px 20px;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }

        .hero {
            background: rgba(0, 0, 0, 0.5);
            color: #ffffff;
            text-align: center;
            padding: 100px 0;
            border-radius: 10px;
        }

        .hero h1 {
            font-size: 36px;
            margin-bottom: 20px;
        }

        .hero p {
            font-size: 18px;
            margin-bottom: 40px;
        }

        .btn {
            display: inline-block;
            background-color: #ad1212;
            color: #fff;
            padding: 10px 20px;
            text-decoration: none;
            border-radius: 5px;
        }

        .services {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            align-items: center; /* Adicione esta linha */
            margin-top: 40px;
        }

        .service {
            width: 30%;
            margin: 20px;
            background-color: #d7d4ce;
            border-radius: 10px;
            box-shadow: 0px 2px 5px rgba(0, 0, 0, 0.1);
            overflow: hidden;
            text-align: center; /* Adicione esta linha */
        }

        .service img {

            
            width: 100%;
            height: 200px;
            object-fit: cover;
            border-radius: 10px 10px 0 0;
        }

        .service .details {
            padding: 20px;
        }

        .service h2 {
            font-size: 24px;
            margin-bottom: 10px;
            color: #4c4c4c;
        }

        .service p {
            font-size: 16px;
            color: #666;
        }
        
        .icon {
            display: flex;
            justify-content: center;
            align-items: center;
            font-size: 48px;
            margin-bottom: 10px;
            color: #ad1212;
        }

        .sidebar {
            background-color: #4c4c4c;
            color: #ffffff;
            border-radius: 20px;
            padding: 20px;
            margin-top: 20px;
        }

        .sidebar h2 {
            font-size: 24px;
            margin-bottom: 10px;
        }

        .sidebar p {
            font-size: 16px;
        }

        .contact-tabs {
            display: flex;
            justify-content: center;
            margin-top: 20px;
        }

        .contact-tab {
            flex: 1;
            padding: 10px;
            text-align: center;
            background-color: #ad1212;
            color: #fff;
            border-radius: 5px;
            margin: 0 5px;
            cursor: pointer;
        }

        .active {
            background-color: #4c4c4c;
        }
    </style>
</head>

<body>
    <div class="header">
        <h1>Rafaela Carneiro Advogada</h1>
       
       
    </div>
    <div class="container">
        <div class="hero">
            <h1><b>Defendendo Seus Direitos</b></h1>
            <p><strong>Comprometida em fornecer soluções legais excepcionais para nossos clientes.</strong></p>
            <a href="#services" class="btn">Nossos Serviços</a>
        </div>
        <div id="services" class="services">
            <div class="service">
                <img src="https://menezesemenezes.com.br/wp-content/uploads/elementor/thumbs/judges-gavel-divide-family-figures-p6onxw85najamc2n0ltavi2xcjv5h5an4wxblf4ocg.jpg" alt="Serviço 1"> width=""
                height=""



                <div class="details">
                    <div class="icon"><i class="fas fa-gavel"></i></div>
                    <h2>Direito de Família</h2>
                    <p>Divórcio, guarda, pensão alimentícia.</p>
                </div>
            </div>
            <div class="service">
                <img src="https://www.portalexamedeordem.com.br/wp-content/uploads/2023/02/Design-sem-nome-6-1200x675.png" alt="Serviço 2">
                <div class="details">
                    <div class="icon"><i class="fas fa-building"></i></div>
                    <h2>Direito Cível</h2>
                    <p>Contratos, sociedades, litígios.</p>
                </div>
            </div>
            <div class="service">
                <img src="https://marcosrdias.com.br/wp-content/uploads/2020/04/direitoadquiridotrabalhistaentendacomofunciona-300x151.jpeg" alt="Serviço 3">
                <div class="details">
                    <div class="icon"><i class="fas fa-briefcase"></i></div>
                    <h2>Direito Previdenciário</h2>
                    <p>Relações de trabalho, demissões, ações trabalhistas.</p>
                </div>
            </div>
        </div>
        <div class="sidebar">
            <h2>Preencha nosso Formulário</h2>
            <p>Preencha nosso formulário de contato para obter mais informações sobre nossos serviços e agendar uma consulta.</p>
            <a href="https://pt.surveymonkey.com/create/preview/?sm=9yEEF40BoFqvF3f8nRWABzCaubxloURRyR7ZbMVtyXw_3D" class="btn">Formulário de Contato</a>
        </div>
        <div
        <div class="contact-tabs">
            <div class="contact-tab active" onclick="openTab('email-tab')">Email</div>
            <div class="contact-tab" onclick="openTab('phone-tab')">Telefone</div>
            <div class="contact-tab" onclick="openTab('address-tab')">Endereço</div>
        </div>
        <div class="contact-content" id="email-tab">
            <h3>Email</h3>
            <p>Entre em contato via email: contato@rafaelacarneiroadvogada.com</p>
        </div>
        <div class="contact-content" id="phone-tab" style="display: none;">
            <h3>Telefone</h3>
            <p>Para falar conosco, ligue para: (XX) XXXX-XXXX</p>
        </div>
        <div class="contact-content" id="address-tab" style="display: none;">
            <h3>Endereço</h3>
            <p>Nosso escritório está localizado em: Rua dos Advogados, 123 - Centro</p>
        </div>
    </div>
    <script src="https://kit.fontawesome.com/a076d05399.js" crossorigin="anonymous"></script>
    <script>
        function openTab(tabName) {
            var tabs = document.getElementsByClassName("contact-tab");
            for (var i = 0; i < tabs.length; i++) {
                tabs[i].classList.remove("active");
            }
            document.getElementById(tabName).classList.add("active");

            var contents = document.getElementsByClassName("contact-content");
            for (var i = 0; i < contents.length; i++) {
                contents[i].style.display = "none";
            }
            document.getElementById(tabName + "-tab").style.display = "block";
            <div class="animated-image">
    <img src="animacao.gif" alt="Imagem Animada">
</div>

        }
    </script>
</body>

</html>
