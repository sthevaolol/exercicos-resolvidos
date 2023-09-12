## 1. Problema: Calcular a média

//Descrição: Escreva um programa que receba três números como entrada e retorne a média desses números.

<script>
      //resolução
 function media (a, b, c) {
    var n1 = ((a + b + c) / 3)
    console.log(`a média entre ${a}, ${b} e ${c} é ${n1}`)
}

media (10, 10, 10)

</script>

         -------------------- // ------------


## 2. Problema: Verificar número par

Descrição: Escreva um programa que verifique se um número dado é par. O programa deve exibir "É par" se for par, e "Não é par" caso contrário.

<script>
        // digite na variável a baixo qualquer número :)
    var n2 = 5
    if (n2 % 2 === 0) {
        console.log(`é par`)
    } else {
        console.log(`é impar`)
    }

</script>

    ------------------------- // --------------------

## 3. Problema: Contar vogais

Descrição: Escreva um programa que conte o número de vogais em uma string dada. Considere apenas as letras minúsculas (a, e, i, o, u) como vogais.

<script>
function contarVogais(frase) {
   // Converte a frase para letras minúsculas.
  frase = frase.toLowerCase();
  const vogais = ['a', 'e', 'i', 'o', 'u'];
  const contador = {};
  for (let i = 0; i < frase.length; i++) {
    const caractere = frase[i];
    
    // Verifica se o caractere é uma vogal
    if (vogais.includes(caractere)) {
      if (contador[caractere]) {
        contador[caractere]++;
      } else {
        contador[caractere] = 1;
      }
    }
  }
  
  return contador;
}

// Exemplo
const frase = "Macaco";
const resultado = contarVogais(frase);
console.log(resultado);

</script>

         -------------------------------- // ------------------------


## 4. Problema: Verificar palíndromo

Descrição: Escreva um programa que verifique se uma palavra dada é um palíndromo. Um palíndromo é uma palavra que pode ser lida da mesma forma tanto da esquerda para a direita quanto da direita para a esquerda.

<script>
    

function ePalindromo(str) {
  // Remove espaços em branco e converte para letras minúsculas
  str = str.replace(/\s/g, '').toLowerCase();
  
  // Inverte a string
  const reversedStr = str.split('').reverse().join('');
  
  // Verifica se a string original é igual à string invertida
  return str === reversedStr;
}

// Exemplo
const palavra = "arara";
const resultado = ePalindromo(palavra);

if (resultado) {
  console.log(palavra + " é um palíndromo.");
} else {
  console.log(palavra + " não é um palíndromo.");
}
</script>

            -------------------------------- // -------------------

## 5. Problema: Tabuada de multiplicação

Descrição: Escreva um programa que exiba a tabuada de multiplicação de um número dado. O programa deve exibir a multiplicação de 1 a 10 para o número fornecido.


<script>

function tabuadaDeMultiplicacao(numero, limite) {
  for (let i = 1; i <= limite; i++) {
    const resultado = numero * i;
    console.log(`${numero} x ${i} = ${resultado}`);
  }
}

// Exemplo de uso para gerar a tabuada do 5 até o limite de 10
// Digite um número e o limite.

const numero = 1;
const limite = 10;
tabuadaDeMultiplicacao(numero, limite);

</script>







## FEITO POR:
Sthevão Marques Ferreira
RA: 6923205429
Sala: 325
Noturno