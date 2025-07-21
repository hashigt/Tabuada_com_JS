Projeto: Gerador de Tabuada Interativo
Este projeto é um gerador de tabuadas simples e interativo desenvolvido com HTML, CSS e JavaScript. Ele permite que o usuário insira um número e um limite de multiplicação para gerar e visualizar a tabuada correspondente de forma dinâmica no navegador.

🚀 Tecnologias Utilizadas
HTML: Estrutura básica da página web e dos elementos do formulário.

CSS: Estilização (o arquivo styles.css é referenciado no HTML para dar uma aparência agradável à interface).

JavaScript: Lógica de manipulação do DOM, cálculo da tabuada e interação com o usuário.

✨ Funcionalidades
Entrada de Dados: O usuário pode digitar o número base para a tabuada e o limite máximo de multiplicação.

Geração Dinâmica: A tabuada é gerada e exibida instantaneamente após o clique no botão "Calcular", sem a necessidade de recarregar a página.

Interface Clara: Apresentação das operações de multiplicação de forma organizada.

💡 Como Funciona
Interface do Usuário (HTML):

Um formulário intuitivo solicita o "Número da Tabuada" e o "Multiplicar até".

Um botão "Calcular" aciona a geração da tabuada.

Uma seção dedicada exibe as operações e seus resultados.

Lógica (JavaScript):

O JavaScript seleciona os elementos do formulário e da área de exibição da tabuada.

Uma função criarTabela é responsável por:

Limpar qualquer conteúdo anterior da tabuada.

Iterar de 1 até o limite de multiplicação definido.

Calcular o resultado de cada operação (número x i).

Gerar dinamicamente o código HTML para cada linha da tabuada (ex: 5 x 1 = 5).

Inserir essas linhas HTML na área de exibição.

Atualizar o título para indicar o número da tabuada atual.

Um evento de submit no formulário captura as entradas do usuário, previne o recarregamento da página e valida se os campos foram preenchidos antes de chamar a função criarTabela.

▶️ Como Rodar o Projeto
Para visualizar e testar o projeto, basta abrir o arquivo index.html em seu navegador. Não é necessário nenhum servidor web para executá-lo.
