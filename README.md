# Discord Clone - Landing Page

Este projeto é um clone da página inicial do Discord, desenvolvido como um exercício de Web Design Responsivo. O objetivo principal foi aplicar técnicas avançadas de CSS, manipulação de caminhos de arquivos e otimização de imagens para diferentes dispositivos.

## 🚀 Tecnologias Utilizadas

* **HTML5:** Estruturação semântica do conteúdo.
* **CSS3:** Estilização, Flexbox para alinhamento e Media Queries para responsividade.
* **Google Fonts:** Utilização das fontes *Luckiest Guy* e *Open Sans*.
* **GitHub Pages:** Hospedagem e Deploy do projeto.

## 📱 Responsividade e Imagens

O projeto utiliza a tag HTML `<picture>` para garantir que o usuário receba a imagem mais adequada para o seu tamanho de tela, melhorando a performance e a experiência visual:

* **Mobile/Tablet:** Carrega imagens da pasta raiz `/assets/images/`.
* **Desktop (acima de 1280px):** Substitui automaticamente as imagens pelas versões de alta resolução contidas na pasta `/assets/images/computer/`.

## 🛠️ Como configurar o ambiente local

Para que as imagens apareçam corretamente no seu ambiente de desenvolvimento e no deploy:

1.  Certifique-se de que a estrutura de pastas segue este padrão:
    ```text
    /assets
      /images
        image1.png, image2.png...
        /computer
          img1.png, img2.png...
      /styles
        style.css
    index.html
    ```
2.  **Atenção ao Case Sensitivity:** Todos os nomes de arquivos e pastas devem estar em letras minúsculas para evitar erros em servidores Linux (GitHub Pages).