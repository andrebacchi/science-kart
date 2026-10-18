# Science Kart

Jogo de kart 3D estilo Mario Kart 64 com cientistas famosos como pilotos. Um único arquivo HTML (three.js r128), sem instalação: abra `index.html` no navegador.

**Versão piloto.** Pistas: Gaiola dos Ratos (treino) e Bancada de St. Mary's (Fleming, 1928), com modo reverso (entardecer), itens de ciência e modo batalha.

## Controles
Setas ou WASD para dirigir, Espaço ou Shift para derrapar, E ou X para usar o item, Q para o poder do piloto, V troca a câmera, M liga/desliga a música.

## Controle (joystick)
Funciona com controle padrão (Xbox, PlayStation, GameSir no celular etc.). Na corrida: analógico ou direcional vira, A ou RT aceleram, B ou LT freiam, RB ou X derrapam, LB usa o item, Y usa o poder, L3 olha para trás, R3 troca a câmera, Start pausa, Back liga o filtro N64. Nos menus: direcional ou analógico move o destaque, A confirma, B volta e Start abre o botão principal. Com controle conectado, os botões de toque somem.

## Música
A faixa da primeira pista (Gaiola dos Ratos) fica em `audio/gaiola-dos-ratos.mp3`, música original do projeto. Ela só toca na corrida: começa quando a contagem termina e acelera uns 10% na última volta (o tom não muda). A tecla M liga e desliga. Sem o arquivo, o jogo roda sem música.

## Instalar e QR code
Na tela inicial há o botão ‹ Bacchi Lab (volta ao hub), Instalar (PWA, funciona sem internet depois da primeira visita) e QR code para abrir no celular.

## Créditos dos sons
Efeitos sonoros (motor, derrapagem, impacto, moeda, quebra, disparo, cliques de menu) dos kits iniciais de Kenney (https://kenney.nl), licença MIT:
Starter-Kit-Racing, Starter-Kit-3D-Platformer, Starter-Kit-FPS, Starter-Kit-City-Builder, Starter-Kit-Match-3 (github.com/KenneyNL). Copyright (c) Kenney.
Os arquivos foram reduzidos (mono, mp3/wav comprimido) e o loop do motor foi emendado para não estalar.

## Notas técnicas
Gerado a partir de um fonte único com três.js r128, filtro N64 opcional. Arte própria dos personagens e pistas.
