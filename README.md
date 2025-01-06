## 🌐 [English Version of README](README_EN.md)

# Programador Web - IFRS

Este projeto faz parte do **Curso de Programador Web** do **IFRS** (Instituto Federal de Educação, Ciência e Tecnologia), reunindo diversos exemplos de código em **HTML**, **CSS** e **JavaScript**. A estrutura de diretórios foi organizada por tópicos e datas, oferecendo exemplos para diferentes funcionalidades, desde a inclusão de mídias básicas até scripts mais avançados de interação com o usuário.

## 🔨 Funcionalidades do Projeto

- **Exemplos de HTML:**

    - Inserção de imagens, áudios, vídeos
    - Criação de formulários básicos e avançados
    - Uso de semântica básica de HTML5

- **Exemplos de CSS:**

    - Estilização de páginas e menus
    - Uso de Media Queries para responsividade
    - Personalização de elementos (hover, submenus etc.)

- **Exemplos de JavaScript:**

    - Manipulação de eventos (onLoad, onClick, eventos do mouse)
    - Validação de formulários e campos obrigatórios
    - Cálculos matemáticos (média, IMC, laços de repetição)
    - Transformações de texto (caixa alta, caixa baixa etc.)

## ✔️ Técnicas e Tecnologias Utilizadas

- **HTML5** para a marcação semântica das páginas
- **CSS3** para o design, responsividade e estilos avançados
- **JavaScript** para adicionar interatividade e dinamismo às páginas
- **SweetAlert** (contido em `sweetalert-master/`) como biblioteca para criar alertas estilizados
- **Git** para controle de versão, possibilitando backup e compartilhamento

## 📁 Estrutura do Projeto

Abaixo, um resumo das principais pastas e seus conteúdos:

- **1.11.1 Exemplo imagem.html-20241231/**

    - `imagem.html`: Exemplo de uso da tag `<img>`.
    - `esquilo.jpg`: Imagem exibida no exemplo.

- **1.12.1 Exemplo audio.html-20241231/**

    - `audio.html`: Exemplo de uso da tag `<audio>`.
    - `music.mp3`: Arquivo de áudio.

- **2.7.1 Exemplo menu-20250103/**

    - `index.html`: Exemplo de menu interativo com CSS.
    - `styles.css`: Estilos do menu (hover, submenus, etc.).

- **2.8.1 Exemplo Media Query-20250103/**

    - `index.html`: Uso de diferentes breakpoints para layout responsivo.
    - `pagina.css`: Contém as Media Queries.

- **4.12.1 Código-fonte onLoad-20250104/**

    - `load.html`: Demonstra eventos `onLoad` e `onResize`.
    - `load.js`: Script para registrar eventos na página.

- **4.16.1 Código-fonte validação de formulários-20250104/**

    - `vazio.html`: Demonstra uma simples checagem de campo vazio.
    - `vazio.js`: Código que exibe alerta se o campo estiver vazio.

- **Backup/**

    - Zips de cada tópico, caso você queira restaurar ou baixar separadamente.

- **sweetalert-master/**

    - Contém o código-fonte da biblioteca SweetAlert, incluindo exemplos, estilos, testes e documentação.
    - Útil para mostrar alertas amigáveis e personalizados em JavaScript.

## 🛠️ Abrir e rodar o projeto

Este conjunto de exemplos não requer obrigatoriamente Node.js. Você pode abrir os arquivos `.html` diretamente no seu navegador. Entretanto, se desejar utilizar um servidor local ou contar com scripts adicionais, siga as instruções abaixo:

1. **Certifique-se de que o Node.js está instalado (opcional)**\
   Para checar, execute no terminal:

   ```bash
   node -v
   ```

   Se não estiver instalado, faça o download no [site oficial do Node.js](https://nodejs.org/).

2. **Clone o Repositório**\
   Copie a URL do repositório e execute no seu terminal:

   ```bash
   git clone <URL_DO_REPOSITORIO>
   ```

3. **Abra os arquivos em seu navegador**\
   Navegue até a pasta do exemplo que deseja testar e abra o arquivo `.html`.

    - Exemplo: `1.11.1 Exemplo imagem.html-20241231/imagem.html`.

   **Opcional**: Execute um servidor local:

   ```bash
   npx http-server .
   ```

   Em seguida, acesse `http://localhost:8080` (ou outra porta configurada) no seu navegador.

## 🌐 Deploy

Para publicar estes exemplos, você pode:

- **Utilizar um serviço de hospedagem estática**:

    - Exemplos incluem [GitHub Pages](https://pages.github.com/), [Vercel](https://vercel.com/) ou [Netlify](https://www.netlify.com/).
    - Basta enviar os arquivos `.html`, `.css`, `.js` e assets (imagens, áudios, vídeos) para o serviço escolhido.

- **Configurar um servidor web** (Nginx, Apache, etc.):

    - Subir os arquivos do projeto em um VPS ou instância na nuvem (AWS, Azure, DigitalOcean, etc.) e apontar o servidor para a pasta contendo o projeto.
    - A partir daí, basta acessar o endereço configurado (ex.: `www.seusite.com`).

Este README serve como guia para compreender a estrutura geral e como iniciar a execução de cada exemplo. Explore as pastas, abra os arquivos `.html` e conheça de forma prática diferentes conceitos de desenvolvimento Web!

