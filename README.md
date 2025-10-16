# exercicios-lista01-logica-forja-tarde
1 - captar do usuario nome e printar logo abaixo do input (NOME DA PASTA: EXER1)
2 - pegar idade do usuario, se for menor que 18 falar que é menor de idade se nao printar maior de idade (NOME DA PASTA: EXER2)
3 - pegar a media de 3 notas, printar o resultado logo abaixo, SE ABAIXO DE 7 PRINTAR REPROVADO SE NAO APROVADO (NOME DA PASTA: EXER3)
4 - calcular a area de um quadrado  (NOME DA PASTA: EXER4)
5 - pegar nome, descricao, idade, genero e hobby preferido do usuario, printar tudo logo abaixo  (NOME DA PASTA: EXER5)
6 - calcular a soma de dois numeros , ao final, subtrair 5 e printar o resultado  (NOME DA PASTA: EXER6)

TODOS OS EXERCÍCIOS DEVEM ESTAR EM PASTAS DIFERENTES, O ESTILO É DE LIVRE ESCOLHA DO ALUNO, TERMINAR ATÉ O FIM DA TARDE DE HJ.
CRIAR UM NOVO REPOSITORIO NO GITHUB CHAMADO exercicios-lista01-logica-forja-tarde

DESAFIO:
Com ajuda do chatgpt ou gemini ou deepseek, pedir uma calculadora com +, -, * e /, usando grid no css, sendo a estrutura em html e javascript para o funcionamento, a calculadora deve estar centralizada na tela.
Pegas os arquivos e montar em uma pasta chamada CalculadoraIA

OS EXERCICIOS VALEM 1 PTO CADA, COMPORTAMENTO 3 PTOS E O DESAFIO 1 PTO. PARA O COMPORTAMENTO QUEM TERMINAR DEVE AJUDAR OS COLEGAS COM DIFICULDADE.

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>EXER4</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>
    <h1>ÁREA DE UM QUADRADO</h1>
    <main>
        <div>
            <label>Lado do quadrado</label>
            <input type="number" placeholder="lado" id="lado1">
               <input type="number" placeholder="lado" id="lado2">
        </div>
        <button onclick="quadrado ()">Clique</button>
        <br><br>
        <hr id="resposta"></h2>
    </main>

    <script src="script.js"></script>
</body>

</html>