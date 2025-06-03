# Projeto-Agrinho
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Educação no Paraná</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            background-color: #f5f5f5;
            color: #333;
        }
        header {
            background: linear-gradient(135deg, #1e3c72, #2a5298);
            color: white;
            padding: 30px 0;
            text-align: center;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }
        .logo {
            width: 120px;
            height: auto;
        }
        h1 {
            margin: 10px 0 0;
        }
        nav {
            background-color: #e8491d;
            padding: 15px 0;
        }
        nav ul {
            display: flex;
            justify-content: center;
            list-style: none;
            padding: 0;
            margin: 0;
        }
        nav li {
            margin: 0 20px;
        }
        nav a {
            color: white;
            text-decoration: none;
            font-weight: bold;
            font-size: 18px;
            transition: all 0.3s ease;
        }
        nav a:hover {
            color: #ffd700;
        }
        .container {
            max-width: 1200px;
            margin: 30px auto;
            padding: 0 20px;
        }
        .destaque {
            background-color: white;
            border-radius: 8px;
            padding: 25px;
            margin-bottom: 30px;
            box-shadow: 0 3px 10px rgba(0,0,0,0.1);
        }
        .destaque h2 {
            color: #1e3c72;
            border-bottom: 2px solid #e8491d;
            padding-bottom: 10px;
        }
        .noticias {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
            gap: 25px;
            margin-top: 30px;
        }
        .noticia-card {
            background: white;
            border-radius: 8px;
            overflow: hidden;
            box-shadow: 0 3px 10px rgba(0,0,0,0.1);
            transition: transform 0.3s ease;
        }
        .noticia-card:hover {
            transform: translateY(-5px);
        }
        .noticia-img {
            width: 100%;
            height: 180px;
            object-fit: cover;
        }
        .noticia-conteudo {
            padding: 20px;
        }
        .noticia-conteudo h3 {
            margin-top: 0;
            color: #1e3c72;
        }
        footer {
            background-color: #1e3c72;
            color: white;
            text-align: center;
            padding: 25px 0;
            margin-top: 40px;
        }
        .dados-educacao {
            background-color: #f8f9fa;
            border-left: 5px solid #e8491d;
            padding: 15px;
            margin: 20px 0;
        }
    </style>
</head>
<body>
    <header>
        <img src="https://www.pr.gov.br/sites/default/files/emblema_parana.png" alt="Emblema do Paraná" class="logo">
        <h1>Educação no Estado do Paraná</h1>
        <p>Conheça as iniciativas e resultados da educação paranaense</p>
    </header>

    <nav>
        <ul>
            <li><a href="#sobre">Sobre</a></li>
            <li><a href="#estatisticas">Estatísticas</a></li>
            <li><a href="#programas">Programas</a></li>
            <li><a href="#noticias">Notícias</a></li>
            <li><a href="#contato">Contato</a></li>
        </ul>
    </nav>

    <div class="container">
        <section id="sobre" class="destaque">
            <h2>Sobre a Educação no Paraná</h2>
            <p>O Paraná se destaca nacionalmente por seu sistema educacional, com investimentos constantes em infraestrutura, formação de professores e inovação pedagógica. O estado possui uma rede de ensino robusta, atendendo desde a educação infantil até o ensino superior.</p>
            
            <div class="dados-educacao">
                <h3>Destaques da Educação Paranaense:</h3>
                <ul>
                    <li>Maior IDEB (Índice de Desenvolvimento da Educação Básica) entre os estados do Sul</li>
                    <li>Programa de Robótica presente em todas as escolas estaduais</li>
                    <li>Mais de 1 milhão de estudantes na rede pública estadual</li>
                    <li>Referência nacional em educação profissional e tecnológica</li>
                </ul>
            </div>
        </section>

        <section id="estatisticas" class="destaque">
            <h2>Estatísticas Educacionais</h2>
            <p>O Paraná mantém indicadores educacionais acima da média nacional, fruto de políticas públicas consistentes e investimentos estratégicos.</p>
            
            <div class="dados-educacao">
                <h3>Principais Números (2023):</h3>
                <ul>
                    <li><strong>Taxa de alfabetização:</strong> 98,5% (maior que a média nacional)</li>
                    <li><strong>IDEB Anos Iniciais:</strong> 6.8 (rede pública)</li>
                    <li><strong>IDEB Anos Finais:</strong> 5.4 (rede pública)</li>
                    <li><strong>Escolas estaduais:</strong> 2.100 unidades</li>
                    <li><strong>Professores na rede estadual:</strong> Mais de 80 mil</li>
                </ul>
            </div>
        </section>

        <section id="programas" class="destaque">
            <h2>Programas Educacionais</h2>
            <p>O Paraná implementa diversos programas inovadores para melhorar a qualidade do ensino:</p>
            
            <div class="noticias">
                <div class="noticia-card">
                    <img src="https://www.educacao.pr.gov.br/sites/default/arquivos_restritos/files/imagem/2023-04/robotica.jpg" alt="Estudantes com robô" class="noticia-img">
                    <div class="noticia-conteudo">
                        <h3>Robótica Paraná</h3>
                        <p>Programa pioneiro que levou o ensino de robótica para todas as escolas estaduais, formando estudantes para as profissões do futuro.</p>
                    </div>
                </div>
                
                <div class="noticia-card">
                    <img src="https://www.educacao.pr.gov.br/sites/default/arquivos_restritos/files/imagem/2022-11/lingua_inglesa.jpg" alt="Aula de inglês" class="noticia-img">
                    <div class="noticia-conteudo">
                        <h3>Inglês Paraná</h3>
                        <p>Iniciativa que oferece aulas de inglês gratuitas para estudantes do ensino médio, com metodologia inovadora e professores qualificados.</p>
                    </div>
                </div>
                
                <div class="noticia-card">
                    <img src="https://www.educacao.pr.gov.br/sites/default/arquivos_restritos/files/imagem/2023-03/escola_conectada.jpg" alt="Tablets em sala de aula" class="noticia-img">
                    <div class="noticia-conteudo">
                        <h3>Escola Conectada</h3>
                        <p>Distribuição de tablets e ampliação da conectividade nas escolas, garantindo inclusão digital para todos os estudantes.</p>
                    </div>
                </div>
            </div>
        </section>

        <section id="noticias" class="destaque">
            <h2>Notícias Recentes</h2>
            
            <div class="noticias">
                <div class="noticia-card">
                    <img src="https://www.educacao.pr.gov.br/sites/default/arquivos_restritos/files/imagem/2023-08/vestibular_2024.jpg" alt="Estudantes em prova" class="noticia-img">
                    <div class="noticia-conteudo">
                        <h3>Vestibular 2024 tem recorde de inscritos</h3>
                        <p>Processo seletivo para as universidades estaduais registrou mais de 120 mil inscrições.</p>
                    </div>
                </div>
                
                <div class="noticia-card">
                    <img src="https://www.educacao.pr.gov.br/sites/default/arquivos_restritos/files/imagem/2023-07/merenda_escolar.jpg" alt="Merenda escolar" class="noticia-img">
                    <div class="noticia-conteudo">
                        <h3>Paraná amplia investimento em merenda escolar</h3>
                        <p>Governo estadual aumenta em 15% os recursos para alimentação nas escolas.</p>
                    </div>
                </div>
                
                <div class="noticia-card">
                    <img src="https://www.educacao.pr.gov.br/sites/default/arquivos_restritos/files/imagem/2023-09/professores.jpg" alt="Professores em capacitação" class="noticia-img">
                    <div class="noticia-conteudo">
                        <h3>Capacitação para 10 mil professores</h3>
                        <p>Programa de formação continuada atenderá educadores de todas as disciplinas.</p>
                    </div>
                </div>
            </div>
        </section>
    </div>

    <footer id="contato">
        <h3>Secretaria de Estado da Educação do Paraná</h3>
        <p>Av. Água Verde, 2140 - Vila Izabel, Curitiba - PR, 80240-900</p>
        <p>Telefone: (41) 3340-1500 | E-mail: educacao@pr.gov.br</p>
        <p>&copy; 2023 Governo do Estado do Paraná. Todos os direitos reservados.</p>
    </footer>
</body>
</html>faça um codigo index.html sobrefaça um codigo index.html sobre
