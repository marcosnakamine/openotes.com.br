---
layout: post
title: "[ES6 serie] Escopo e diferenças entre let e const"
date: "2016-12-23 12:35:50 -0200"
author:
    name: "Marcel Nakamine"
    url: "https://www.blogger.com/profile/15113696834989107891?rel=author"
    image: "//lh3.googleusercontent.com/zFdxGE77vvD2w5xHy6jkVuElKv-U9_9qLkRYK8OnbDeJPtjSZ82UPq5w6hJ-SA=w35"
categories: [ES6]
---
# Escopo de variáveis

## conceito

Temos 2 tipos de escopo:

- global
- local

Temos 3 formas de declarar variáveis no Javascript 2015 ou ES6:

- var
- let
- const

Vamos explorar cada um deles.

## var

### Exemplo de escopo global

``` Javascript
var minhaIdade = 26;
console.log(minhaIdade);
```

```
> 26
```

a variável *minhaIdade* está no escopo global sendo possível acessá-la em qualquer lugar do seu arquivo js.

### Exemplo de escopo local

``` Javascript
function quantosAnosTenho() {
  var minhaIdade = 26;
  console.log(`Tenho ${minhaIdade} anos.`);
}
console.log(`Acessando a variável ${minhaIdade} fora da função.`);
```

```
> Tenho 26 anos.
> ReferenceError: minhaIdade is not defined
```

Observe que na chamada da variável *minhaIdade* fora da função retornou erro. Isso porque *var* é escopo de função. Pra todas as outras formas ela será global. Note a diferença a seguir.

``` Javascript
var minhaIdade = 26;
if (minhaIdade > 12){
  var idadeDeCachorro = minhaIdade * 7;
  console.log(`Tenho ${minhaIdade} anos. E equivalente a idade de um cachorro seria de ${idadeDeCachorro}.`);
}
console.log(`Teria ${idadeDeCachorro} anos se fosse um cachorro.`);
```

```
> Tenho 26 anos. E equivalente a idade de um cachorro seria de 182.
> Teria 182 anos se fosse um cachorro.
```

A declaração da variável *idadeDeCachorro* é global mesmo estando dentro do bloco *if*.
Pra solucionar esse problema de escopo onde você não deveria ter acesso para evitar possíveis bugs, te apresento o *let* e o *const*

## let

### O escopo é por bloco.

``` Javascript
var minhaIdade = 26;
if (minhaIdade > 12){
  let idadeDeCachorro = minhaIdade * 7;
  console.log(`Tenho ${minhaIdade} anos. E equivalente a idade de um cachorro seria de ${idadeDeCachorro}.`);
}
console.log(`Teria ${idadeDeCachorro} anos se fosse um cachorro.`);
```

```
> Tenho 26 anos. E equivalente a idade de um cachorro seria de 182.
> ReferenceError: idadeDeCachorro is not defined
```

## const

### O escopo também é por bloco.

Quem for declarado com o *const* acaba possuindo o comportamento de uma constante. Assim você não poderá mudar a estrutura desse objeto.

``` Javascript
const nome = 'Marcel';
nome = 'Joao';
```

```
> TypeError: Assignment to constant variable.
```

Para Objetos, é um pouco diferente. Segue exemplos:

``` Javascript
const Pessoa = {
  nome: 'Marcel',
  idade: 26
}

console.log(Pessoa.nome);

Pessoa.nome = 'Érica';

console.log(Pessoa.nome);
```  

```
> Marcel
> Érica
```
