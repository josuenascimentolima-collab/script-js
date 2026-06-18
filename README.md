# script-js
script
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AGRINHO 2026 | O Futuro da Agricultura</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <!-- HEADER -->
    <header>
        <div class="container">
            <h1>AGRINHO <span>2026</span></h1>
            
            <div id="menu-toggle">
                <span></span>
                <span></span>
                <span></span>
            </div>

            <nav id="nav-menu">
                <a href="#inicio">Início</a>
                <a href="#sobre">Sobre</a>
                <a href="#atividades">Atividades</a>
                <a href="#inscricao">Inscrição</a>
                <a href="#contato">Contato</a>
            </nav>
        </div>
    </header>

    <!-- HERO -->
    <section id="inicio" class="hero">
        <div class="hero-content">
            <h2>Plantando o Futuro</h2>
            <p>Participe do maior projeto educacional sobre agricultura, sustentabilidade e inovação do Brasil.</p>
            <a href="#inscricao" class="btn">Inscreva-se Agora</a>
        </div>
    </section>

    <!-- Outras seções podem ser adicionadas aqui -->

    <!-- Formulário de Inscrição -->
    <section id="inscricao">
        <div class="container">
            <h2>Faça sua Inscrição</h2>
            <form id="form-inscricao">
                <input type="text" placeholder="Nome completo" required>
                <input type="email" placeholder="E-mail" required>
                <input type="tel" placeholder="Telefone">
                <select required>
                    <option value="">Selecione sua escola</option>
                    <option value="1">Escola Municipal</option>
                    <option value="2">Escola Estadual</option>
                </select>
                <textarea placeholder="Por que quer participar?" rows="4"></textarea>
                <button type="submit">Enviar Inscrição 🌱</button>
            </form>
        </div>
    </section>

    <script src="script.js"></script>
</body>
</html>
