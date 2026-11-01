# 🐔 Galinha Atravessa a Rua

Jogo online estilo *Crossy Road / Frogger*: ajude a galinha a atravessar a rua desviando dos carros. Multinível, com som, e funciona no navegador e no celular.

## 🎮 Como jogar

- **Computador:** use as setas do teclado ou `WASD` para mover a galinha. `P` ou `Espaço` pausa.
- **Celular:** use os botões coloridos na tela (segure para mover continuamente) ou deslize o dedo sobre o jogo.
- Chegue à linha de chegada (faixa xadrez no topo) para completar o nível.
- A grama entre as pistas é segura — pare lá para esperar o momento certo.
- Você tem 3 vidas. Cada nível adiciona mais pistas, carros mais rápidos e caminhões.

## 🚀 Rodar localmente

Basta abrir o arquivo `index.html` em qualquer navegador moderno (Chrome, Edge, Firefox, Safari). Não precisa de servidor nem de instalação.

## 🌐 Publicar no GitHub Pages

1. Crie um repositório público no GitHub e faça upload do `index.html` (e deste `README.md`).
2. No repositório, vá em **Settings → Pages**.
3. Em **Source**, escolha **Deploy from a branch**, selecione a branch `main` e a pasta `/ (root)`. Clique em **Save**.
4. Aguarde cerca de 1–2 minutos. O jogo estará disponível em:
   `https://SEU-USUARIO.github.io/NOME-DO-REPOSITORIO/`

## 🛠️ Tecnologias

- HTML5 Canvas (gráficos do jogo)
- JavaScript puro (lógica, física, colisão)
- Web Audio API (sons e música sintetizados — sem arquivos de áudio externos)
- Tailwind CSS (via CDN) e Google Fonts (Fredoka)

Todo o jogo está em um único arquivo `index.html`, sem dependências para instalar.
