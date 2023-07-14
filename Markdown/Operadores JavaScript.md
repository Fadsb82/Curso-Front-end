# Operadores

## Aritméticos: retornam o resultado de uma operação

+ Somar

- Subtrair

* Multiplicar

/ Dividir

% Resto de divisão




## Comparadores matemáticos: teste lógico, retorno booleano (true / false):

< Menor que

> Maior que

<= Menor ou igual

>= Maior ou igual


# Atribuição 

a = 1
b = 4

a = b
a = 4



## Comparadores Lógicos: teste lógico, retorno booleano (true / false):

== Igualdade entre em sentenças (valor)

!= Diferença entre sentenças (valor)

=== Igualdade entre sentenças (valor e tipo)

!== Diferenças entre sentenças (valor e tipo)


## Operadores de lógica e junção lógica

!    NÃO (NOT)
&&    E  (AND)
||    OU (OR)

O sinal de exclamação (!) é o operador NOT (não), utilizado para negar a sentença quem vem na sequência.

#### Exemplos:

a != b // O valor de a é diferente de b

x !== y // O valor e o tipo e o tipo de x são diferentes de y

!a == b // O valor de a não igual ao valor de b


#### As condições lógicas são convertidas em números binários:

true é equivalente a 1

false é equivalente a 0


#### Operador lógico de atribuição

Tem a capacidade de atribuir valor a uma variável a partir de uma condição lógica, economiza IFs

Exemplo:

var meuCarro = color == "preto" ? "preto" : "branco";

## If

if (...) {
    ...
}

## Else 

else {

}

if (color == "preto"){
    meuCarro = "preto";
}else{
    meuCarro = "cinza";
}


## Else if 

else if (...){

}

Exemplo:

if (color == "preto"){
    meuCarro = "preto";
}else if (color == "vermelho"){
    meuCarro = "cinza";
}else if (color == "amarelo"){
    meuCarro = "branco";
}else{
    meuCarro = "azul";
}



## Switch

switch (color) {
    case 'branco' :
        meuCarro = 'branco';
        break;
    case 'vermelho' :
        meuCarro = 'vermelho';
        break;
    case 'amarelo' :
        meuCarro = 'amarelo';
        break;
    default :
    console.log('não temos a cor desejada)    
}

## media

var nota1 = 10;
var nota2 = 8;
var nota3 = 9;
var nota4 = 7;
var media = (nota1 + nota2 + nota3 + nota4) /4;
if (media > 8) {
    console.log("Aluno aprovado")
}else{
    console.log("Aluno em recuperação")
}

## Laços de Repetição (Loops)

for([expressaoInicial]; [condiçao]; [icremento])

while ( [condicao] ){
    [execucao]
}

var coontador = 0;

while ( c < 10) {
    contador++
}

var hora = 23;
while (hora > 0) {
   
    cosole.log(hora); 
    hora--;
}

do {
    execucao
} while ([condição]) {

}

...

 // Fazer a revisão no carro aos 10km
var km;
var revisao = 10;

for(km = 0; km < revisao; km++){
    console.log("pode rodar")
}

### Cálculo da média de alunos

var alunos = [
    [6, 7, 8, 6],
    [8, 5, 6, 8],
    [10, 6, 8, 7],
] 

var nota = 0;
for(var i = 0; i < alunos.lenght; i++){
    
    nota = 0;
    notasAluno = alunos[1]
    console.log("Aluno: " + i);
    console.log("Notas: " + notasAluno);

    for( c = 0; c < aluno.lenth; c++){    
        nota += aluno[c];
   }       


    media = nota /4

    if(media >= 7) {
        resultado = "Aprovado";
    }else{
        resultado = "Reprovado";
    }

    console.log("Media: " + media + " - " + resultado);    

}

## Funções

- Evitar repetição de código
- Realizar chamadas dinâmicas de algoritmos

function calcularMedia( notas ) { 

    var soma = 0;    
    for( c = 0; c < notas.length; c++) {
        soma += notas[c];
     }    

       media = soma / notas.length; 

       return media;

}

let media;//escopo global

function aprovacao ( notas ) {

       let media = calcularMedia( notas );//escopo da função
       
       let condicao = media >= 8 ? "aprovado" : "reprovado";
       
       return 'Media ' + media + ' -  Resultado: ' + condicao; 
}

//console.log( "Média: " + calcularMedia([7, 7, 7, 7]));
//console.log( aprovacao (calcularMedia([7, 8, 6, 9])));
console.log( aprovacao([8, 8, 7]));

//console.log( "Média: " + calcularMedia([4, 8, 7, 9]));
//console.log( aprovacao (calcularMedia([8, 6, 9, 10])));
console.log( aprovacao([8, 8, 10, 6]));

//console.log( "Média: " + calcularMedia([7, 5, 6, 8]));
//console.log( aprovacao (calcularMedia([5, 8, 7, 9])));
console.log( aprovacao([9, 6]));