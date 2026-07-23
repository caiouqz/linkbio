🚀 Bem-vindo ao meu repositório!
Sou o Caio Vinicius, Full Stack Dev.

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

### 🎵 Como alterar a Música de Fundo

Para trocar a música que toca quando o usuário entra no site, procure pela tag `<audio>` (geralmente fica logo abaixo da tela de "splash-screen") no arquivo `index.html`. 

Altere o link dentro do atributo `src`:

```html
<!-- PASSO A PASSO PARA ALTERAR A MÚSICA -->
<audio id="bg-music" loop>
  
  <!-- Substitua o link abaixo pelo link direto do arquivo de áudio (.mp3) da sua escolha -->
  <!-- Dica: Sites como [pixabay.com/music](https://pixabay.com/music) ou bensound.com têm ótimas músicas gratuitas e sem direitos autorais! -->
  <source src="LINK_DA_SUA_MUSICA_AQUI.mp3" type="audio/mp3">

</audio>
