<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Parcerias | Ani Apps</title>
    <style>
        /* Layout básico */
        body {
            margin: 0;
            background-color: #000000e3;
            color: white;
            font-family: system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
            line-height: 1.5;
        }

        main {
            max-width: 960px;
            margin: 0 auto;
            padding: 1.5rem 1rem;
        }

      /*  h1 {
            text-align: center;
            margin-top: 1.5rem;
            text-transform: capitalize;
        }*/
        p {
            margin-bottom: 1.25rem;
        }

        .partner-list {
            list-style: disc inside;
            padding-left: 0;
            max-width: 780px;
            margin: 0 auto 2rem;
            text-align: left;
        }

        .partner-list li {
            margin-bottom: 1rem;
        }

        /* Navegação */
        .menu {
            display: flex;
            justify-content: space-between;
            align-items: center;
            background: #1e1e1e;
            padding: 15px 40px;
        }

        .logo {
            color: white;
            font-weight: 700;
            letter-spacing: 0.05em;
        }

        .menu ul {
            display: flex;
            list-style: none;
            margin: 0;
            padding: 0;
        }

        .menu ul li + li {
            margin-left: 20px;
        }

        .menu ul li a {
            text-decoration: none;
            color: white;
            font-size: 18px;
            transition: color 0.3s ease;
        }

        .menu ul li a:hover {
            color: #00bcd4;
        }

        @media (max-width: 640px) {
            .menu {
                padding: 12px 16px;
                flex-wrap: wrap;
            }

            .menu ul {
                width: 100%;
                justify-content: center;
                margin-top: 10px;
            }

            .menu ul li + li {
                margin-left: 12px;
            }
        }
        footer{
            text-align: center;
        }
    </style>
</head>
<body>
    <header>
        <nav class="menu" aria-label="Menu principal">
            <div class="logo">Ani Apps</div>
            <ul>
                <li><a href="aniapps.index.html">Home</a></li>
                <li><a href="contato.html">Contato</a></li>
                <li><a href="parcerias.html">Parcerias</a></li>
                <li><a href="sobre.html">Sobre</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section>
            <h1>Parcerias</h1>
            <p>
                Atualmente, a Ani-Apps tem parcerias com as seguintes plataformas de streaming de anime:
            </p>

            <ul class="partner-list">
                <li>
                    <strong>Crunchyroll</strong>: uma das maiores plataformas de streaming de anime do mundo,
                    oferecendo uma ampla variedade de séries e filmes. Conhecida por sua interface intuitiva
                    e conteúdo em alta qualidade.
                </li>
                <li>
                    <strong>Funimation</strong>: plataforma popular de streaming de anime, atualizada constantemente
                    com novos episódios e títulos exclusivos.
                </li>
                <li>
                    <strong>Yomura Animes</strong>: serviço de streaming com grande variedade de séries e filmes, com
                    interface leve e conteúdo em alta qualidade.
                </li>
            </ul>

            <p>
                A Ani-Apps está sempre buscando novas parcerias para oferecer aos seus usuários a melhor
                experiência possível, e continuará a expandir sua biblioteca de animes para atender às necessidades
                dos fãs de anime em todo o mundo.
            </p>
        </section>
    </main>

    <footer>
        <p>
            Apenas para fins de estudo: as parcerias citadas acima não são reais e não possuem vínculo com a Ani-Apps.
        </p>
    </footer>
</body>
</html>
