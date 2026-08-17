# Spotfy 🎵

Landing page inspirada no Spotify, desenvolvida com **HTML5**, **CSS3** e **Bootstrap 5**. O projeto reproduz a estética de uma página inicial do Spotify responsiva, com carousel de destaque, seções de apresentação de recursos e um rodapé completo.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap_5-7952B3?style=flat&logo=bootstrap&logoColor=white)

## 📸 Demonstração

![Preview do projeto](imagens/printH1.png) 
![Preview do projeto](imagens/printH2.png)
![Preview do projeto](imagens/printH3.png)

## ▶️ Demonstração no youtube
<a href="https://www.youtube.com/watch?v=RYAch08K-i8">
  <img src="https://img.youtube.com/vi/RYAch08K-i8/maxresdefault.jpg" width="700" alt="Assistir à demonstração">
</a>


## 📋 Sobre o projeto

O Spotfy é um projeto front-end estático que simula a página de entrada do Spotify, com foco em:

- Layout responsivo utilizando o grid system do Bootstrap 5;
- Navegação fixa (`fixed-top`) com menu colapsável (hambúrguer) para dispositivos móveis;
- Carousel de destaque em tela cheia, com troca automática de slides;
- Seções alternadas de imagem/texto apresentando funcionalidades do app;
- Seção de plano Premium com imagens rotacionadas via CSS;
- Rodapé com links institucionais e redes sociais.

## Funcionalidades

- **Carousel dinâmico**: apresenta diferentes chamadas ("Música grátis para todos", "As melhores playlists", "Seus artistas favoritos") com botões de ação personalizados;
- **Menu responsivo**: colapsa em telas menores utilizando o componente `navbar` do Bootstrap;
- **Cards de recursos**: grid de imagens e textos destacando músicas, playlists e novos lançamentos;
- **Chamada para o Premium**: seção dedicada com imagens de mockups de celular e botão de conversão;
- **Rodapé institucional**: colunas de links (Company, Comunidades, Links úteis) e ícones de redes sociais.

## 🛠️ Tecnologias utilizadas

- HTML5
- CSS3 (customizações próprias em `style.css`)
- [Bootstrap 5](https://getbootstrap.com/)
- [Bootstrap Icons](https://icons.getbootstrap.com/)

## 📁 Estrutura do projeto

```
spotfy/
├── css/
│   └── bootstrap.min.css
├── js/
│   └── bootstrap.bundle.min.js
├── imagens/
│   ├── favicon.png
│   ├── spotify.svg
│   ├── capa.png
│   ├── ruido.png
│   ├── img1.jpg ... img4.jpg
│   ├── iphone1.png
│   └── iphone2.png
├── index.html
├── style.css
└── README.md
```

## Destaques de estilização

- **Fundo dinâmico**: combinação de imagens (`capa.png`, `ruido.png`) com gradiente linear (`linear-gradient(50deg, #ff5169, #7c26f8)`) e `background-attachment: fixed` para efeito de profundidade;
- **Tipografia customizada**: títulos com a classe `.lr` usando a fonte Impact para reforçar a identidade visual;
- **Botões customizados**: variações `btn-roxo`, `btn-branco` e `btn-premium`, cada uma com estados de hover próprios;
- **Efeito de rotação**: classe `.rotacao` aplicada aos mockups de celular na seção Premium.

## ▶️ Como executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/PedroLins04/spotfy.git
   ```
2. Acesse a pasta do projeto:
   ```bash
   cd spotfy
   ```
3. Abra o arquivo `index.html` diretamente no navegador, ou utilize uma extensão como o **Live Server** (VS Code) para melhor experiência de desenvolvimento.

## 👤 Autor

Desenvolvido por **Pedro Lins**
[GitHub](https://github.com/PedroLins04)

---

*Projeto desenvolvido para fins de estudo e prática de front-end com Bootstrap 5.*