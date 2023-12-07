<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>hDC Host</title>
    <!-- Ícones -->
    <link   rel="stylesheet" 
            href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css"
            integrity="sha512-DTOQO9RWCH3ppGqcWaEA1BIZOC6xxalwEsw9c2QQeAIftl+Vegovlnee1c9QX4TctnWMn13TZye+giMm8e2LwA=="
            crossorigin="anonymous"    
            referrerpolicy="no-referrer" />

    <!-- Estilos -->
    <link rel="stylesheet" href="/css/style.css">
</head>

<body>
    <div class="container">
        <div class="navbar-container">
            <nav>
                <a href="#">
                    <img src="/imagens/hdchostlogo.png" alt="hDC Host" class="logo"/>
                </a>
                <ul class="navbar-items">
                    <li>
                        <a href="#">Home</a>
                    </li>
                    <li>
                        <a href="#">Preços</a>
                    </li>
                    <li>
                        <a href="#">Contato</a>
                    </li>
                    <li>
                        <a href="#" class="default-btn">Entrar</a>
                    </li>
                </ul>
            </nav>
        </div>
        <main>
            <div class="main-banner">
                <h1>hDC Host</h1>
                <p>Os melhores serviços para projetos de todos os tamanhos!</p>
            </div>
            <section class="services-container">
                <ul>
                    <li class="teste">
                        <i class="fas fa-shield-alt"></i>
                        <h3>Segurança</h3>
                        <p>Conte com o host confiavel e com uma segurança essencial para hospedar seu site </p>
                    </li>
                    <li>
                        <i class="fas fa-rocket"></i>
                        <h3>Performance</h3>
                        <p>A melhor velocidade para o seu site </p>
                    </li>
                    <li>
                        <i class="fas fa-comments"></i>
                        <h3>Suporte</h3>
                        <p>Suporte 24 horas para tirar dúvidas </p>
                    </li>
                </ul>
            </section>
            <section class="pricing-container">
                <h2>Planos e preços</h2>
                <p>Selecione o plano que atenda a suas necessidades</p>
                <div class="plans-container">
                    <div class="plan">
                      <ul>
                        <li class="price">R$15/mês</li>
                        <li class="plan-name">Básico</li>
                        <li>2GB de espaço</li>
                        <li>1 Subdomínios</li>
                        <li>25 contas de e-mail</li>
                        <li>C-panel</li>
                        <li>Suporte 24/7</li>
                        <li class="plan-btn">Saber mais</li>
                      </ul>
                    </div>
                    <div class="plan">
                      <ul>
                        <li class="price">R$30/mês</li>
                        <li class="plan-name">Dedicado</li>
                        <li>5GB de espaço</li>
                        <li>10 Subdomínios</li>
                        <li>50 contas de e-mail</li>
                        <li>C-panel</li>
                        <li>Suporte 24/7</li>
                        <li class="plan-btn">Saber mais</li>
                      </ul>
                    </div>
                    <div class="plan">
                      <ul>
                        <li class="price recommended">R$50/mês</li>
                        <li class="plan-name">Dedicado Plus</li>
                        <li>10GB de espaço</li>
                        <li>10 Subdomínios</li>
                        <li>100 contas de e-mail</li>
                        <li>C-panel</li>
                        <li>Suporte 24/7</li>
                        <li class="plan-btn recommended">Saber mais</li>
                      </ul>
                    </div>
                    <div class="plan">
                      <ul>
                        <li class="price">R$100/mês</li>
                        <li class="plan-name">Cloud</li>
                        <li>20GB de espaço</li>
                        <li>20 Subdomínios</li>
                        <li>200 contas de e-mail</li>
                        <li>C-panel</li>
                        <li>Suporte 24/7</li>
                        <li class="plan-btn">Saber mais</li>
                      </ul>
                    </div>
                  </div>
            </section>
            <section class="searchdomain-container">
                <h2>Qual domínio você quer para o seu site?</h2>
                <p>Verifique se o domínio está disponível</p>
                <form >
                    <input 
                        type="text" 
                        name="domain" 
                        id="domain" 
                        placeholder="Digite o domínio desejado">
                    <input 
                        type="submit" 
                        value="Procurar domínio">
                </form>
            </section>
            <section class="contact-container">
                <h2>Mande uma mensagem</h2>
                <p>Envie sua mensagem, em até 4 horas um especialista entrará em contato</p>
                <form>
                    <input 
                        type="text" 
                        name="name" 
                        id="name" 
                        placeholder="Seu nome">
                    <input 
                        type="email" 
                        name="email" 
                        id="email" 
                        placeholder="Seu email">
                    <textarea name="message" id="message" placeholder="Descreva o que você precisa ou o seu projeto..."></textarea>
                    <input type="submit" value="Enviar">
                </form>
            </section>
        </main>
        <footer>
            <p>hDC Host @2023 joão </p>
        </footer>
    </div>
</body>

</html>
