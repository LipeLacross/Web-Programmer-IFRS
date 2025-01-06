## 🌐 [Versão em Inglês do README](README_EN.md)

# Programador Web - IFRS

Este projeto faz parte do **Curso de Programador Web** do **IFRS** (Instituto Federal de Educação, Ciência e Tecnologia), reunindo diversos exemplos de código em **HTML**, **CSS** e **JavaScript**. A estrutura de diretórios está organizada por tópicos e datas, oferecendo exemplos para diferentes funcionalidades, desde a inclusão de mídias básicas até scripts mais avançados de interação com o usuário.

## 🔨 Funcionalidades do Projeto

- **Exemplos de HTML:**

    - Inserção de imagens, áudios e vídeos
    - Criação de formulários básicos e avançados
    - Uso de semântica básica do HTML5

- **Exemplos de CSS:**

    - Estilização de páginas e menus
    - Uso de Media Queries para responsividade
    - Personalização de elementos (efeitos de hover, submenus, etc.)

- **Exemplos de JavaScript:**

    - Manipulação de eventos (onLoad, onClick, eventos do mouse)
    - Validação de formulários e campos obrigatórios
    - Cálculos matemáticos (médias, IMC, laços de repetição)
    - Transformações de texto (caixa alta, caixa baixa, etc.)

## ✔️ Ferramentas e Tecnologias Utilizadas

- **HTML5** para a estrutura semântica das páginas
- **CSS3** para design, responsividade e estilos avançados
- **JavaScript** para adicionar interatividade e dinamismo às páginas
- **SweetAlert** (incluído em `sweetalert-master/`) como biblioteca para criar alertas estilizados
- **Git** para controle de versão, possibilitando backups e compartilhamento

## 📁 Estrutura do Projeto

Abaixo está um resumo completo de todas as pastas e seus conteúdos:

- **1.11.1 Exemplo imagem.html-20241231/**
    - `imagem.html`: Exemplo de uso da tag `<img>`.
    - `esquilo.jpg`: Imagem exibida no exemplo.

- **1.12.1 Exemplo audio.html-20241231/**
    - `audio.html`: Exemplo de uso da tag `<audio>`.
    - `music.mp3`: Arquivo de áudio.

- **1.12.2 Exemplo video.html-20241231/**
    - `video.html`: Exemplo de uso da tag `<video>`.
    - `video.mp4`: Arquivo de vídeo.

- **2.1.1 Exemplo 1-20241231/**
    - `index.html`: Exemplo básico com estilos inline.
    - `estilo.css`: Demonstração de estilização com CSS.

- **2.7.1 Exemplo menu-20250103/**
    - `index.html`: Exemplo de menu interativo com CSS.
    - `styles.css`: Estilos do menu (efeitos de hover, submenus, etc.).

- **2.8.1 Exemplo Media Query-20250103/**
    - `index.html`: Uso de diferentes breakpoints para layout responsivo.
    - `pagina.css`: Contém as Media Queries.

- **4.12.1 Código-fonte onLoad-20250104/**
    - `load.html`: Demonstra eventos `onLoad` e `onResize`.
    - `load.js`: Script para registrar eventos na página.

- **4.13.1 Código-fonte onClick-20250104/**
    - `click.html`: Exemplo para lidar com eventos de clique e duplo clique.
    - `click.js`: Script para alternar imagens com base nos eventos de clique.
    - `fachada.jpg`: Imagem exibida ao clicar.
    - `ifrs.gif`: Imagem exibida ao clicar duas vezes.

- **4.15.1 Código-fonte eventos do mouse-20250104/**
    - `mouse.html`: Exemplo de eventos do mouse como hover, clique e arraste.
    - `mouse.js`: Script demonstrando mudanças de cor durante os eventos do mouse.
    - `mouse.css`: Estilos para o exemplo de interação com o mouse.

- **4.16.1 Código-fonte validação de formulários-20250104/**
    - `vazio.html`: Demonstra uma validação simples de campos vazios.
    - `vazio.js`: Código que exibe alerta se o campo estiver vazio.

- **4.17.1 Código-fonte cálculo do IMC-20250104/**
    - `imc.html`: Página para cálculo de IMC.
    - `imc.js`: Script para calcular IMC e validar os campos de entrada.

- **4.18.1 Código-fonte transformação de letra-20250104/**
    - `maiuscula.html`: Exemplo para converter texto para maiúsculas.
    - `maiuscula.js`: Script para transformar automaticamente o texto inserido.

- **4.3.1 Código-fonte operações aritméticas-20250104/**
    - `indexjs.html`: Exemplo utilizando operações aritméticas básicas.
    - `meucodigo.js`: Script demonstrando prompts e cálculos.

- **4.5.1 Código-fonte média de valores-20250104/**
    - `media.html`: Exemplo para calcular médias de notas.
    - `media.js`: Script para cálculo de notas com condições.

- **4.6.1 Código-fonte confirmação-20250104/**
    - `confirm.html`: Exemplo demonstrando o método `confirm`.
    - `confirm.js`: Script para lidar com prompts de confirmação.

- **4.7.1 Código-fonte laços de repetição-20250104/**
    - `repete.html`: Exemplo demonstrando loops.
    - `repete.js`: Script para iterar e exibir mensagens.

- **4.8.1 Código-fonte para até-20250104/**
    - `parate10.html`: Exemplo utilizando loops para listar números pares.
    - `parate10.js`: Script para gerar números pares até um limite.

- **Backup/**
    - Contém arquivos ZIP para cada pasta de exemplo.

- **sweetalert-master/**
    - Contém o código-fonte da biblioteca SweetAlert, incluindo exemplos, estilos, testes e documentação.
    - Útil para exibir alertas amigáveis e personalizados em JavaScript.

## 🛠️ Como Rodar o Projeto

Este conjunto de exemplos não requer obrigatoriamente Node.js. Você pode abrir os arquivos `.html` diretamente no navegador. Entretanto, se desejar usar um servidor local ou scripts adicionais, siga as instruções abaixo:

1. **Certifique-se de que o Node.js está instalado (opcional)**\
   Para verificar, execute o seguinte comando no terminal:

   ```bash
   node -v
   ```

   Caso não esteja instalado, faça o download no [site oficial do Node.js](https://nodejs.org/).

2. **Clone o Repositório**\
   Copie a URL do repositório e execute o seguinte comando no terminal:

   ```bash
   git clone <URL_DO_REPOSITORIO>
   ```

3. **Abra os arquivos no navegador**\
   Navegue até a pasta do exemplo que deseja testar e abra o arquivo `.html`.

    - Exemplo: `1.11.1 Exemplo imagem.html-20241231/imagem.html`.

   **Opcional**: Execute um servidor local:

   ```bash
   npx http-server .
   ```

   Em seguida, acesse `http://localhost:8080` (ou a porta configurada) no navegador.

## 🌐 Deploy

Para publicar estes exemplos, você pode:

- **Utilizar um serviço de hospedagem estática:**

    - Exemplos incluem [GitHub Pages](https://pages.github.com/), [Vercel](https://vercel.com/) ou [Netlify](https://www.netlify.com/).
    - Basta enviar os arquivos `.html`, `.css`, `.js` e assets (imagens, áudios, vídeos) para o serviço escolhido.

- **Configurar um servidor web** (Nginx, Apache, etc.):

    - Envie os arquivos do projeto para um VPS ou instância na nuvem (AWS, Azure, DigitalOcean, etc.) e configure o servidor para apontar para a pasta contendo o projeto.
    - A partir daí, acesse o endereço configurado (ex.: `www.seusite.com`).

Este README serve como guia para compreender a estrutura geral e como executar cada exemplo. Explore as pastas, abra os arquivos `.html` e aprenda de forma prática diferentes conceitos de desenvolvimento Web!

