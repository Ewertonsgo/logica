var nome, altura, idade, maiorDeidade;


nome = window.prompt('Qual o seu nome?');
altura = Number(window.prompt('Qual é a sua altura?'));
idade = Number(window.prompt('Qual a sua idade ?'));
maiorDeidade = false;
if (idade >= 18) {
  maiorDeidade = true;
}
window.alert(nome);
window.alert(altura);
window.alert(idade);
window.alert(maiorDeidade);
