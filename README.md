<!DOCTYPE HTML>
<html>
<head>
    <title>conteudo-jogo</title>
    <meta charset="uft-8">
    
    <style>
        body {
            background-color: #121212;
            color: white; /*Isso aqui define o estilo do negócio*/
            font-family: Arial;
        }
    
        img {
            width: 250px; /*Essa budega faz o formato da imagem*/
            border-radius: 15px;
            
            display: block;
            margin-left: auto;
            margin-right: auto; /* E essa budega centraliza todas as imagens*/
            max-width: 100%;
            height: auto;
         }
          
        button {
            color: black;
            background-color: #F72119;
            width: 250px;
            height: 50px; /*E isso define o tamanho do botão*/
            font-size: 20px;
          
            display: block;        /* Transforma o botão em bloco */
            margin-left: auto;     /* Empurra para a direita */
            margin-right: auto;    /* Empurra para a esquerda */
        }
        button:hover {
            transform: scale(1.1); /*E isso aqui dá uma animaçãozinha no botão*/
            transition: 0.3s;
        }
            
        .game {
            background-color: #2b2b2b;
            padding: 20px;
            border-radius: 15px; /*Se eu colocar um "game" dentro de uma <div class= "#"> vai ficar com um estilo de card */
            margin-bottom: 30px;
            box-shadow: 0px 0px 10px black;
            
            transition: 0.3s;
        }
    
        h3 {
            text-align: center;
        }
        
        h1 {
            color: red;
            background-color: grey;
            text-align: center;
        }
        h2 {
            text-align: center; /*Isso aqui serve para centralizar o texto*/
        }
        .minecraft h2 {
            color: green;
            background-color: grey;
        }
        .marvelrivals h2 {
            color: red;
            background-color: grey;
        }
        .pokemon h2 {
            color: yellow;
            background-color: grey;
        }
        .bear h2 {
            color: #964B00;
            background-color: grey;
        }
        .brawlstars h2 {
            color: #FF0000;
            background-color: grey;
        }
        .unite h2 {
            color: blue;
            background-color: grey;
        }
        .peak h2 {
            color: white;
            background-color: grey;
        }
        .repo h2 {
            color: #FF6D2D;
            background-color: grey;
        }
        .webbing h2 {
            color: orange;
            background-color: grey;
        }
        .fall h2 {
            color: green;
            background-color: grey;
        }
        .pacman h2 {
            color: yellow;
            background-color: grey;
        }
        .bot h2 {
            color: blue;
            background-color: grey;
        }
        .go h2 {
            color: orange;
            background-color: grey;
        }
        .nyan h2 {
            color: magenta;
            background-color: grey;
        }
        .zombie h2 {
           color: green;
           background-color: grey;            
        }
        .hello h2 {
            color: brown;
            background-color: grey;
        }
        .guys h2 {
           color: #1F51FF;
           background-color: grey;            
        }
        .neighbor2 h2 {
            color: red;
            background-color: grey;
        }
        .zzz h2 {
            color: orange;
            background-color: grey;
        }
        .overcooked h2 {
            color: #7FFF00;
            background-color: grey;
        }
        .overcooked2 h2 {
            color: #CCFF00;
            background-color: grey;
        }
        .valley h2 {
            color: blue;
            background-color: grey;
        }
        .mask h2 {
            color: #9d00ff;
            background-color: grey;
        }
        .pacman256 h2 {
            color: yellow;
            background-color: grey;
        }
        .zombie2 h2 {
            color: green;
            background-color: grey;
        }
        .fluffy h2 {
            color: #FF033E;
            background-color: grey;
        }
        .animal h2 {
            color: #FFD700;
            background-color: grey;
        }
        .odyssey h2 {
            color: red;
            background-color: grey;
        }
        .kart h2 {
            color: #FF2C2C;
            background-color: grey;
        }
        .baldi h2 {
            color: #00FF00;
            background-color: grey;
        }
        .horizon h2 {
            color: blue;
            background-color: grey;
        }
        .mouse h2 {
            color: #FC4C02;
            background-color: grey;
        }
        input {
            text-align;
            font-size: 20px;
        }
    </style>
</head>
    <body>
        
        <h1>🕹 PIXELHUB 🎮</h1>
        <input type="text" id="pesquisa" placeholder="🔍 Procure um jogo" onkeyup="procurarJogo()">    
        <hr>
        
        <div class="game minecraft">
            <h2>Minecraft</h2>
                <img src="https://m.media-amazon.com/images/I/81gsSy5r13L.png" alt="minecraft Banner">
                    <h3>Sandbox | Aventura | RPG | Criativo</h3>
                <p>Minecraft é um jogo eletrônico sandbox de sobrevivência de 2011 desenvolvido e publicado pela desenvolvedora sueca Mojang Studios!</p>
                <p> <strong>🏆Avaliações gerais: 10/10🏆</strong> </p>
                <p> <strong>Avaliações: 5⭐</strong> </p>
                <a href="https://www.minecraft.net" target="_blank">
                    <button style="background-color: green">Ver site oficial</button>
                </a>
        </div>
        <div class= "game marvelrivals">
            <h2>Marvel Rivals</h2>
                <img src= "https://static.wikia.nocookie.net/marveldatabase/images/d/d0/Marvel_Rivals_key_art_2025_002.jpg/revision/latest?cb=20251207173730" alt= "marvel rivals banner">
                    <h3>Hero Shooter | Estratégico | Competitivo</h3>
                <p>Marvel Rivals é um jogo de tiro competitivo em equipes (hero shooter) gratuito e em terceira pessoa desenvolvido pela NetEase Games em parceria com a Marvel. Os jogadores controlam heróis e vilões icônicos com habilidades únicas em partidas PvP focadas em trabalho estratégico em equipe, sinergia de poderes e arenas destrutíveis.</p>
                <p> <strong>🏆Avaliações gerais: 8/10🏆</strong> </p>
                <p> <strong>Avaliações: 3.2⭐</strong> </p>
                <a href= "https://www.marvelrivals.com/m/" target= "_blank">
                    <button style= "background-color: red">Ver site oficial</button> 
                </a> 
        </div>
        <div class= "game pokemon">
            <h2>Pokémon TCG Pocket</h2>
                <img src= "https://dxkck1miuebqc.cloudfront.net/books/373915/preview/cover_front_big.jpg" alt="pokemon cartas ilustradas banner">
                    <h3>Criativo | Card game | Social</h3>
                <p>Pokémon TCG Pocket é um jogo mobile focado na coleta simplificada e batalhas rápidas de cartas Pokémon.</p>
                <p> <strong>🏆Avaliações gerais: 8/10🏆</strong> </p>
                <p> <strong>Avaliações: 4⭐</strong> </p>
                <a href= "https://tcgpocket.pokemon.com/en-us/" target= "_blank">
                    <button style="background-color: yellow">Ver site oficial</button>
                </a>
        </div>
        <div class= "game bear">
            <h2>Super Bear Adventure</h2>
                <img src= "https://m.media-amazon.com/images/I/71TWApDZTQL.png" alt= "super bear adventure banner">
                    <h3>Sandbox | Aventura | Ação | Exploração</h3>
                <p>Super Bear Adventure é um jogo de plataforma 3D inspirado em clássicos dos anos 90, onde você controla o urso Baaren para salvar um reino mágico.</p>
                <p> <strong>🏆Avaliações gerais: 8.5/10🏆</strong> </p>
                <p> <strong>Avalações: 4.5⭐</strong> </p>
                <a href= "https://www.nintendo.com/pt-br/store/products/super-bear-adventure-switch/?srsltid=AfmBOoqCBMY7gM82VDzhHKXxKt1CsIVPs-5LYzpMKGJpLE0QMIHL_JAM" target= "_blank">
                    <button style="background-color: #964B00">Ver site oficial</button>
                </a>
        </div>
        <div class= "game brawlstars">
            <h2>Brawl Stars</h2>
                <img src= "https://upload.wikimedia.org/wikipedia/en/thumb/b/b2/Brawl_Stars_logo_2025.svg/500px-Brawl_Stars_logo_2025.svg.png" alt= "brawl stars banner">
                    <h3>Competitivo | MOBA | Multiplayer | Casual</h3>
                <p>Brawl Stars é um jogo de tiro multiplayer rápido (3x3 e Battle Royale) desenvolvido pela Supercell, lançado globalmente em 2018 para iOS e Android. Com estilo cartoon e visão superior, os jogadores escolhem "Brawlers" com habilidades únicas para disputar modos competitivos, focado em trabalho de equipe, estratégia e reflexos rápidos.</p>
                <p> <strong>🏆Avaliações gerais: 8/10🏆</strong> </p>
                <p> <strong>Avaliações: 4⭐</strong> </p>
                <a href= "https://store.supercell.com/pt/brawlstars" target= "_blank">
                    <button style="background-color: #FF0000">Ver site oficial</button>
                </a>
        </div>
        <div class= "game unite">
            <h2>Pokémon UNITE</h2>
                <img src= "https://sm.ign.com/t/ign_ap/cover/p/pokemon-un/pokemon-unite_g4zw.1200.jpg" alt= "pokemon unite banner">
                    <h3>Ação | MOBA | Casual | Competitivo</h3>
                <p>Pokémon UNITE é um jogo gratuito de arena de batalha multijogador online (MOBA) estilo 5v5, desenvolvido pela TiMi Studios e The Pokémon Company.</p>  
                <p> <strong>🏆Avaliações gerais: 7.5/10🏆</strong> </p>
                <p> <strong>Avaliações: 3⭐</strong> </p>
                <a href= "https://unite.pokemon.com/en-us/" target= "_blank">
                    <button style="background-color: blue">Ver site oficial</button>
                </a> 
       </div>
       <div class= "game peak">
           <h2>PEAK</h2>
              <img src= "https://cdn.gameboost.com/igdb/covers/349524/coat49.jpg" alt= "peak banner">
                  <h3>Sandbox | Ação | Aventura | Simulador</h3>
              <p>PEAK é um jogo cooperativo de escalada e sobrevivência que se tornou um sucesso viral no PC (Steam) em 2025, conhecido por testar a amizade e exigir coordenação precisa entre os jogadores.</p>
              <p> <strong>🏆Avaliações gerais: 8.6/10🏆</strong> </p>
              <p> <strong>Avaliações: 4.2⭐</strong> </p>
              <a href="https://store.steampowered.com/app/3527290/PEAK/" target="_blank">
                  <button style="background-color: White">Ver site oficial</button>
              </a>
       </div>
       <div class="game repo ">
           <h2>REPO</h2>
              <img src= "https://upload.wikimedia.org/wikipedia/pt/e/ef/R.E.P.O..jpg" alt= "repo banner">
                   <h3>Coperativo | Sobrevivência | Terror </h3>
              <p>R.E.P.O. é um jogo de terror cooperativo (PvE) para até 6 jogadores, focado em exploração e extração física de itens valiosos em cenários assustadores, similar a Lethal Company.</p>
              <p> <strong>🏆Avaliações gerais: 7.5/10🏆</strong> </p>
              <p> <strong>Avaliações: 4.2⭐</strong> </p>
              <a href= "https://store.steampowered.com/app/3241660/REPO/" target="_blank">
                  <button style="background-color: #FF6D2D">Ver site oficial</button>
              </a>
       </div>
       <div class="game webbing">
           <h2>A webbing journey</h2>
              <img src= "https://cdn2.steamgriddb.com/logo_thumb/a00f813395b2a9678a4c9ee177ab95ae.png" alt="a webbing journey banner">
                   <h3>Aventura | Sandbox | Puzzle | Casual</h3>
              <p>A Webbing Journey é um charmoso jogo de aventura e sandbox 3D desenvolvido pela Fire Totem Games, onde você controla uma aranha fofa com a missão de ajudar seus humanos favoritos com tarefas domésticas.</p>
              <p> <strong>🏆Avaliações gerais: 9.5/10🏆</strong> </p>
              <p> <strong>Avaliações: 5⭐</strong> </p>
              <a href="https://store.steampowered.com/app/2073910/A_Webbing_Journey/" target="_blank">
                  <button style="background-color: orange">Ver site oficial</button>
              </a>
       </div>
       <div class="game fall">
           <h2>Human: Fall flat</h2>
              <img src= "https://sttc.gamersgate.com/images/product/human-fall-flat/cover-616-85cdba.jpg" alt= "human fall flat banner">
                  <h3>Puzzle | Coperativo | Plataforma | Indie</h3>
              <p>Human: Fall Flat é um hilariante jogo de plataformas com física num mundo de paisagens de sonho flutuantes. Cada nível de sonho fornece um novo ambiente para navegar, desde mansões, castelos e aventuras astecas até montanhas cobertas de neve, paisagens noturnas sinistras e instalações industriais.</p>
              <p> <strong>🏆Avaliações gerais: 8.5/10🏆</strong> </p>
              <p> <strong>Avaliações: 4⭐</strong> </p>
              <a href="https://store.steampowered.com/app/477160/Human_Fall_Flat/" target="_blank">
                  <button style="background-color: green">Ver site oficial</button>
              </a>
       </div>
       <div class= "game pacman">
           <h2>Pac-Man</h2>
              <img src="https://cdn.shortpixel.ai/spai/q_lossy+ret_img+to_auto/www.fizzcreations.com/wp-content/uploads/2020/01/PAC-MAN-Banner-768x385.jpg" alt= "pac man banner">
                  <h3>Ação | Arcade | Retrô | Casual</h3>
              <p>Pac-Man é um clássico jogo de labirinto de 1980 onde o jogador controla uma criatura amarela circular que deve comer todos os pontos ("Pac-Dots") em um labirinto.</p>
              <p> <strong>🏆Avaliações gerais: 8.5/10🏆</strong> </p>
              <p> <strong>Avaliações: 3.5⭐</strong> </p>
              <a href= "https://www.pacman.com/en/" target="_blank">
                    <button style="background-color: yellow">Ver site oficial</button>
              </a>
       </div>
       <div class="game bot">
           <h2>Astro Bot</h2>
              <img src="https://www.hoerzu.de/_default_upload_bucket/10251/image-thumb__10251__stage-content/AstroBot%202.bda1b6b0.webp" alt= "astro bot banner">
                  <h3>Plataforma 3D | Aventura | Ação | Casual</h3>
              <p>Astro Bot é um jogo eletrônico de plataforma de 2024 desenvolvido pela Team Asobi e publicado pela Sony Entertainment para o PlayStation 5.</p>
              <p> <strong>🏆Avaliações gerais: 9.5/10🏆</strong> </p>
              <p> <strong>Avaliações: 5⭐</strong> </p>
              <a href="https://www.playstation.com/pt-br/games/astro-bot/" target="_blank">
                  <button style= "background-color: blue">Ver site oficial</button>
              </a>
       </div>
       <div class= "game go">
           <h2>Pokémon GO</h2>
              <img src= "https://upload.wikimedia.org/wikipedia/en/thumb/0/0f/Pokemon_Go.svg/500px-Pokemon_Go.svg.png" alt= "pokemon go banner">
                  <h3>Free to Play | Competitivo | Casual </h3>
              <p>Pokémon GO é um jogo de realidade aumentada (RA) para dispositivos móveis (iOS e Android), lançado em 2016 pela Niantic, Nintendo e The Pokémon Company. </p>
              <p> <strong>🏆Avaliações gerais: 7.8/10🏆</strong> </p>
              <p> <strong>Avaliações: 4⭐</strong> </p>
              <a href="https://pokemongo.com/pt_br" target="_blank">
                  <button style="background-color: orange">Ver site oficial</button>
              </a>
       </div>
       <div class= "game nyan">
           <h2>Nyan Cat: Lost In Space</h2>
              <img src= "https://cdn.soft112.com/nyan-cat-lost-in-space/00/00/0F/PJ/00000FPJ38/Nyan-Cat---1.png" alt= "nyan cat banner">
                  <h3>Pixel Art | Plataforma 2D | Casual</h3>
              <p>Nyan Cat: Lost In Space é um jogo de plataforma arcade e corredor infindável (endless runner) onde você guia o famoso gato com corpo de Pop-Tart, deixando um rastro de arco-íris, pelo espaço sideral.</p>
              <p> <strong>🏆Avaliações gerais: 8.5/10🏆</strong> </p>
              <p> <strong>Avaliações: 2.5⭐</strong> </p>
              <a href= "https://store.steampowered.com/app/415420/Nyan_Cat_Lost_In_Space/" target="_blank">
                  <button style="background-color: magenta">Ver site oficial</button>
              </a>
       </div>
       <div class= "game zombie">
         <h2>Plants vs. Zombies</h2>
            <img src="https://upload.wikimedia.org/wikipedia/en/d/da/Plants_vs_Zombies_logo.png" alt= "plants vs zombies banner">
                <h3>Estratégico | Casual | Shooter</h3>
            <p>Plants vs. Zombies (PvZ) é uma franquia de jogos de estratégia criada por George Fan, onde plantas geneticamente modificadas defendem um quintal contra zumbis liderados pelo Dr. Edgar Zumbão (Zomboss).</p>
            <p> <strong>🏆Avaliações gerais: 8.5/10🏆</strong> </p>
            <p> <strong>Avaliações: 4.3⭐</strong> </p>
            <a href="https://www.ea.com/pt-br/games/plants-vs-zombies" target="_blank">
                <button style="background-color: green">Ver site oficial</button>
            </a>
       </div>
       <div class="game hello">
           <h2>Hello Neighbor</h2>
              <img src="https://m.media-amazon.com/images/I/71eMlFEtxiL._AC_UF1000,1000_QL80_FMwebp_DpWeblab_.jpg" alt= "hello neighbor banner">
                  <h3>Sandbox | Puzzle | Aventura</h3>
              <p>Hello Neighbor é um jogo de stealth horror (terror furtivo) e quebra-cabeça, onde o objetivo é invadir a casa do vizinho para descobrir segredos sombrios escondidos no porão. </p>
              <p> <strong>🏆Avaliações gerais: 9/10🏆</strong> </p>
              <p> <strong>Avaliações: 4.1⭐</strong> </p>
              <a href="https://www.helloneighborgame.com/" target="_blank">
                  <button style="background-color: brown">Ver site oficial</button>
              </a>
       </div>
       <div class="game neighbor2">
           <h2>Hello Neighbor 2</h2>
              <img src="https://m.media-amazon.com/images/I/81sLBtfELML._AC_UF1000,1000_QL80_FMwebp_.jpg" alt="hello neighbor 2 banner">
                  <h3>Terror furtivo | Aventura | Estratégico </h3>
              <p>Hello Neighbor 2 é um jogo de terror furtivo onde você controla Quentin, um jornalista investigativo na cidade de Raven Brooks.</p>
              <p> <strong>🏆Avaliações gerais: 7.2/10🏆</strong> </p>
              <p> <strong>Avaliações: 3.5⭐</strong> </p>
              <a href="https://www.helloneighbor2.com/" target="_blank">
                  <button style="background-color: red">Ver site oficial</button>
              </a>
       </div>
       <div class="game zzz">
           <h2>Zenless Zone Zero</h2>
              <img src="https://upload-os-bbs.hoyolab.com/upload/2024/12/03/430244924/681cd2991a995d9ea2461413dd9cb6d9_5732060706216801261.png?x-oss-process=image%2Fresize%2Cs_1000%2Fquality%2Cq_80%2Fauto-orient%2C0%2Finterlace%2C1%2Fformat%2Cwebp" alt="zenless zone zero banner">
                  <h3>RPG | Simulador | Ação | Gacha</h3>
               <p>Zenless Zone Zero (ZZZ) é um RPG de ação e fantasia urbana da HoYoverse, ambientado em um mundo pós-apocalíptico destruído por desastres sobrenaturais chamados "Esferas Negras" (Hollows).</p>
               <p> <strong>🏆Avaliações gerais: 8.5/10🏆</strong> </p>
               <p> <strong>Avaliações: 4⭐</strong> </p>
               <a href="https://zenless.hoyoverse.com/m/en-us/main" target="_blank">
                  <button style="background-color: orange">Ver site oficial</button>
               </a>
       </div>
       <div class= "game guys">
           <h2>Fall Guys</h2>
               <img src="https://assets.nintendo.com/image/upload/q_auto:best/f_auto/dpr_2.0/ncom/en_US/articles/2022/fall-guys-is-available-now-and-free-to-play/1920x1980_Switch_News_FallGuys" alt= "fall guys banner">
                   <h3>Ação | Plataforma | Party Royale | Causal</h3>
               <p>Fall Guys é um jogo party royale gratuito, multiplataforma e multijogador, onde até 60 competidores enfrentam pistas de obstáculos caóticas inspiradas em gincanas.</p>
               <p> <strong>🏆Avaliações gerais: 8/10🏆</strong> </p>
               <p> <strong>Avaliações: 4⭐</strong> </p>
               <a href= "https://www.fallguys.com/?lang=pt-BR" target="_blank">
                   <button style="background-color: #1F51FF">Ver site oficial</button>
               </a>
       </div>
       <div class="game overcooked">
           <h2>Overcooked</h2>
              <img src= "https://www.wog.ch/nas/cover_large/pcd/pcd_overcooked.jpg" alt= "overcooked banner">
           <h3>Ação | Simulação | Indie | Coperativo</h3>
              <p>Overcooked é um jogo caótico de simulação de culinária cooperativa, onde o objetivo principal é preparar, cozinhar e servir pratos específicos antes que os clientes fiquem impacientes.</p>
              <p> <strong>🏆Avaliações gerais: 9/10🏆</strong> </p>
              <p> <strong>Avaliações: </strong> </p>
              <a href="https://www.nintendo.com/pt-br/store/products/overcooked-special-edition-switch/?srsltid=AfmBOopMX2L7hFhiio0nOKbn0kLkoRE1ReFeXYW04o-WkkYt7PdfJDuY">
                  <button style="background-color: #7FFF00">Ver site oficial</button>
              </a>
       </div>
       <div class="game overcooked2">
           <h2>Overcooked! 2</h2>
              <img src="https://image.api.playstation.com/cdn/EP4064/CUSA10870_00/xWWemobK1Xc5DLDDWaeHgQPX4qUlNjYKEBVfjXfEwb3sIvR5aMNaFfJo9tfvhVDY.png?w=780&thumb=false" alt="overcooked 2 banner">
                  <h3>Simulação | Coperativo | Ação | Puzzle</h3>
              <p>Em Overcooked! 2, os jogadores retornam ao Reino da Cebola para salvar o mundo mais uma vez, agora enfrentando a ameaça dos "Pães Zumbis" (The Unbread). </p>
              <p> <strong>🏆Avaliações gerais: 9/10🏆</strong> </p>
              <p> <strong>Avaliações: 4.4⭐</strong> </p>
              <a href="https://store.steampowered.com/app/728880/Overcooked_2/" target="_blank">
                  <button style="background-color: #CCFF00">Ver site oficial</button>
              </a>
       </div>
       <div class="game valley">
           <h2>Stardew Valley</h2>
              <img src= "https://upload.wikimedia.org/wikipedia/en/f/fd/Logo_of_Stardew_Valley.png?utm_source=en.wikipedia.org&utm_campaign=parser&utm_content=thumbnail_unscaled" alt= "stardew valley banner">
                  <h3>Simulador | Sandbox | RPG | Exploração</h3>
              <p>Stardew Valley é um RPG de simulação de vida no campo onde você herda a fazenda decadente do seu avô. Armado com ferramentas velhas e poucas moedas, seu objetivo é transformar o terreno abandonado em um lar próspero, cultivando, criando animais, pescando e interagindo com os moradores da Vila Pelicanos.</p>
              <p> <strong>🏆Avaliações gerais: 10/10🏆</strong> </p>
              <p> <strong>Avaliações: 4.8⭐</strong> </p>
              <a href="https://www.stardewvalley.net/" target="_blank">
                  <button style="background-color: blue">Ver site oficial</button>
              </a>
       </div>
       <div class="game mask">
           <h2>Tomb of the Mask: Jogo Retro</h2>
              <img src="https://static.wikia.nocookie.net/tomb-of-the-mask/images/1/1a/TotM_Icon_%28Version_1.7.13%29.png/revision/latest?cb=20220730030729" alt="jogo retro banner">
                  <h3>Arcade | Puzzle | Casual | Estratégico</h3>
              <p>Tomb of the Mask é um jogo de arcade com labirintos verticais e uma variedade de inimigos e power-ups. No início do jogo, encontre uma máscara estranha que permitirá que você escale as paredes de forma fácil e rápida e embarque em uma aventura dinâmica de pixel!</p>
              <p> <strong>🏆Avaliações gerais: 8/10🏆</strong> </p>
              <p> <strong>Avaliações: 4.6⭐</strong> </p>
              <a href="https://tombofthemask.org/" target="_blank">
                  <button style="background-color: #9d00ff">Ver site oficial</button>
              </a>
       </div>
       <div class="game pacman256">
           <h2>PAC-MAN 256 - Endless Maze</h2>
              <img src="https://us-east-1-bandai.graphassets.com/AXzioIclSWilEjFtsMJPwz/Vy7gnwAPRXylN0fyNsxI" alt="pac man 256 banner">
                <h3>Arcade | Ação | Endless Runner | Casual</h3>
              <p>PAC-MAN 256 é um jogo de labirinto infinito onde você deve fugir da "Falha" (um enorme erro de código pixelado que consome a tela) enquanto come pastilhas e desvia de fantasmas.</p>
              <p> <strong>🏆Avaliações gerais: 8.5/10🏆</strong> </p>
              <p> <strong>Avaliações: 4.7⭐</strong> </p>
              <a href="https://www.bandainamcoent.com/games/pacman-256" target="_blank">
                  <button style="background-color: yellow">Ver site ofical</button>
              </a>
       </div>
       <div class="game zombie2">
           <h2>Plants vs Zombies 2</h2>
              <img src="https://macmagazine.com.br/wp-content/uploads/2013/07/12-PvZ2-logo.png" alt="plants vs zombies 2 banner">
                  <h3>Casual | MOBA | Puzzle | Sandbox</h3>
              <p>Plants vs. Zombies 2 é um jogo de estratégia em que você utiliza um exército de plantas com habilidades únicas para defender o seu cérebro de hordas de zumbis.</p>
              <p> <strong>🏆Avaliações gerais: 8/10🏆</strong> </p>
              <p> <strong>Avaliações: 4.2⭐</strong> </p>
              <a href="https://pvzge.com/en/" target="_blank">
                  <button style="background-color: green">Ver site oficial</button>
              </a>
       </div>
       <div class="game fluffy">
           <h2>Fluffy Fall</h2>
              <img src="https://fluffyfall.com/img/logo.png" alt="fluffy fall banner">
                  <h3>Casual | Arcade | Endless Runner 3D</h3>
              <p>Fluffy Fall é um jogo de corrida e desvio (runner infinito) onde você guia uma criatura adorável, macia e colorida por túneis e labirintos tridimensionais cheios de armadilhas mortais.</p>
              <p> <strong>🏆Avaliações gerais: 9.4🏆</strong> </p>
              <p> <strong>Avaliações: 4.7⭐</strong> </p>
              <a href="https://fluffyfall.com/" target="_blank">
                  <button style="background-color: #FF033E">Ver site oficial</button>
              </a>
       </div>
       <div class="game animal">
           <h2>Animal Crossing</h2>
                <img src="https://assets.nintendo.eu/image/upload/f_auto,c_limit,w_992,q_auto:low/MNS/NOE/70010000027620/1.1_2000x2000_ProductTile_Switch_AnimalCrossingNewHorizons_KeyVisual_enGB_v1_100q" alt="animal crossing banner">
                    <h3>Simulador de vida | Casual | Sandbox</h3>
                <p>Animal Crossing é uma famosa franquia de jogos de simulação de vida da Nintendo. Você assume o papel de um humano que se muda para uma comunidade habitada por animais antropomórficos.</p>
                <p> <strong>🏆Avaliações: 9/10🏆</strong> </p>
                <p> <strong>Avaliações: 3.9⭐</strong> </p>
                <a href="https://animalcrossing.nintendo.com/" target="_blank">
                    <button style="background-color: #FFD700">Ver site oficial</button>
                </a>
       </div>
       <div class="game odyssey">
           <h2>Super Mário Odyssey</h2>
                <img src="https://m.media-amazon.com/images/I/81nHzMe0lrL._AC_UF1000,1000_QL80_FMwebp_.jpg" alt="super mario odyssey banner">
                    <h3>Plataforma 3D | Aventura | Mundo aberto</h3>
                <p>Super Mario Odyssey é um jogo de plataforma 3D para Nintendo Switch onde Mario e seu novo aliado, Cappy, viajam pelo mundo a bordo da nave Odyssey. A missão da dupla é resgatar a Princesa Peach e Tiara, que foram sequestradas pelo vilão Bowser para realizar um casamento à força.</p>
                <p> <strong>🏆Avaliações: 10/10🏆</strong> </p>
                <p> <strong>Avaliações: 5⭐</strong> </p>
                <a href="https://supermario.nintendo.com/" target="_blank">
                   <button style="background-color: red">Ver site oficial</button>
                </a>
       </div>
       <div class="game baldi">
           <h2>Baldi's Basics in Education and Learning</h2>
              <img src="https://images.squarespace-cdn.com/content/v1/6491eb91bb711304dd556188/98633883-f9d3-4ea3-bfba-97b2f6bebb71/BaldisBasicsClassicRemastered_Screenshot+%281%29.png?format=750w" alt="baldis badic banner">
                  <h3>Puzzle | Casual | Sandbox</h3>
              <p>Baldi's Basics in Education and Learning (geralmente chamado apenas de Baldi's Basics) é um jogo independente de terror e sobrevivência que parodia os jogos educativos de computador dos anos 1990. O jogador precisa explorar uma escola, coletar cadernos e resolver equações matemáticas, enquanto tenta fugir de um professor assustador e humorístico.</p>
              <p> <strong>🏆Avaliações: 8/10🏆</strong> </p>
              <p> <strong>Avaliações: 4⭐</strong> </p>
              <a href="https://www.basicallygames.com/" target="_blank">
                  <button style="background-color: #00FF00">Ver site oficial</button>
              </a>
       </div>
       <div class="game kart">
           <h2>Super Mário Kart 8 Deluxe</h2>
              <img src="https://assets.nintendo.com/image/upload/ar_16:9,c_lpad,w_801/b_white/f_auto/q_auto/store/software/switch/70010000000153/de697f487a36d802dd9a5ff0341f717c8486221f2f1219b675af37aca63bc453" alt="Super mario kart 8 deluxe banner">
                  <h3>Arcade | Competitivo | Casual | Sandbox</h3>
              <p>Mario Kart 8 Deluxe é a edição definitiva do clássico jogo de corrida da Nintendo, lançada para o Nintendo Switch. O título reúne o jogo base do Wii U, todos os conteúdos adicionais (DLCs) originais e novidades exclusivas, oferecendo mais de 96 pistas e dezenas de personagens jogáveis.</p>
              <p> <strong>🏆Avaliações gerais: 9/10🏆</strong> </p>
              <p> <strong>Avaliações: 5⭐</strong> </p>
              <a href="https://mariokart8.nintendo.com/" target="_blank">
                  <button style="background-color: #FF2C2C">Ver site oficial</button>
              </a>
       </div>
       <div class="game horizon">
           <h2>Horizon: Zero Dawn</h2>
              <img src="https://image.api.playstation.com/vulcan/ap/rnd/202409/2716/b23608e3b46e3b1f6aebb78a4aa9b1bf4f72a1d99f42ed01.jpg?w=780&thumb=false" alt="horizon zero dawn banner">
                  <h3>Exploração | Mundo aberto | Aventura</h3>
              <p>Horizon Zero Dawn é um jogo de ação e RPG em mundo aberto ambientado num futuro pós-apocalíptico onde a Terra é dominada por criaturas robóticas gigantes. A história segue Aloy, uma caçadora exilada que busca descobrir a verdade sobre seu passado, suas origens e o mistério que causou a destruição da antiga civilização humana.</p>
              <p> <strong>🏆Avaliações gerais: 9.5/10🏆</strong> </p>
              <p> <strong>Avaliações: 4.5⭐</strong> </p>
              <a href="https://www.playstation.com/pt-br/horizon/" target="_blank">
                  <button style="background-color: blue">Ver site oficial</button>
              </a>
       </div>
       <div class="game mouse">
           <h2>MouseBot: Escape from CatLab</h2>
              <img src="https://shared.fastly.steamstatic.com/store_item_assets/steam/apps/1652710/header.jpg?t=1738820942" alt="mousebot banner">
                  <h3>Ação | Plataforma 3D | Arcade | Casual</h3>
              <p>MouseBot: Escape from CatLab é um jogo de plataforma e corrida estilo arcade desenvolvido pela Vector Unit. Você controla um simpático ratinho robótico que tenta escapar de um laboratório cheio de armadilhas criadas por gatos cientistas, testando seus reflexos enquanto coleta queijos.</p>
              <p> <strong>🏆Avaliações gerais: 7.5/10🏆</strong> </p>
              <p> <strong>Avaliações: 4.2⭐</strong> </p>
              <a href="https://store.steampowered.com/app/1652710/MouseBot_Escape_from_CatLab/" target="_blank">
                  <button style="background-color: #FC4C02">Ver site oficial</button>
              </a>
       </div>
        <script>
        alert("Bem-vindo(a)!!");
        
       function procurarJogo() {
    let busca = document.getElementById("pesquisa").value.toLowerCase();
    let jogos = document.querySelectorAll(".game");

    jogos.forEach(jogo => {
        let tituloElemento = jogo.querySelector("h2");
        if (!tituloElemento) return;

        let titulo = tituloElemento.innerText.toLowerCase();
        if (titulo.includes(busca)) {
            jogo.style.display = "";
        } else {
            jogo.style.display = "none";
        }
    });
}
        </script>
    </body>
</html>
