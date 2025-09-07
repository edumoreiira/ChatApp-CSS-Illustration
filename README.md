# Chat App CSS Illustration

Este projeto é uma solução para o desafio "Chat app CSS illustration" do [Frontend Mentor](https://www.frontendmentor.io). O principal objetivo foi recriar uma ilustração de interface de um aplicativo de chat para celular, demonstrando um domínio avançado de **HTML e SCSS** na construção de layouts desafiadores e ricos em detalhes.

Todo o design, incluindo as formas de fundo complexas e a interface do smartphone, foi construído do zero, sem o uso de frameworks, focando na precisão e na fidelidade ao design proposto.

## 🚀 Live Demo

**Visualize o projeto em ação acessando o link do GitHub Pages:**

### **[https://edumoreiira.github.io/ChatApp-Design/](https://edumoreiira.github.io/ChatApp-Css-Illustration/)**

## ✨ Funcionalidades

  - **Layout Fiel ao Design:** Uma recriação precisa da interface de um chat, incluindo cabeçalho, corpo das mensagens e caixa de envio.
  - **Formas de Fundo com CSS:** As grandes formas curvas no fundo da página foram criadas puramente com CSS, utilizando gradientes e `border-radius`.
  - **Caixas de Texto Customizadas:** Estilização detalhada para diferenciar mensagens enviadas, recebidas, com imagens e opções de seleção.
  - **Design Responsivo:** O layout se adapta de forma elegante a diferentes tamanhos de tela, de mobile a desktop.

## 💻 Tecnologias Utilizadas

  - **HTML5**
  - **SCSS** (Sass) para estilização avançada

## ⚙️ Como Utilizar

Por ser um projeto estático, basta seguir os passos abaixo:

1.  **Clone o repositório:**
    ```bash
    git clone https://github.com/edumoreiira/ChatApp-Design.git
    ```
2.  **Navegue até o diretório do projeto:**
    ```bash
    cd ChatApp-Design
    ```
3.  **Abra o arquivo `index.html` em seu navegador de preferência.**

## 🤝 Destaques do Código e Técnicas Utilizadas

Este projeto é um excelente exemplo de como layouts complexos podem ser construídos com um profundo conhecimento de CSS.

### SCSS (Sass)

  * **Construção de Layouts Desafiadores:** A principal técnica utilizada foi a combinação de `position: absolute` e `position: relative` para sobrepor e posicionar elementos com precisão, como a interface do smartphone sobre as formas de fundo decorativas.
  * **Criação de Formas Complexas com CSS:** As grandes formas curvas no fundo não são imagens. Elas são elementos `div` estilizados com um `border-radius` muito grande (`100vw`), que força o elemento a se tornar um círculo perfeito, criando o efeito desejado.
  * **Uso de Variáveis SCSS:** O código utiliza variáveis SCSS (`$primaryColor`, `$secondaryColor`, etc.) para gerenciar a paleta de cores de forma centralizada. Isso torna o código mais limpo, legível e fácil de manter.
  * **Flexbox para Alinhamento Fino:** O `display: flex` é usado extensivamente dentro da interface do chat para alinhar os elementos de forma eficiente, como o cabeçalho do usuário, as mensagens (com `align-self: flex-end` para as mensagens recebidas) e a caixa de envio.
  * **Estilização de Detalhes:** As caixas de texto do chat têm cantos arredondados de forma assimétrica (`border-radius: 1em 1em 1em .4em`), demonstrando atenção aos detalhes para corresponder ao design.
  * **Layout Responsivo com Media Queries:** Uma `@media query` é usada para reestruturar completamente o layout em telas menores, ajustando o posicionamento das formas de fundo e centralizando o conteúdo principal, garantindo uma ótima experiência em dispositivos móveis.

### HTML

  * **Estrutura Semântica e Clara:** O HTML é bem organizado com nomes de classes descritivos que correspondem à estrutura visual, facilitando a estilização e a compreensão do código.
