# caique

HTML
A estrutura da página é definida em HTML. Inclui quatro campos de entrada (<input>) onde o usuário pode digitar os números, um botão (<button>) para acionar o cálculo, e uma área (<div>) para exibir o resultado. Cada campo de entrada tem um identificador único (id) para facilitar o acesso e manipulação dos valores inseridos pelo usuário.

CSS
O CSS é utilizado para estilizar a página, tornando-a visualmente agradável. Define o layout geral, como centralizar o conteúdo na tela e aplicar uma aparência moderna aos elementos. A classe .container adiciona uma borda arredondada e sombra ao bloco que contém os campos e o botão. Os campos de entrada e o botão são estilizados para melhorar a usabilidade e a aparência.

JavaScript
O JavaScript é responsável pela funcionalidade da página. Quando o botão é clicado, a função calcularMedia() é chamada. Esta função coleta os valores inseridos nos campos de entrada, converte-os em números usando parseFloat, e calcula a média aritmética dos quatro valores. Se algum campo estiver vazio, o valor padrão utilizado é 0. O resultado da média é então formatado com duas casas decimais e exibido na área designada (<div id="resultado">).
