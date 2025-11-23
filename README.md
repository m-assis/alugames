# 🎮 AluGames: Simulador de Aluguel de Boardgames

![Banner Ilustrativo do Projeto AluGames]

## 📖 Sobre o Projeto

O **AluGames** é um projeto prático desenvolvido como parte de um treinamento focado em **Lógica de Programação e Algoritmos com JavaScript**. O objetivo é simular uma funcionalidade simples e comum em aplicações web: o controle de estado (alugado/disponível) de itens em uma lista.

A aplicação apresenta uma lista de jogos de tabuleiro, onde o usuário pode interagir com o botão "Alugar" ou "Devolver" para modificar o status do jogo.

---

## ✨ Funcionalidade Principal

A lógica central do projeto reside na função que permite a alternância do status:

- Quando o jogo está **Disponível**, o botão exibe **"Alugar"**.
- Ao Clicar em "Alugar":
    - O texto do botão muda para **"Devolver"**.
    - A capa do jogo é visualmente alterada (escurecida via CSS) para indicar que o item está alugado.
- Ao Clicar em "Devolver", o status e a capa voltam ao estado original.

---

## 🚀 Tecnologias e Conceitos Aplicados

| Categoria | Descrição |
| :--- | :--- |
| **Linguagem Principal** | **JavaScript (JS)**: Essencial para a lógica de controle de fluxo e manipulação do DOM. |
| **Estrutura** | **HTML5**: Criação da estrutura e dos elementos interativos. |
| **Estilização** | **CSS3**: Estilização visual, incluindo a alteração de classes para indicar o status "Alugado". |

### 🧠 Foco em Lógica de Programação e JS

O projeto foi uma excelente prática para:

* **Funções:** Criação e utilização de uma função central (`alterarStatus(id)`) com passagem de parâmetros.
* **Controle Condicional (`if/else`):** Determinar a ação correta (alugar ou devolver) com base no status atual do elemento.
* **Manipulação do DOM:** Utilização de métodos como `document.getElementById`, `classList.contains`, `classList.add` e `classList.remove` para alterar a aparência e o comportamento dos elementos HTML.

---

## ⚙️ Como Rodar o Projeto

Siga os passos para visualizar e testar o simulador:

1.  **Clone o Repositório:**
    ```bash
    git clone [LINK DO SEU REPOSITÓRIO]
    ```
2.  **Abra o Arquivo:**
    Abra o arquivo `index.html` (ou o arquivo principal do seu projeto) diretamente no seu navegador.
3.  **Teste a Funcionalidade:**
    Clique nos botões "Alugar" e "Devolver" para interagir com o sistema.
