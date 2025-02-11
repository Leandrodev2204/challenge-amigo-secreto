# Sorteio Amigo Secreto

Este projeto implementa um sorteio de amigo secreto interativo utilizando HTML, CSS e JavaScript. Permite adicionar nomes de amigos, listá-los e sortear um amigo secreto aleatoriamente.

## Funcionalidades

*   **Adicionar Amigo:** Permite inserir o nome de um amigo e adicioná-lo à lista.
*   **Listar Amigos:** Exibe a lista de amigos adicionados.
*   **Sortear Amigo Secreto:** Realiza o sorteio aleatório e revela o amigo secreto sorteado.
*   **Interface Amigável:** Design responsivo e intuitivo para facilitar o uso.

## Tecnologias Utilizadas

*   **HTML:** Estrutura do conteúdo e elementos da página.
*   **CSS:** Estilos visuais e layout da aplicação.
*   **JavaScript:** Lógica de programação, manipulação do DOM e funcionalidades interativas.

## Como Usar

1.  Clone este repositório: `git clone https://github.com/Leandrodev2204/challenge-amigo-secreto`
2.  Abra o arquivo `index.html` em seu navegador.
3.  Digite o nome de um amigo no campo de texto e clique em "Adicionar".
4.  Repita o passo anterior para adicionar mais amigos.
5.  Clique em "Sortear amigo" para realizar o sorteio.
6.  O amigo secreto sorteado será exibido na tela.

## Estrutura do Projeto

sorteio-amigo-secreto/
├── index.html      # Arquivo principal HTML
├── app.js          # Arquivo JavaScript com a lógica do sorteio
├── style.css       # Arquivo CSS com os estilos visuais
└── assets/         # Pasta com imagens e outros recursos
└── amigo-secreto.png
└── play_circle_outline.png

## Explicação do Código

### `app.js`

*   `amigos`: Array que armazena os nomes dos amigos.
*   `adicionarAmigo()`: Função que adiciona um amigo à lista, após validar se o campo está vazio.
*   `atualizarLista()`: Função que atualiza a exibição da lista de amigos na tela.
*   `sortearAmigo()`: Função que realiza o sorteio aleatório e exibe o resultado.

### `index.html`

*   Estrutura básica da página HTML, incluindo os elementos de entrada, lista e botão.
*   Chamadas para os arquivos CSS e JavaScript.
*   Funções `adicionarAmigo()` e `sortearAmigo()` são chamadas através dos eventos `onclick` nos botões.

### `style.css`

*   Estilos visuais da página, incluindo cores, fontes e layout.
*   Design responsivo para diferentes tamanhos de tela.

## Melhorias Futuras

*   **Persistência de Dados:** Implementar o uso de localStorage ou um banco de dados para salvar a lista de amigos.
*   **Sorteio Secreto Individual:** Enviar o resultado do sorteio para cada amigo individualmente, talvez por e-mail ou outro meio.
*   **Interface Gráfica Aprimorada:** Melhorar o design e a experiência do usuário.
*   **Testes Unitários:** Adicionar testes para garantir a qualidade do código.

## Contribuição

Contribuições são sempre bem-vindas! Sinta-se à vontade para abrir issues e pull requests.

## Autor

LEANDRO TORRES LOUZEIRO DA SILVA

