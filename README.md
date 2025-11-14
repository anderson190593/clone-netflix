# 📺 Projeto: Clone de Interface (Streaming)

![Preview do Clone de Interface](preview.gif)

Uma recriação visual da interface de um popular serviço de streaming (inspirado no Netflix), construída com HTML5, CSS3 e Bootstrap. Este projeto é um exercício de **design de interface** focado na replicação de layouts complexos e efeitos visuais com alta fidelidade.

---

### 🎯 Objetivo

O objetivo principal é demonstrar **atenção aos detalhes** e a habilidade de traduzir um design de produto existente em código CSS funcional. O foco não está na lógica de back-end, mas sim na proficiência em CSS avançado, incluindo Flexbox, gradientes, pseudo-elementos e animações de `hover`.

---

### 🛠️ Tecnologias Utilizadas

* **Linguagem:** JavaScript (para interações futuras)
* **Tecnologias Web:** HTML5, CSS3
* **Framework/Biblioteca:** Bootstrap 5 (para a navbar, grid base e ícones)
* **Ambiente:** Navegador Web

---

### 🧱 Estrutura do Código

A aplicação é uma página única, com o `style.css` sendo o arquivo mais complexo, responsável por todos os efeitos visuais.

| Arquivo/Elemento | Propósito Principal |
| :--- | :--- |
| `index.html` | Estrutura semântica das seções (navbar, hero, fileiras de filmes). |
| `css/style.css` | **Estilização Principal:** Contém todo o design, gradientes, hover e layout. |
| `.jumbotron` | Classe personalizada para a seção "Hero" principal, com imagem de fundo. |
| `.jumbotron::after` | Pseudo-elemento CSS usado para aplicar o *overlay* de gradiente escuro. |
| `.movie-row` | Classe para as fileiras de filmes, utilizando `flex-nowrap` e `overflow-auto`. |
| `.movie-row img:hover` | Seletor que aplica a animação de `transform: scale()` nas capas. |

---

### 🔍 Funcionalidades

* **Navbar Fixa:** Barra de navegação que se mantém no topo, com ícones e logo.
* **Seção "Hero" com Gradiente:** Uma seção de destaque com imagem de fundo e um *overlay* de gradiente (técnica comum em UIs de streaming).
* **Fileiras com Scroll Horizontal:** Múltiplas fileiras de filmes que podem ser roladas horizontalmente.
* **Efeito de Hover (Zoom):** As capas dos filmes aumentam de tamanho (`scale`) suavemente ao passar o mouse, simulando a interatividade da plataforma original.
* **Layout Responsivo:** A interface se adapta para visualização em dispositivos móveis.

---

### 🧪 Como Executar

Este é um projeto de front-end estático.

1.  Clone o repositório (ou tenha a pasta do projeto em sua máquina).
2.  Abra o arquivo `index.html` no seu navegador de preferência.

---

### 📚 Aprendizado

Este projeto foi um exercício profundo de design e CSS avançado:

* **Layout com Flexbox:** Pratiquei o uso de `flex-nowrap` e `overflow-auto` para criar carrosséis horizontais de forma limpa, sem a necessidade de bibliotecas JavaScript.
* **CSS Avançado (Pseudo-elementos):** Aprendi a usar pseudo-elementos como `::after` para aplicar *overlays* de gradiente (`linear-gradient`), uma técnica essencial para design de interfaces modernas.
* **Animações e Transições:** Aprofundei meu conhecimento em `transform: scale()` e `transition` para criar efeitos de `hover` fluidos e profissionais.
* **Atenção ao Detalhe:** O maior desafio foi replicar o "feeling" da plataforma original, ajustando pequenos detalhes de espaçamento, sombra e timing das animações.

---

📄 **Licença**
Este projeto está licenciado sob a MIT License.
