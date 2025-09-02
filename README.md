<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
    <title>Lugares Turísticos do Paraná</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f8ff;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #006400;
            color: white;
            padding: 20px;
            text-align: center;
        }
        h1 {
            margin: 0;
        }
        section {
            padding: 20px;
            max-width: 1200px;
            margin: auto;
        }
        .lugar {
            margin-bottom: 40px;
            display: flex;
            flex-direction: column;
            align-items: center;
        }
        .lugar img {
            width: 100%;
            max-width: 800px;
            height: auto;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.2);
        }
        .descricao {
            margin-top: 15px;
            text-align: justify;
        }
        footer {
            background-color: #006400;
            color: white;
            text-align: center;
            padding: 15px;
            margin-top: 40px;
        }
        @media(max-width: 768px) {
            .lugar {
                width: 100%;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Lugares Turísticos do Paraná</h1>
        <p>Descubra os principais pontos turísticos do estado do Paraná</p>
    </header>
    <section>
        <!-- Lugar 1: Cataratas do Iguaçu -->
        <div class="lugar" id="cataratas-iguacu">
            <h2>Cataratas do Iguaçu</h2>
            <img src="https://images.unsplash.com/photo-1506744038136-46273834b3fb" alt="Cataratas do Iguaçu" />
            <div class="descricao">
                <p>Localizadas na fronteira entre Brasil e Argentina, as Cataratas do Iguaçu são uma das maiores e mais impressionantes quedas d'água do mundo, atraindo turistas de todos os cantos do planeta. O parque nacional oferece trilhas, passeios de barco e uma vista espetacular da natureza exuberante.</p>
            </div>
        </div>
        <!-- Lugar 2: Ilha do Mel -->
        <div class="lugar" id="ilha-do-mel">
            <h2>Ilha do Mel</h2>
            <img src="https://images.unsplash.com/photo-1521826027945-2a0f1ac1a0f8" alt="Ilha do Mel" />
            <div class="descricao">
                <p>A Ilha do Mel, localizada no litoral do Paraná, é conhecida por suas praias paradisíacas, trilhas ecológicas e vilas históricas. Um destino perfeito para quem busca contato com a natureza e tranquilidade.</p>
            </div>
        </div>
        <!-- Lugar 3: Parque Estadual do Guartelá -->
        <div class="lugar" id="parque-guartela">
            <h2>Parque Estadual do Guartelá</h2>
            <img src="https://images.unsplash.com/photo-1549924231-f129b911e442" alt="Parque Guartelá" />
            <div class="descricao">
                <p>Considerado um dos maiores cânions do Brasil, o Parque do Guartelá oferece trilhas, cachoeiras e vistas de tirar o fôlego. É ideal para amantes do ecoturismo e aventuras ao ar livre.</p>
            </div>
        </div>
        <!-- Lugar 4: Curitiba e seu centro histórico -->
        <div class="lugar" id="curitiba">
            <h2>Curitiba</h2>
            <img src="https://images.unsplash.com/photo-1549887534-7c68084424d7" alt="Centro de Curitiba" />
            <div class="descricao">
                <p>A capital do Paraná é famosa por seu planejamento urbano, parques e atrações culturais. Destaque para o Jardim Botânico, o Museu Oscar Niemeyer e o centro histórico com suas construções coloniais.</p>
            </div>
        </div>
    </section>
    <footer>
        <p>&copy; 2023 - Turismo Paraná. Todos os direitos reservados.</p>
    </footer>
</body>
</html>
