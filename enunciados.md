<h1>Enunciados</h1>

<h3>1</h3>
<p>Reescrever o código abaixo de maneira que ele imprima as informações de maneira correta, que faça sentido e sem erros:</br></br>
let numeroUm = 1</br>
let stringUm = '1'</br>
let numeroTrinta = 30</br>
let stringTrinta = '30'</br>
let numeroDez = 10</br>
let stringDez = '10'</br>

if (COMPARAR O numeroUm e a stringUm) {</br>
  console.log('As variáveis numeroUm e stringUm tem o mesmo valor, mas tipos diferentes')</br>
} else {</br>
  console.log('As variáveis numeroUm e stringUm não tem o mesmo valor')</br>
}</br>

if (COMPARAR O numeroTrinta e a stringTrinta) {</br>
  console.log('As variáveis numeroTrinta e stringTrinta tem o mesmo valor e mesmo tipo')</br>
} else {</br>
  console.log('As variáveis numeroTrinta e stringTrinta não tem o mesmo tipo')</br>
}</br>

if (COMPARAR O numeroDez e a stringDez) {</br>
  console.log('As variáveis numeroDez e stringDez tem o mesmo valor, mas tipos diferentes')</br>
} else {</br>
  console.log('As variáveis numeroDez e stringDez não tem o mesmo valor')</br>
}</p>

<h3>2</h3>
<p>Sabe quando você se cadastra em um site e, logo em seguida, quando faz o seu login, ele já te chama pelo seu nome?</br>
É isso que você vai fazer no desafio de hoje!</br>

Ele deve pedir para o usuário responder 3 perguntas:
- Qual o seu nome?
- Quantos anos você tem?
- Qual linguagem de programação você está estudando?</br>

No final, o sistema vai exibir a mensagem:</br>
"Olá [nome], você tem [idade] anos e já está aprendendo [linguagem]!"</br></br>

EXERCÍCIO OPCIONAL

Você vai complementar o código para que, depois de exibir a mensagem anterior, o programa pergunte:</br>
Você gosta de estudar [linguagem]? Responda com o número 1 para SIM ou 2 para NÃO.</br></br>
E aí, dependendo da resposta, ele deve mostrar uma das seguintes mensagens:

1 > Muito bom! Continue estudando e você terá muito sucesso.</br>
2 > Ahh que pena... Já tentou aprender outras linguagens?</p>

<h3>3</h3>
<p>Seu desafio de hoje é criar os destinos possíveis de um jogo, em que o usuário consiga escolher:

1. Se quer seguir para área de Front-End ou seguir para a área de Back-End.

2. Caso esteja na área de Front-End, se quer aprender React ou aprender Vue. 
Caso esteja na área de Back-End, poderá aprender C# ou aprender Java.

3. Depois, independente das escolhas anteriores, o usuário poderá escolher entre seguir 
se especializando na área escolhida ou seguir se desenvolvendo para se tornar Fullstack. 
Você deve exibir na tela uma mensagem específica para cada escolha.

4. Por fim, pergunte quais são as tecnologias nas quais a pessoa gostaria de se especializar 
ou de conhecer. Aqui, a pessoa pode responder N tecnologias, uma de cada vez. Então, enquanto 
ela continuar respondendo ok para a pergunta: "Tem mais alguma tecnologia que você gostaria 
de aprender?", continue apresentando para ela o Prompt, para que ela complete o nome da tecnologia 
em questão. E, logo depois, apresente uma mensagem comentando algo sobre a linguagem inserida.

O importante é que a pessoa que estiver jogando possa sempre escolher qual decisão tomar para 
conseguir aprender e se desenvolver na área de programação.

Além disso, também é essencial que, ao final do jogo, ela possa inserir quantas tecnologias 
quiser na lista de aprendizado.
</p>

<h3>4</h3>
<p>Você deve criar um programa que comece com um valor específico pré-definido entre 0 a 10 para o número que você vai adivinhar (7, por exemplo).

Em seguida, o programa vai perguntar para você qual o valor que você deseja chutar e, caso você acerte, ele irá te parabenizar. Caso erre, ele vai te dar mais 2 tentativas.

No fim, caso você não acerte nenhuma vez, ele vai imprimir qual era o número inicial.

Depois que o programa estiver funcionando, tente usar um número randômico em vez de um número pré-definido.
</p>

<h3>5</h3>
<p>Você deve criar um programa em Javascript que perguntará se você deseja adicionar uma comida na sua lista de compras, 
  e você deve poder responder com sim ou não.

Em seguida, ele perguntará qual comida você deseja inserir, e você digitará o nome dela, como por exemplo batata.

Depois, ele deverá perguntar em qual categoria essa comida se encaixa, com algumas opções já pré-definidas, como frutas, laticínios, congelados, doces e o que mais você achar interessante. Assim, você poderá separar tudo no seu devido grupo.

Por fim, caso você não queira mais adicionar nada na lista de compras e responder não na primeira pergunta, ele irá exibir uma lista com todos os itens agrupados, da seguinte forma:

Caso você adicione na sua lista:
banana, leite em pó, tomate, leite vegetal, chiclete, bala de ursinho, maçã, uva, abacate e leite de vaca

O programa deverá imprimir, por exemplo:

Lista de compras:
- Frutas: banana, tomate, maçã, uva, abacate
- Laticínios: leite vegetal, leite de vaca, leite em pó
- Congelados:
- Doces: chiclete e bala de ursinho
</p>

<h3>6</h3>
<p>Você deverá criar a opção de remover algum item da lista de compras, que será exibida junto à pergunta de “você deseja adicionar uma comida na lista de compras”?

A partir daí, caso a pessoa escolha essa opção, o programa irá imprimir os elementos presentes na lista atual, e a pessoa deverá escrever qual deles deseja remover.

Depois disso, o programa irá remover o elemento da lista e imprimir a confirmação de que o item realmente não está mais lá.

Por fim, ele voltará para o ciclo inicial de perguntas.

Se, na hora de deletar o item, o mesmo não for encontrado na lista, você deverá exibir uma mensagem avisando isso.

Por exemplo: “Não foi possível encontrar o item dentro da lista!”

Lembre-se que a opção de remover um item só deverá estar disponível a partir do momento que existir ao menos um elemento dentro da lista de compras.
</p>

<h3>7</h3>
<p>Faça uma calculadora que peça ao usuário que escolha a operação que deseja realizar (adição, subtração, multiplicação ou divisão).
  O usuário também deve informar os números a serem calculados.</p>
