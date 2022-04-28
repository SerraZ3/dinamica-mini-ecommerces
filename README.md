# Ecommerces

## Petshop

### Descrição

"Possuo um petshop onde realizo atendimento de pets (cachorros e gatos) e vendo itens, alimentos e roupas para eles" - José

### Funcionalidades

#### 1- Cadastro de ração

No array de ração, adicione um objeto no final desse array e liste as rações

```js
var racao = [
  {
    marca: "Biofresh",
    preco: 50.5,
    porte: "grande",
    especie: "cachorro",
  },
  {
    marca: "Golden",
    preco: 120,
    porte: "pequeno",
    especie: "cachorro",
  },
  {
    marca: "Whiskas",
    preco: 120,
    porte: "pequeno",
    especie: "gato",
  },
];
```

#### 2- Cadastro de pet

No array de pet, adicione um objeto no final desse array e liste os pets

```js
var pet = [
  {
    raca: "Buldogue",
    especie: "cachorro",
    dono: "Henrique",
    idade: 8,
  },
  {
    raca: "Pastor Alemão",
    especie: "cachorro",
    dono: "Paula",
    idade: 4,
  },
  {
    raca: "Sphynx",
    especie: "gato",
    dono: "José",
    idade: 1,
  },
];
```

#### 3- Buscar por um cliente

Pegar id do cliente e retorna o mesmo e caso não exista retorne a mensagem "Cliente não encontrado"

```js
var cliente = [
  {
    id: 1,
    nome: "Rogério Lucas",
    sobrenome: "Silva",
    idade: 30,
    contato: "4002-8922",
  },
  {
    id: 2,
    nome: "Roberto Carlos",
    sobrenome: "Braga",
    idade: 70,
    contato: "(11) 9 1111-1111",
  },
  {
    id: 3,
    nome: "Sylvester",
    sobrenome: "Stallone",
    idade: 80,
    contato: "(22) 9 2222-2222",
  },
];
```

#### 4- Cadastro de cliente

No array de cliente, adicione um objeto no final desse array e liste os clientes

```js
var cliente = [
  {
    id: 1,
    nome: "Rogério Lucas",
    sobrenome: "Silva",
    idade: 30,
    contato: "4002-8922",
  },
  {
    id: 2,
    nome: "Roberto Carlos",
    sobrenome: "Braga",
    idade: 70,
    contato: "(11) 9 1111-1111",
  },
  {
    id: 3,
    nome: "Sylvester",
    sobrenome: "Stallone",
    idade: 80,
    contato: "(22) 9 2222-2222",
  },
];
```

#### 5- Listar clientes entre duas idades

Crie uma função que ao receber a idade inicial e final e em seguida retorne todos os clientes que estão nesse intervalo

```js
var cliente = [
  {
    id: 1,
    nome: "Rogério Lucas",
    sobrenome: "Silva",
    idade: 30,
    contato: "4002-8922",
  },
  {
    id: 2,
    nome: "Roberto Carlos",
    sobrenome: "Braga",
    idade: 70,
    contato: "(11) 9 1111-1111",
  },
  {
    id: 3,
    nome: "Sylvester",
    sobrenome: "Stallone",
    idade: 80,
    contato: "(22) 9 2222-2222",
  },
];
```

#### 6- Listar clientes que começam com uma determinada letra

Crie uma função que receba uma letra e retorne todos os clientes que começam com a mesma letra

```js
var cliente = [
  {
    id: 1,
    nome: "Rogério Lucas",
    sobrenome: "Silva",
    idade: 30,
    contato: "4002-8922",
  },
  {
    id: 2,
    nome: "Roberto Carlos",
    sobrenome: "Braga",
    idade: 70,
    contato: "(11) 9 1111-1111",
  },
  {
    id: 3,
    nome: "Sylvester",
    sobrenome: "Stallone",
    idade: 80,
    contato: "(22) 9 2222-2222",
  },
];
```

## Restaurante vegano

## Restaurante Japonês

## Roupas de nenêm

## Roupas de dogs

## Distribuidora de cervejas artesanais

## Livraria online

## Roupas e materiais Geek

### Descrição

"Nós temos uma loja online de itens da cultura pop/geek e trabalhando vendo-os" -  Carlos e Daniel

### Funcionalidades

#### 1 - Cadastro de produtos

No array de `produtos`, adicione um objeto no final desse array e liste os produtos

```js
var produtos = [
  {
    nome: "Camiseta Meu Amigo Totoro",
    preco: 59.99,
    tamanho: "G",
    tipo: "vestuario",
    qtd: 120,
  },
  {
    nome: "Poster Star Wars",
    preco: 20.25,
    tipo: "decoração"
    qtd: 1420,
  },
  {
    nome: "Luminaria DC (Limitada)",
    preco: 90.0,
    tipo: "decoração",
    qtd: 100
  },
];
```

#### 2- Cadastro de itens exclusivos

No array de exclusivos, adicione um objeto no final desse array e liste todos os itens

```js
var exclusivos = [
  {
    nome: "Baralho do Cthulhu,
    dataLancamento: '02/02/2022',
    ehBrinde: false,
    brand: 'Lovecraft'
  },
  {
    nome: "Omnitrix",
    dataLancamento: '07/07/2022',
    ehBrinde: true,
    brand: 'Ben 10'
  },
];
```

#### 3- Buscar por um cliente

Pegar id do cliente e retorna o mesmo e caso não exista retorne a mensagem "Cliente não encontrado"

```js
var cliente = [
  {
    id: 1,
    nome: "Rogério Lucas",
    sobrenome: "Silva",
    idade: 30,
    contato: "4002-8922",
  },
  {
    id: 2,
    nome: "Roberto Carlos",
    sobrenome: "Braga",
    idade: 70,
    contato: "(11) 9 1111-1111",
  },
  {
    id: 3,
    nome: "Sylvester",
    sobrenome: "Stallone",
    idade: 80,
    contato: "(22) 9 2222-2222",
  },
];
```

#### 4- Cadastro de cliente

No array de cliente, adicione um objeto no final desse array e liste os clientes

```js
var cliente = [
  {
    id: 1,
    nome: "Rogério Lucas",
    sobrenome: "Silva",
    idade: 30,
    contato: "4002-8922",
  },
  {
    id: 2,
    nome: "Roberto Carlos",
    sobrenome: "Braga",
    idade: 70,
    contato: "(11) 9 1111-1111",
  },
  {
    id: 3,
    nome: "Sylvester",
    sobrenome: "Stallone",
    idade: 80,
    contato: "(22) 9 2222-2222",
  },
];
```

#### 5- Listar clientes entre duas idades

Crie uma função que ao receber a idade inicial e final e em seguida retorne todos os clientes que estão nesse intervalo

```js
var cliente = [
  {
    id: 1,
    nome: "Rogério Lucas",
    sobrenome: "Silva",
    idade: 30,
    contato: "4002-8922",
  },
  {
    id: 2,
    nome: "Roberto Carlos",
    sobrenome: "Braga",
    idade: 70,
    contato: "(11) 9 1111-1111",
  },
  {
    id: 3,
    nome: "Sylvester",
    sobrenome: "Stallone",
    idade: 80,
    contato: "(22) 9 2222-2222",
  },
];
```

#### 6- Listar clientes que começam com uma determinada letra

Crie uma função que receba uma letra e retorne todos os clientes que começam com a mesma letra

```js
var cliente = [
  {
    id: 1,
    nome: "Rogério Lucas",
    sobrenome: "Silva",
    idade: 30,
    contato: "4002-8922",
  },
  {
    id: 2,
    nome: "Roberto Carlos",
    sobrenome: "Braga",
    idade: 70,
    contato: "(11) 9 1111-1111",
  },
  {
    id: 3,
    nome: "Sylvester",
    sobrenome: "Stallone",
    idade: 80,
    contato: "(22) 9 2222-2222",
  },
];
```


## Loja esportiva (roupa, bolas...)

### Descrição

"Eu sou gerente de uma loja de artigos esportivos e vendo camisas e alugo outros tipos de produtos, preciso de sistema para gerenciar meu estoque" -  Júlia

### Funcionalidades

#### 1 - Cadastro de camisas

No array de `camisas`, adicione um objeto no final desse array e liste os camisas

```js
var camisas = [
  {
    nome: "Fiorentina Retrô Batistuta",
    preco: 200,
    ano: "1998",
    clube: "Fiorentina",
    qtd: 40,
  },
  {
    nome: "Lazio Retrô",
    preco: 120.54,
    ano: "1978",
    clube: "Lazio",
    qtd: 12,
  },
  {
    nome: "Newll's Old Boys Retrô",
    preco: 150,90,
    ano: null,
    clube: "Newll's Old Boys",
    qtd: 54,
  },
];
```

#### 2- Cadastro de equipamentos

No array de `equipamentos`, adicione um objeto no final desse array e liste todos os equipamentos

```js
var equipamentos = [
  {
    nome: 'Estreita Eletrônica',
    tipo: 'estreita',
    estaAlugado: true,
    dataDeDevolucao: '01/06/2022'
  },
  {
    nome: 'Conjunto de bolas de futebol',
    tipo: 'artigos esportivos',
    estaAlugado: false,
    dataDeDevolucao: null
  },
  {
    nome: 'Estacao de musculação',
    tipo: 'academia',
    estaAlugado: true,
    dataDeDevolucao: '05/05/2022'
  },
];
```

#### 3- Buscar por um cliente

Pegar id do cliente e retorna o mesmo e caso não exista retorne a mensagem "Cliente não encontrado"

```js
var cliente = [
  {
    id: 1,
    nome: "Rogério Lucas",
    sobrenome: "Silva",
    idade: 30,
    contato: "4002-8922",
  },
  {
    id: 2,
    nome: "Roberto Carlos",
    sobrenome: "Braga",
    idade: 70,
    contato: "(11) 9 1111-1111",
  },
  {
    id: 3,
    nome: "Sylvester",
    sobrenome: "Stallone",
    idade: 80,
    contato: "(22) 9 2222-2222",
  },
];
```

#### 4- Cadastro de cliente

No array de cliente, adicione um objeto no final desse array e liste os clientes

```js
var cliente = [
  {
    id: 1,
    nome: "Rogério Lucas",
    sobrenome: "Silva",
    idade: 30,
    contato: "4002-8922",
  },
  {
    id: 2,
    nome: "Roberto Carlos",
    sobrenome: "Braga",
    idade: 70,
    contato: "(11) 9 1111-1111",
  },
  {
    id: 3,
    nome: "Sylvester",
    sobrenome: "Stallone",
    idade: 80,
    contato: "(22) 9 2222-2222",
  },
];
```

#### 5- Listar clientes entre duas idades

Crie uma função que ao receber a idade inicial e final e em seguida retorne todos os clientes que estão nesse intervalo

```js
var cliente = [
  {
    id: 1,
    nome: "Rogério Lucas",
    sobrenome: "Silva",
    idade: 30,
    contato: "4002-8922",
  },
  {
    id: 2,
    nome: "Roberto Carlos",
    sobrenome: "Braga",
    idade: 70,
    contato: "(11) 9 1111-1111",
  },
  {
    id: 3,
    nome: "Sylvester",
    sobrenome: "Stallone",
    idade: 80,
    contato: "(22) 9 2222-2222",
  },
];
```

#### 6- Listar clientes que começam com uma determinada letra

Crie uma função que receba uma letra e retorne todos os clientes que começam com a mesma letra

```js
var cliente = [
  {
    id: 1,
    nome: "Rogério Lucas",
    sobrenome: "Silva",
    idade: 30,
    contato: "4002-8922",
  },
  {
    id: 2,
    nome: "Roberto Carlos",
    sobrenome: "Braga",
    idade: 70,
    contato: "(11) 9 1111-1111",
  },
  {
    id: 3,
    nome: "Sylvester",
    sobrenome: "Stallone",
    idade: 80,
    contato: "(22) 9 2222-2222",
  },
];
```


## Viagem

### Descrição

"Sou dono de uma agencia de viagens e preciso de um sistema onde possa cadastrar serviços como: passeios, pacotes e meus clientes" -  Marcelo

### Funcionalidades

#### 1 - Cadastro de pacote

No array de `pacotes`, adicione um objeto no final desse array e liste os pacotes

```js
var pacotes = [
  {
    nome: "Gramado",
    preco: 3670.89,
    hotel: "Gran Palace",
    temTransfer: true,
    qtdDias: 12,
  },
  {
    nome: "Porto de galinhas",
    preco: 5270.25,
    hotel: "Pedras Altas",
    temTransfer: false,
    qtdDias: 12,
  },
  {
    nome: "Fernando de Noronha",
    preco: 8730.99,
    hotel: "Pousada Mar Aberto",
    temTransfer: false,
    qtdDias: 12,
  },
];
```

#### 2- Cadastro de passeios

No array de passeios, adicione um objeto no final desse array e liste todos os passeios

```js
var passeios = [
  {
    nome: "Meet Rio",
    precoPorAdulto: 369.00,
    precoPorCrianca: 150,
    incluiRefeicao: true,
    duracao: '8 horas'
  },
  {
    nome: "Boat Tour Santos",
    precoPorAdulto: 180,
    precoPorCrianca: null,
    incluiRefeicao: true,
    duracao: '3 horas'
  },
  {
    nome: "Reveillon a Bordo",
    precoPorAdulto: 420,
    precoPorCrianca: 210,
    incluiRefeicao: true,
    duracao: '7 hrs'
  },
];
```

#### 3- Buscar por um cliente

Pegar id do cliente e retorna o mesmo e caso não exista retorne a mensagem "Cliente não encontrado"

```js
var cliente = [
  {
    id: 1,
    nome: "Rogério Lucas",
    sobrenome: "Silva",
    idade: 30,
    contato: "4002-8922",
  },
  {
    id: 2,
    nome: "Roberto Carlos",
    sobrenome: "Braga",
    idade: 70,
    contato: "(11) 9 1111-1111",
  },
  {
    id: 3,
    nome: "Sylvester",
    sobrenome: "Stallone",
    idade: 80,
    contato: "(22) 9 2222-2222",
  },
];
```

#### 4- Cadastro de cliente

No array de cliente, adicione um objeto no final desse array e liste os clientes

```js
var cliente = [
  {
    id: 1,
    nome: "Rogério Lucas",
    sobrenome: "Silva",
    idade: 30,
    contato: "4002-8922",
  },
  {
    id: 2,
    nome: "Roberto Carlos",
    sobrenome: "Braga",
    idade: 70,
    contato: "(11) 9 1111-1111",
  },
  {
    id: 3,
    nome: "Sylvester",
    sobrenome: "Stallone",
    idade: 80,
    contato: "(22) 9 2222-2222",
  },
];
```

#### 5- Listar clientes entre duas idades

Crie uma função que ao receber a idade inicial e final e em seguida retorne todos os clientes que estão nesse intervalo

```js
var cliente = [
  {
    id: 1,
    nome: "Rogério Lucas",
    sobrenome: "Silva",
    idade: 30,
    contato: "4002-8922",
  },
  {
    id: 2,
    nome: "Roberto Carlos",
    sobrenome: "Braga",
    idade: 70,
    contato: "(11) 9 1111-1111",
  },
  {
    id: 3,
    nome: "Sylvester",
    sobrenome: "Stallone",
    idade: 80,
    contato: "(22) 9 2222-2222",
  },
];
```

#### 6- Listar clientes que começam com uma determinada letra

Crie uma função que receba uma letra e retorne todos os clientes que começam com a mesma letra

```js
var cliente = [
  {
    id: 1,
    nome: "Rogério Lucas",
    sobrenome: "Silva",
    idade: 30,
    contato: "4002-8922",
  },
  {
    id: 2,
    nome: "Roberto Carlos",
    sobrenome: "Braga",
    idade: 70,
    contato: "(11) 9 1111-1111",
  },
  {
    id: 3,
    nome: "Sylvester",
    sobrenome: "Stallone",
    idade: 80,
    contato: "(22) 9 2222-2222",
  },
];
```
