# aula-dev 25/09/24
//Questão 1 NÍVEL FÁCIL

const nome = ('Carla');
console.log (nome);

//Questão 2

const numero1 = ('10')
const numero2 = ('20')
const somaFinal = numero1 + numero2;
console.log (somaFinal);

//Questão 3

let idade = ('25')
let maiordeidade = idade >= 18
console.log (maiordeidade)

//Questão 4

let a = 5;
let b = 10;
let c = 15;

let media = (a + b + c) /3;
console.log (media)

//Questão 5

let preco = 130;
preco += preco * 0.10;
console.log (preco)

//Questão 1 NÍVEL MÉDIO

const anoNascimento = 2007;
const idadeFinal = 2024 - anoNascimento;
console.log (idadeFinal)

//Questão 2

function isEven (N) {
    return N % 2 === 0 ? true : false;
}

let N = 5;
console.log (isEven(N))

//Questão 3

let salario = 2500;

if(salario > 2000) {
    salario *= 0,9;
} 
 else {
    salario *= 1,5
}

console.log (salario);

//Questão 4

const r = 9;   
const perimetro = 2 * Math.PI * r;

console.log (perimetro)

//Questão 5

let num1 = 12
let num2 = 19

const numeroMaior = num2 > num1 ? num2 : num1;
console.log ('O maior número é: ' + numeroMaior);

//Questão 6

var celsius = 32;
let result = (celsius * 9/5) + 32;
console.log (result);

//Questão 7

let g = 15; 
let d = 30;

console.log('Antes da troca: g = ${g}, d = ${d}');

[g, d] = [d, g];

console.log ('Após a troca: g = ${g}, d = $(d)');










# aula-dev 27/09/24

const u = 10;
const b = o numero é ${u};
console.log(b)

const nome = 'Carla.' ;
const idade = 17;
const stringTemplate = oi meu nome é ${nome} ! e minha idade é ${idade};
console.log (stringTemplate);

const valor1 = true;
const valor2 = false;

const valor1EValor2 = valor1 && valor2;
const valor1OUValor2 = valor1 || valor2;
const inversoValor1 = !valor1;
const inversoValor2 = !valor2;

console.log(valor1EValor2);
//false
console.log(valor1OUValor2);
//true

console.log(inversoValor1);
//false
console.log(inversoValor2);









# aula-dev 02/10/24

//teste 1
let x = 2;
let y = 'string de test';

//teste 2
console.log(01:${x > 1});
console.log(02:${x > 10});

//teste 3
console.log(03:${y === 'string de teste'});
console.log(04:${y !== 'novo texto que eu inventei'});

//teste 4
console.log(05:${x >= 2});
console.log(06:${x >= 1});
console.log(07:${x >= 3});
console.log(08:${x <= 3});
console.log(09:${x <= 10});

//teste 5
let valor1 = 2;
console.log(valor1);
console.log(typeof valor1);

//teste 6
let valor2 = undefined;
console.log (valor2);
console.log (typeof valor2);
[13:58, 10/2/2024] carlinha: let minhaString = "Eu adoro aprender JavaScript";
if (minhaString.includes(JavaScript)){
    console.log ("Minha String contém a palavra JavaScript");
} else {
    console.log ("Minha String não contém a palavra JavaScript");
}
let salario = 320;
console.log(salario >= 2000);

//EXERCICIOS

//1
let meuNome = "Carla Santos";
console.log (meuNome);

//2
let string1 = "Olá mundo!";
let string2 = "Olá mundo!";

if
    (string1==string2)
    {
        console.log("As strings são iguais")
    } else {
        console.log("As strings são diferentes")
    };

//3

let num = 9;
console.log(num >= 10);

//4

let idade1 = 17;
if (idade1 >= 18) {
    console.log("Parabéns");
} else {
    console.log("Ainda não tem 18");
}

//5
let podeVotar = 14
if (podeVotar >= 16) {
    console.log ("Pode votar");
} else {
    console.log ("Não pode votar");
}

//6
let valor2 = 49
if (valor2 >= 50) {
    console.log ("Está entre 50 e 100");
} else {
    console.log ("Não está entre 50 e 100");
}

//1

let idade2 = 14;
if (idade2 >= 18) {
    console.log("Adulto");
} else {
    console.log("Não adulto");
}

//2


let num1 = 7;
let num2 = 10;

if (num1 > num2) {
    console.log(num1);
} else {
    console.log (num2)
}

//3

let text1 = "carl";

if(text1.length >= 5){
    console.log ("Texto maior que 5 caracteres.");
} else {
    console.log ("Texto menor que 5 caracteres.");
}

//4
let num4 = 12;
let par = num4 % 2 === 0;

console.log(par);

//5

let minhaString = "Eu adoro aprender JavaScript!";

if (minhaString.includes("JavaScript")) {
    console.log("A string contém a palavra 'JavaScript'.");
} else {
    console.log("A string não contém a palavra 'JavaScript'.");
}

//6

let salario = 320;
console.log(salario >= 2000);

//2

let nota1 = ("8");
let nota2 = ("6");
let nota3 = ("10");

let media = (nota1 + nota2 + nota3) / 3;

if (media > 7) {
    console.log("Aprovado");
} else {
    console.log("Reprovado");
}








# aula-dev 04/10/2024

//Nível Fácil

//1
let meuArray =[];

meuArray [0] = 10;
meuArray [1] = 100;
meuArray [2] = 30;

console.log (meuArray);

//2
console.log (meuArray[0]);

//3
console.log (meuArray[1]);

//4
const Array = ["maçã", "banana","uva", "morango", "melão"];
console.log ("Quantidade de elementos:", Array.length);

//5
const numeros = [1, 5, 8, 9, 5];

const soma = numeros.reduce ((total, num) => total + num, 0);
console.log ("A soma dos números é:", soma);

//6
const numeros1 = [10, 20, 30, 40, 50];
numeros.pop();
console.log("O novo array é:", numeros1);

//7
const number = [1, 2, 3, 4];
number.unshift(8);
console.log ("O novo numero é:", number);

//8
array1 = [3, 5, 9, 0];
array2 = [2, 4, 8, 1];

const combinado = array1.concat(array2);
console.log ("O array combinado é:", combinado);

//Nível médio

//1

 //2

const livros = [
    { nome: "É assim que acaba", autor: "Colleen Hoover" },
    { nome: "Mentirosos", autor: "E. Lockhart" },
    { nome: "Verity", autor: "Collen Hoover" },
    { nome: "A Revolução dos Bichos", autor: "George Orwell" },
    { nome: "O Pequeno Príncipe", autor: "Antoine de Saint-Exupéry" }
];

livros.forEach(livro => {
    console.log("Nome do livro:", livro.nome);
});









# aula-dev 16/10/24

//teste 1
function pegarComanda (){
    console.log('Ola, boa noite!')
    console.log('Pegue aqui sua comanda')
    console.log('Bom apetite')
    console.log('---------------------------------');
}

pegarComanda();
pegarComanda();
pegarComanda();
pegarComanda();
pegarComanda();
pegarComanda();

//teste 2

let numeroDaVez = 1;

function calcuQuadrado() {
    console.log(O número da vez é o ${numeroDaVez});
    console.log(O número da vez ${numeroDaVez} ao quadrado é ${numeroDaVez ** 2});
}

calcuQuadrado(1);

//teste 3

function calcularRaizQuadrada (base) {
    base**(1/2);
console.log(base**(1/2));
}

//teste 4
function resolverBhaskara (a, b, c) {
    const delta = b ** 2 - 4 * a * c;
    const x1 = (-b + calcularRaizQuadrada(delta)) / (2 * a);
    const x2 = (-b - calcularRaizQuadrada(delta)) / (2 * a);

    console.log(
        Os dois valores de X dos pontos da parábola no eixo X são ${x1} e ${x2}
    );

}



# aula-dev 31/10/24

// 1 Maiusculo/Minusculo
let texto = "senaimorvan"; 
let maiusculo = texto.toLowerCase();
let minusculo = texto.toUpperCase();

console.log(minusculo);
console.log(maiusculo);

// 2 includes/indexOF
let aaa = "certeza";
console.log(aaa.includes("a"), aaa.indexOf("a"));

// 3 slice
let noiticia = "Frase para retirar";
console.log(noiticia.slice(10))

// 4 concat
let morvan = "Morvan";
console.log(morvan.concat(" Figueiredo"));

// 5 Replace
let abc = "abc";
console.log(abc.replace('abc', 'zxc'))

// 6 split, join

// 7 push, pop
let fila = [];
let add = fila.push(1, 2, 3 ,4 , 5);
let pp = fila.pop(5);
console.log(fila);

// 8 shift, unshift 
let cliente = [15, 20, 25, 30];
let sai = cliente.shift();
let entra = cliente.unshift(22);
console.log(cliente);

// 9 reverse
let numerosss = [1, 2, 3, 4 ,5];
console.log(numerosss.reverse());

// 10 map 

// 11 filter 
const listaNotas = [
    {nome: 'Bagriel', nota: 10},
    {nome: 'rilomu', nota: 15},
    {nome: 'Pina', nota: 12},
    {nome: 'Carla', nota: 6}
    ];
    
    const alunoAprovado = listaNotas.filter(function(aluno){
        return aluno.nota > 7;
    });
    
    console.log(alunoAprovado);

// 12 reduce    
const compras = [2, 4, 6, 8, 0]

const soma = compras.reduce((total, num) => total + num, 0)
console.log(soma);

// 13 sort 
let livro = ["Diario de um Banana", "Biblia", "O pequeno Principe"];

livro.sort();


console.log(livro);

// 14 Math.random
let senha  = Math.random().toString(36).substr(2, 10);
console.log(senha);
//Math.floor
let idade = Math.floor(25.5);
console.log(idade);

// 15 Object.keys, object.values
const pessoa = {
    nome: 'João',
    idade: 25,
    cidade: 'São Paulo'
    }
    const keys = Object.keys(pessoa);
    const values = Object.values(pessoa);
    console.log(keys);  
    console.log(values);

// 16 this
function pessoa(nome, idade, cidade){
    this.nome = nome;
    this.idade = idade;
    this.cidade = cidade;
    }
    const joao = new pessoa('João', 25, 'São Paulo');
    console.log(joao);

    # aula-dev 05/11/24

    //1
    let curso = "Logística";

switch(curso) {
  case "Desenvolvimento de Sistemas":
    console.log("Curso: Desenvolvimento de Sistemas\nDuração: 2 anos\nCarga horária: 3200 horas");
    return;
  case "Logística":
    console.log("Curso: Logística\nDuração: 1 ano e 6 meses\nCarga horária: 2400 horas");
    return;
  case "Administração":
    console.log("Curso: Administração\nDuração: 2 anos\nCarga horária: 3000 horas");
    return;
  default:
    console.log("Curso não encontrado.");

    
}

//2
const mais = '/';
const soma = 2;
const soma1 = 4;
switch(mais){
    case'+':
    console.log(`${soma + soma1}`);
    break;
    case'-':
    console.log(`${soma - soma1}`);
    break;
    case'*':
    console.log(`${soma * soma1}`);
    case'/':
    break;
    console.log(`${soma / soma1}`);
    break;
}

//3
const idade = 2;
switch(true){
    case idade <= 12:
    console.log("Infantil");
    break;
    case'>=13 && <=17':
    console.log("Adolescente");
    break;
    case'>=18 && <60':
    console.log("Adulto");
    break;
    case'>=65':
    console.log("Idoso");
    break;
}

//4

let nota = 2; 

switch (true) {
    case (nota = 1 && nota <= 3):
        console.log("Insuficiente");
        break;
    case (nota >= 4 && nota <= 6):
        console.log("Regular");
        break;
    case (nota >= 7 && nota <= 8):
        console.log("Bom");
        break;
    case ( nota >= 9):
        console.log("Excelente");
        break;
}

//5

let semana = 2;

switch(true) {
    case (semana === 1):
    console.log("Domingo");
    break;
    case (semana === 2):
    console.log("Segunda");
    break;
    case (semana === 3): 
    console.log("Terça");
    break;
    case (semana === 4): 
    console.log("Quarta-feira");
    break;
    case (semana === 5): 
    console.log("Quinta-feira");
    break;
    case (semana === 6): 
    console.log("Sexta-feira");
    break;
    case (semana === 7): 
    console.log("Sabado");
    break;
}

//6

let evento = "Festa junina" 
switch (evento) {
    case "Festa junina" :
    console.log ('A Festa Junina é uma celebração tradicional brasileira, realizada em junho, com danças típicas como quadrilha, comidas regionais como canjica e pamonha, e roupas caipiras. A festividade é uma homenagem aos santos populares São João, São Pedro e Santo Antônio.');
break;
}

//7

let cal = 1;
switch (cal) {
    case cal === 1:
        console.log("Janeiro");
        break;
    case (cal === 2):
        console.log("Fevereiro");
        break;
    case (cal === 3):
        console.log("Março");
        break;
    case (cal === 4):
        console.log("Abril");
        break;
    case (cal === 6):
        console.log("Junho");
        break;
    case (cal === 7):
        console.log("Julho");
        break;
    case (cal === 8):
        console.log("Agosto");
        break;
    case (cal === 9):
        console.log("Setembro");
        break;
    case (cal === 10):
        console.log("Outubro");
        break;
    case (cal === 11):
        console.log("Novembro");
        break;
    case (cal === 12):
        console.log("Dezembro");
        break;

    default:
        console.log("nenhuma das alternativas")

}


