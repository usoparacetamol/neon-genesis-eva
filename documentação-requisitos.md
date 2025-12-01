# Neon Genesis Eva

## Informações Gerais
---
- **Nome:** Neon Genesis Eva  
- **Gênero:** história, rpg  
- **Público alvo:** 9+  
- **Data:** 30/11/25  
- **Versão do documento:** 1.1

### Sinopse
Você se torna o protagonista, com seus próprios pensamentos, estilo de vida e ideais. Viva a história de Evangelion e tome suas próprias decisões, mudando o rumo da história.

### Ideia inicial
Jogo inspirado em Evangelion, história de escolhas parecida com a do anime, mecânicas com evas (missões para matar anjos ou explorar o mapa), interação com NPCs.

---

## Requisitos Funcionais (RF)

### RF 001 - Sistema de movimentação
**Desc:** movimentação e detalhes de animação

    - movimentação tridimensional  
    - cabeça se move junto com a câmera, animações detalhadas  
    - PC: WASD; Mobile: "bolinha"  
    - sistema de corrida e stamina para limitar movimentação prolongada  
    - animações de nado e parkour simples para exploração  

---

### RF 002 - Equipamentos e veículos
#### Evas
**Desc:** funcionamento e detalhes dos evas

    - movimentação detalhada e tridimensional  
    - será usado para as missões e fará parte da história  
    - poderá matar anjos ou explorar o mapa  
    - sistema de customização básica (cores, armas secundárias)  
    - barra de energia que limita tempo de uso do Eva

#### Automobilísticos
**Desc:** movimentação e detalhes dos veículos

    - carro da Misato  
    - velocidade: 50-70 studs/s  
    - avião utilizado pelo Gendo Ikari para ir a lugares distantes  
    - velocidade: 100-110 studs/s  
    - postos de gasolina para abastecer o carro

---

### RF 003 - Inimigos
#### Anjos
**Desc:** principais inimigos e detalhes dos anjos

    - principais inimigos  
    - praticamente todos igual ao anime, movimentação detalhada, serão minibosses  
    - os anjos principais serão bosses (ex: Ramiel)  
    - **Adição:** cada anjo terá padrão de ataque único (ex: laser, corpo a corpo, explosão)  
    - sistema de fases nos bosses (mudança de comportamento após perder vida)  

---

### RF 004 - Mapa
**Desc:** lugares e detalhamento do mapa

    - NeoTokyo 3 – tamanho considerável  
    - Apartamento da Misato – lugar de descanso/casa do jogador  
    - Cemitério/túmulo da Yui Ikari – cemitério dos personagens que morrerem durante o jogo  
    - Escola do Shinji – interação com amigos, busca de informações sobre o mundo de Evangelion e os evas  
    - NERV – base de operações/missões e interação com pilotos  
    - ciclo de dia/noite e clima dinâmico (chuva, sol, nublado)  
    - objetos interativos (portas, computadores, itens coletáveis)  

#### Mini Mapa
**Desc:** minimapa do jogo

    - mini mapa no canto superior da tela  
    - PC: abrir com tecla  
    - Mobile: pressionando encima  
    - ícones diferenciados para NPCs, inimigos e locais importantes  

#### Teleporte

    - cutscene com o avião do Gendo Ikari, usado para lugares distantes do mapa e missões  
    - sistema de desbloqueio de locais (teleporte só após visitar pela primeira vez)  

---

### RF 005 - NPCs
#### NPCs de missão

    - Misato Katsuragi, Gendo Ikari, Funcionários da NERV  

#### NPCs de história/interação

    - personagens principais do anime  

#### NPCs de ambientação

    - Funcionários da NERV  
    - alunos da escola do Shinji
    - civis  
    - **Adição:** sistema de afinidade/reputação com NPCs principais (decisões afetam relação)  
    - diálogos interativos com múltiplas escolhas  

---

## Requisitos Não Funcionais (RNF)

### RNF 001 - FPS
**Desc:** desempenho do jogo

    - deve rodar a 60 FPS nas configurações moderadas e em celulares  
    - rodar 120 FPS em configurações baixas e em PCs potentes  
    - **Adição:** resolução mínima suportada 720p, máxima 1080p  

---

### RNF 002 - Tutorial
**Desc:** tutorial de movimentação com Eva e detalhes do jogo

    - tutorial intuitivo e dinâmico, explicando como utilizar os evas e explorar o mundo  
    - dicas rápidas na tela durante missões (ex: "pressione E para interagir")  

---

### RNF 003 - Interface/UI
**Desc:** UI do jogo

    - deve seguir os parâmetros de resolução do usuário  
    - menus dinâmicos  
    - acessibilidade (legendas, contraste, tamanho de fonte ajustável)  

---

### RNF 004 - Expansões
**Desc:** expansão de conteúdo do jogo

    - sistema deve permitir expansão futura de mapas e NPCs  
    - compatibilidade retroativa (expansões não quebram saves antigos)  
    - possibilidade de eventos sazonais (Halloween, Natal, etc.)
