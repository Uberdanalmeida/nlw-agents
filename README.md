# NLW Agents - Assistente de Meta para Jogos

![profile](./Imagem/nlw-agents.png)

Este projeto é um **Assistente de Meta para Jogos** desenvolvido durante o evento NLW (Next Level Week). Ele permite que você faça perguntas sobre estratégias, builds e dicas para seus jogos favoritos, utilizando a API do Google Gemini para gerar as respostas.

---

## 🚀 Tecnologias Utilizadas

O projeto foi construído utilizando as seguintes tecnologias:

* **HTML5**: Para a estrutura e conteúdo da página web.
* **CSS3**: Para estilização e design responsivo da interface.
* **JavaScript (ES6+)**: Para a lógica de interação com a API do Gemini, manipulação do DOM e funcionalidades dinâmicas.
* **Google Gemini API**: Para processamento de linguagem natural e geração de respostas inteligentes.
* **Showdown.js**: Uma biblioteca para converter Markdown em HTML, utilizada para exibir as respostas da IA.

---

## ✨ Funcionalidades

* **Assistente de Meta**: Faça perguntas específicas sobre estratégias, builds e dicas para jogos como Valorant, League of Legends e CS:GO.
* **Integração com Gemini API**: Utiliza o poder da inteligência artificial do Google Gemini para fornecer respostas relevantes e atualizadas.
* **Design Responsivo**: Interface adaptável a diferentes tamanhos de tela.
* **Feedback Visual**: Indicador de carregamento enquanto a IA processa a pergunta.

---

## 🛠️ Como Usar

Para configurar e rodar este projeto localmente, siga os passos abaixo:

### Pré-requisitos

* Um navegador web moderno (Chrome, Firefox, Edge, Safari, etc.).
* Uma **API Key do Google Gemini**. Você pode obter uma gratuitamente através do [Google AI Studio](https://aistudio.google.com/app/apikey).

### Instalação

1.  **Clone o repositório:**

    ```bash
    git clone <URL_DO_SEU_REPOSITORIO>
    cd nlw-agents
    ```

2.  **Abra o `index.html`:**
    Simplesmente abra o arquivo `index.html` no seu navegador. Não é necessário um servidor local para este projeto, pois ele utiliza apenas tecnologias front-end.

### Utilização

1.  **Informe sua API Key do Gemini**: No campo "Informe a API KEY do Gemini", insira sua chave.
2.  **Selecione um Jogo**: Escolha o jogo para o qual você deseja uma dica (Valorant, League of Legends, CS:GO).
3.  **Faça sua Pergunta**: Digite sua pergunta no campo de texto, por exemplo: "Melhor build para ADC..." ou "Estratégias para o mapa Ascent no Valorant".
4.  **Clique em "Perguntar"**: A IA irá processar sua solicitação e exibir a resposta abaixo do formulário.