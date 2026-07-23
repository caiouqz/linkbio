🚀 Bem-vindo ao meu repositório!
Sou o Caio Vinicius, Full Stack Dev.

Um link-in-bio moderno, interativo e imersivo desenvolvido com **HTML5, CSS3 e JavaScript puro**. O projeto conta com efeitos visuais dinâmicos, animações de zoom refinadas, um player de música flutuante integrado com CD giratório e uma interface totalmente otimizada para desenvolvedores.

---

## ✨ Funcionalidades

- **Tela de Entrada (Splash Screen):** Tela ofuscada com efeito de desfoque (*backdrop-filter*) que aguarda o primeiro clique do usuário para iniciar os efeitos visuais e o player de áudio.
- **Efeitos Visuais de Fundo:** Animações contínuas de chuva e flocos de neve caindo suavemente.
- **Player de Música Flutuante:** 
  - CD giratório animado no canto inferior direito que roda apenas quando a música está ativa.
  - Barra de progresso interativa (permite avançar ou voltar o tempo da música).
  - Controles completos de *Play*, *Pause*, *Próxima* e *Anterior*.
  - Playlist customizável via código.
- **Efeitos de Zoom Interativo:** Transições e zooms fluidos aplicados no card de perfil, botões de redes sociais, caixas de especializações (Frontend, Backend, Ferramentas) e nos itens de tecnologia.
- **Design Responsivo:** Adaptado perfeitamente para telas de computadores, tablets e celulares.

---

## 🛠️ Tecnologias Utilizadas

- **HTML5** (Estruturação semântica)
- **CSS3** (Estilização avançada, Flexbox, Grid, Animações e Keyframes)
- **JavaScript (Vanilla)** (Lógica do player de áudio, controle de estados e gerador dinâmico de partículas/chuva/neve)

---

🌐 Como personalizar do seu jeito:


Se você gostou deste projeto e quer usá-lo para criar o seu próprio link bio, é muito simples! O código foi feito para ser facilmente editável. 

Abaixo estão as instruções de como adicionar suas próprias informações, novas redes sociais e habilidades.

### 📱 Como adicionar novas Redes Sociais (Ex: TikTok, LinkedIn)

Para adicionar um novo botão de rede social, procure no arquivo `index.html` pela div `<div class="profile-links">`. Copie o código abaixo e cole lá dentro:

```html
<!-- PASSO A PASSO PARA ADICIONAR REDE SOCIAL -->
<!-- 1. No href="", substitua pelo link do seu perfil (Ex: link do seu TikTok) -->
<a href="SEU_LINK_DO_PERFIL_AQUI" target="_blank" title="Nome da Rede">
  
  <!-- 2. Aqui dentro vai o código SVG do ícone da rede social. -->
  <!-- Dica: Você pode pegar ícones gratuitos em sites como feathericons.com ou iconify.design -->
  <svg viewBox="0 0 24 24" width="24" height="24" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
    <!-- Exemplo de ícone do TikTok -->
    <path d="M9 12a4 4 0 1 0 4 4V4a5 5 0 0 0 5 5v3a8 8 0 0 1-8-8H7v11a4 4 0 0 0 2 1z"></path>
  </svg>

</a>

💻 Como adicionar novas Habilidades / Ferramentas
Para adicionar uma nova caixinha com uma linguagem ou ferramenta que você domina, procure no index.html pelos blocos de <div class="skill-box">. Copie o código abaixo e cole dentro da categoria desejada (Frontend, Backend ou Ferramentas):

<!-- PASSO A PASSO PARA ADICIONAR HABILIDADE -->
<div class="skill-item">
  
  <!-- 1. No src="", apague e coloque o link da imagem/logo da tecnologia -->
  <!-- Dica: O site devicon.dev tem os links de todas as logos de programação! -->
  <img src="LINK_DA_FOTO_AQUI.png" alt="Nome da Tecnologia"> 
  
  <!-- 2. Escreva o nome da tecnologia logo após a tag da imagem -->
  Nome da Tecnologia
  
</div>

👤 Como alterar a Foto de Perfil principal
Procure pela tag de imagem principal no início do código e substitua o link:

<!-- Substitua o link atual pelo link da sua foto do GitHub ou qualquer outra imagem da internet -->
<img src="LINK_DA_SUA_FOTO_AQUI" alt="Seu Nome" class="profile-img"> 

## 🎵 Como Adicionar e Editar Músicas no Player

Para gerenciar as músicas do player flutuante, abra o código do projeto e localize a constante `playlist` na seção de scripts do JavaScript. Você pode adicionar quantos itens quiser seguindo este modelo:

```javascript
const playlist = [
  {
    title: "Nome da Música",
    artist: "Nome do Artista",
    src: "caminho-do-arquivo.mp3" // ou um link direto da web (.mp3)
  },
  {
    title: "Outra Música",
    artist: "Outro Artista",
    src: "[https://seu-link-de-audio.com/musica.mp3](https://seu-link-de-audio.com/musica.mp3)"
  }
];

 
</audio>

---------------------------------------------------------------------------------------------------

<div align="center">

  <!-- Subtítulo pequeno opcional -->
  <p><code>A M U L T I - P U R P O S E &nbsp; L I N K B I O</code></p>

  <!-- Linha principal com o Cérebro e o nome LINKBIO -->
  <h1>
    <img src="https://api.iconify.design/lucide:brain.svg?color=white&width=45" alt="Cérebro" style="vertical-align: middle; margin-right: 10px;" />
    <span style="color: #FFFFFF; font-family: monospace; letter-spacing: 2px;">LINKBIO</span>
  </h1>

  <!-- Assinatura menor embaixo -->
  <p style="font-size: 12px; color: #888888; margin-top: -10px;">
    by: Caio
  </p>

</div>



