### Termos de acordos

Ao iniciar este projeto, você concorda com as diretrizes do Código de Ética e Conduta e do Manual da Pessoa Estudante da Trybe.

# Boas vindas ao repositório do projeto de ES6 e Testes Unitários!

Você já usa o GitHub diariamente para desenvolver os exercícios, certo? Agora, para desenvolver os projetos, você deverá seguir as instruções a seguir. Atenção a cada passo, e se tiver qualquer dúvida, nos envie por _Slack_! #vqv 🚀

Aqui você vai encontrar os detalhes de como estruturar o desenvolvimento do seu projeto a partir deste repositório, utilizando uma branch específica e um _Pull Request_ para colocar seus códigos.


---

## SUMÁRIO

- [Boas vindas ao repositório do projeto de Trivia!](#boas-vindas-ao-repositório-do-projeto-de-trivia)
- [Sumário](#sumário)
- [Habilidades](#habilidades)
- [Entregáveis](#entregáveis)
  - [O que deverá ser desenvolvido](#o-que-será-desenvolvido)
  - [Desenvolvimento](#desenvolvimento)
  - [Data de entrega](#data-de-entrega)
- [Instruções para entregar seu projeto](#instruções-para-entregar-seu-projeto)
  - [Antes de começar a desenvolver](#antes-de-começar-a-desenvolver)
  - [Durante o desenvolvimento](#durante-o-desenvolvimento)
- [Como desenvolver](#como-desenvolver)
  - [ESLint](#eslint)
- [Requisitos do projeto](#requisitos-do-projeto)
- [Lista de requisitos](#lista-de-requisitos)
  - [Implemente a função average](#1---implemente-a-função-average)
  - [Implemente os casos de teste para a função numbers](#2---implemente-os-casos-de-teste-para-a-função-numbers)
  - [Implemente a função vqv](#3---implemente-a-função-vqv)
  - [Implemente os casos de teste para a função circle](#4---implemente-os-casos-de-teste-para-a-função-circle)
  - [Implemente a função createStudent](#5---implemente-a-função-createstudent)
  - [Implemente os casos de teste para a função productDetails](#6---implemente-os-casos-de-teste-para-a-função-productdetails)
  - [Implemente a função objCalculator](#7---implemente-a-função-objcalculator)
  - [Implemente a função myCounter](#8---implemente-a-função-mycounter)
  - [Implemente os casos de teste e a função createMenu](#9---implemente-os-casos-de-teste-e-a-função-createmenu)
- [Depois de terminar o desenvolvimento (opcional)](#depois-de-terminar-o-desenvolvimento-opcional)
- [Revisando um pull request](#revisando-um-pull-request)
- [Avisos finais](#avisos-finais)

---

## Habilidades

Nesse projeto, você será capaz de:

- Escrever testes unitários para funções utilizando o módulo Assert do NodeJS para verificar o correto funcionamento dessas funções;
- A partir de testes já implementados, escrever funções de forma que elas atendam aos testes propostos;
- Escrever testes e funções utilizando uma abordagem de desenvolvimento orientado a testes.

---

# Entregáveis

Para entregar o seu projeto você deverá criar um Pull Request neste repositório.

Lembre-se que você pode consultar nosso conteúdo sobre
[Git & GitHub](https://course.betrybe.com/intro/git/) sempre que precisar!

---

## O que será desenvolvido

Você implementará várias funções para atender aos requisitos propostos e/ou testes unitários para garantir que as implementações das funções estão corretas.

---

## Desenvolvimento

* Nos testes unitários que não estão implementados, vocês verão um `assert.fail();`. Esse código deve ser removido a partir do momento que vocês começarem a escrever o teste unitário. Ele só existe para fazer o teste falhar. Se o `assert.fail();` não estivesse nos blocos em que não há testes unitários implementados ainda, o teste iria passar com sucesso, pois não haveria nada para ser testado dentro.

* Os comandos que você utilizará com mais frequência são:
  6. `npm test` _(executa todos os testes presentes na aplicação)_
  7. `npm test path/to/file` _(executa apenas os testes presentes no arquivo path/to/file)_
    * exemplo: `npm test tests/average.spec.js`
  8. `jest path/to/file` _(executa apenas os testes presentes no arquivo path/to/file)_
    * exemplo: `jest tests/average.spec.js`

---

## Data de entrega

  - Projeto individual;

  - Será um dia de projeto;

  - Data de entrega para avaliação final do projeto: `31/05/2021 - 14:00h`

---

# Instruções para entregar seu projeto:

## Antes de começar a desenvolver:

1. Clone o repositório
  * `git clone git@github.com:tryber/sd-012-project-js-unit-tests.git`.
  * Entre na pasta do repositório que você acabou de clonar:
    * `cd sd-012-project-js-unit-tests`

2. Instale as dependências
  * `npm install`

3. Crie uma branch a partir da branch `master`
  * Verifique que você está na branch `master`
    * Exemplo: `git branch`
  * Se não estiver, mude para a branch `master`
    * Exemplo: `git checkout master`
  * Agora crie uma branch para qual você vai submeter os `commits` do seu projeto
    * Você deve criar uma branch no seguinte formato: `nome-sobrenome-nome-do-projeto`
    * Exemplo: `git checkout -b joaozinho-abravanel-unit-tests`

4. Faça as alterações em, por exemplo, alguma das funções que precisam de implementação. Por exemplo, a `average.js` em `src/`:
```jsx
const average = () => {
  // add your implementation here
}

module.exports = average
```

5. Adicione as mudanças ao _stage_ do Git e faça um `commit`
  * Verifique que as mudanças ainda não estão no _stage_
    * Exemplo: `git status` (deve aparecer listado o arquivo _src/last.js_ em vermelho)
  * Adicione o arquivo alterado ao _stage_ do Git
      * Exemplo:
        * `git add .` (adicionando todas as mudanças - _que estavam em vermelho_ - ao stage do Git)
        * `git status` (deve aparecer listado o arquivo _src/last.js_ em verde)
  * Faça o `commit` inicial
      * Exemplo:
        * `git commit -m 'iniciando o projeto. VAMOS COM TUDO :rocket:'` (fazendo o primeiro commit)
        * `git status` (deve aparecer uma mensagem tipo _nothing to commit_ )

6. Adicione a sua branch com o novo `commit` ao repositório remoto
  * Usando o exemplo anterior: `git push -u origin joaozinho-abravanel-unit-tests`

7. Crie um novo `Pull Request` _(PR)_
  * Vá até a página de _Pull Requests_ do [repositório no GitHub](https://github.com/tryber/sd-012-project-js-unit-tests/pulls)
  * Clique no botão verde _"New pull request"_
  * Clique na caixa de seleção _"Compare"_ e escolha a sua branch **com atenção**
  * Clique no botão verde _"Create pull request"_
  * Adicione uma descrição para o _Pull Request_ e clique no botão verde _"Create pull request"_
  * **Não se preocupe em preencher mais nada por enquanto!**
  * Volte até a [página de _Pull Requests_ do repositório](https://github.com/tryber/sd-012-project-js-unit-tests/pulls) e confira que o seu _Pull Request_ está criado

---

## Durante o desenvolvimento

:warning: **PULL REQUESTS COM ISSUES NO LINTER NÃO SERÃO AVALIADAS, ATENTE-SE PARA RESOLVÊ-LAS ANTES DE FINALIZAR O DESENVOLVIMENTO!** :warning:

* Faça `commits` das alterações que você fizer no código regularmente

* Lembre-se de sempre após um (ou alguns) `commits` atualizar o repositório remoto

* Os comandos que você utilizará com mais frequência são:
  1. `git status` _(para verificar o que está em vermelho - fora do stage - e o que está em verde - no stage)_
  2. `git add` _(para adicionar arquivos ao stage do Git)_
  3. `git commit` _(para criar um commit com os arquivos que estão no stage do Git)_
  4. `git push -u nome-da-branch` _(para enviar o commit para o repositório remoto na primeira vez que fizer o `push` de uma nova branch)_
  5. `git push` _(para enviar o commit para o repositório remoto após o passo anterior)_

---

## Como desenvolver

Este repositório contém um _template_ de uma aplicação **NodeJS** (observe a existência do arquivo _package.json_).
Após clonar o projeto e instalar as dependências, você não precisará realizar nenhuma configuração adicional.
Todos os arquivos estritamente necessários para finalizar o projeto já estão criados, **não** sendo necessária a criação de outros arquivos.
Você deverá completar as funções e testes unitários de forma a satisfazer os requisitos listados na seção **Lista de requisitos**.

As funções a serem implementadas estão dentro da pasta `src` e seus respectivos testes estão na pasta `tests`.
O nome dos arquivos também seguem uma ordem definida. Basicamente, os arquivos de teste possuem o nome do arquivo alvo (arquivo da funcionalidade) acrescido do nome `.spec.js`.
Existirá um arquivo `src/exemplo.js` que conterá a implementação de uma função e um arquivo `tests/exemplo.spec.js` com os testes unitários referentes à função presente no arquivo `src/exemplo.js`.

Cada função possui um bloco de comentários em suas primeiras linhas explicando qual é o trabalho que a função deve realizar.

Você só deve alterar os arquivos indicados nos requisitos. **Os arquivos que não estão indicados nos requisitos não devem ser alterados, ou sua avaliação poderá ser comprometida.**

Para entregar o seu projeto você deverá criar um _Pull Request_ neste repositório. Este _Pull Request_ deverá conter a implementação dos arquivos solicitados abaixo.

**⚠️ É importante que seus arquivos tenham exatamente estes nomes! ⚠️**. Apesar de não ser necessário para ser aprovado no projeto, você pode adicionar outros arquivos se julgar necessário. Qualquer dúvida, procure o time de instrução no Slack.

Lembre-se que você pode consultar nosso conteúdo sobre [Git & GitHub](https://course.betrybe.com/intro/git/) sempre que precisar!

### EsLint

Usaremos o [ESLint](https://eslint.org/) para fazer a análise estática do seu código.

Para garantir a qualidade do seu código de forma a tê-lo mais legível, de mais fácil manutenção e seguindo as boas práticas de desenvolvimento, nós utilizamos neste projeto o linter `ESLint`. Para rodar o linter localmente no seu projeto, execute o comando abaixo:

```bash
npm run lint
```

Caso ainda fique alguma dúvida, você pode consultar nosso conteúdo sobre [`ESLint`](https://app.betrybe.com/course/real-life-engineer/eslint)

Você pode também instalar o plugin do `ESLint` no `VSCode`, bastar ir em extensions e baixar o [plugin `ESLint`](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint).

---

## Requisitos do projeto

 **PULL REQUESTS COM ISSUES DE LINTER NÃO SERÃO AVALIADAS. ATENTE-SE PARA RESOLVÊ-LAS ANTES DE FINALIZAR O DESENVOLVIMENTO!** ⚠

### 1 - Implemente a função `average`

A função average recebe um array (tamanho variável) e retorna a média dos valores recebidos. Caso a função receba algum valor não númerico ou um array vazio, o valor undefined deve ser retornado. Todos os resultados devem ser arredondados para valores inteiros. Ex: 4,6 vira 5; 1,3 vira 1. O arquivo `average.spec.js` contém os testes para `average` já implementados. Implemente a função no arquivo `src/average.js` de forma que ela atenda aos testes propostos.

  **O que será avaliado**

  * Será validado se o comportamento da função "average" está correto.

### 2 - Implemente os casos de teste para a função `numbers`

 A função `numbers` recebe um array (tamanho variável) e retorna true se todos os parâmetros forem do tipo 'number' e false caso contrário. Essa função já está implementada no arquivo `src/numbers.js`. Escreva os testes para essa função para garantir que a implementação de `numbers` está correta.

  **O que será avaliado**

  * Será validado se o teste da função `numbers` verifica se o retorno da função é um array e se o array retornado contém somente números.

### 3 - Implemente a função `vqv`

Use template literals para escrever uma função que recebe seu nome e sua idade e retorna o parágrafo descrito abaixo:

```javascript
`'Oi, meu nome é Tunico!
Tenho 30 anos,
trabalho na Trybe e mando muito em programação!
#VQV!'`
```

Caso a função seja chamada sem nenhum parâmetro, o valor undefined deve ser retornado. O arquivo `vqv.spec.js` contém os testes para `vqv` já implementados. Implemente a função no arquivo `src/vqv.js` de forma que ela atenda aos testes propostos.

  **O que será avaliado**

  * Será validado se a função `vqv` retorna a frase esperada com nome e idade.

### 4 - Implemente os casos de teste para a função `circle`

A função `circle` recebe o raio de um círculo e retorna um objeto contendo suas informações (Raio, Área e Circunferência). Se não for especificado um raio, a função retorna `undefined`. Essa função já está implementada no arquivo `src/circle.js`. Escreva os testes para essa função para garantir que a implementação de `circle` está correta.

  **O que será avaliado**

  * Será validado se o teste da função `circle` verifica se ao receber um raio, o retorno da função é um objeto com as informações corretas (Raio, Área e Circunferência).

### 5 - Implemente a função `createStudent`

A função `createStudent` recebe como parâmetro um nome, e retorna um objeto contendo duas chaves:
    (1) name, contendo o nome passado como parâmetro;
    (2) feedback, contendo uma função que retorna a frase 'Eita pessoa boa!' ao ser chamada.
O arquivo `createStudent.spec.js` contém os testes para `createStudent` já implementados. Implemente a função no arquivo `src/createStudent.js` de forma que ela atenda aos testes propostos.

  **O que será avaliado**

  * Será validado se a função `createStudent` retorna o objeto esperado.

### 6 - Implemente os casos de teste para a função `productDetails`

A função `productDetails` recebe duas strings que representam nomes de produtos, e retorna um array contendo dois objetos com os detalhes dos respectivos produtos:

```javascript
productDetails('Alcool gel', 'Máscara') // Retorna:
  [
    {
      name: 'Alcool gel'
      details: {
        productId: 'Alcool gel123'
      }
    },
    {
      name: 'Máscara'
      details: {
        productId: 'Máscara123'
      }
    }
  ]
```

Essa função já está implementada no arquivo `src/productDetails.js`. Escreva os testes para essa função no arquivo `tests/productDetails.js` para garantir que a implementação de `productDetails` está correta.

  **O que será avaliado**

  * Será validado se o teste da função `productDetails` verifica se ao receber duas strings, o retorno da função é um array de objetos e se cada objeto contém os dados necessários.

### 7 - Implemente a função `objCalculator`
Desenvolva um objeto calculator que possui quatro chaves:
  - add;
  - mult;
  - div;
  - sub.

Para cada uma delas atribua uma função que realiza a respectiva operação. A função deve receber dois inteiros e retornar um inteiro. Os resultados das divisões devem sempre ser arredondados para baixo. O arquivo `objCalculator.spec.js` contém os testes para `objCalculator` já implementados. Implemente a função no arquivo `src/objCalculator.js` de forma que ela atenda aos testes propostos.

  **O que será avaliado**

  * Será validado se a função `objCalculator` retorna os valores esperados.

### 8 - Implemente a função `myCounter`
A função myCounter possui dois loops aninhados que inserem valores dentro de um array. Como podemos perceber, eles vão adicionando valores ao array até sua condição de parada. Corrija a função `myCounter` para que a função retorne o array correto. O arquivo `myCounter.spec.js` contém os testes para `myCounter` já implementados. Implemente a função no arquivo `src/myCounter.js` de forma que ela atenda aos testes propostos.

  **O que será avaliado**

  * Será validado se a função `myCounter` retorna os dados esperados.

### 9 - Implemente os casos de teste e a função `createMenu`

**Agora prepare-se! Esse último requisito vai te guiar através de um longo e rico processo de desenvolvimento orientado a testes (Test Driven Development, ou TDD). Dará trabalho, mas vale a pena!**

Você é responsável por escrever o código do sistema de pedidos de um restaurante. Deve ser possível, através desse sistema, cadastrar um menu. Dado que um menu foi cadastrado, o sistema deve disponibilizar um objeto através do qual se consegue:
  - ler o menu cadastrado;
  - fazer pedidos;
  - verificar o que foi pedido;
  - somar o valor da conta.

A estrutura deste código e deste objeto já foi definida e você irá implementá-lo. Você encontrará mais detalhes sobre a estrutura a ser seguida e exemplos do retorno da função no arquivo `src/restaurant.js`. Você deverá seguir o passo-a-passo a seguir para garantir o bom desenvolvimento do sistema.

  1. No arquivo `tests/restaurant.spec.js`, escreva um teste que verifica se a função `createMenu()`, retorna um objeto que possui, mas não é necessariamente é limitado à chave `fetchMenu`, a qual tem como valor uma função.
  2. No arquivo `tests/restaurant.spec.js`, escreva um teste que verifica se, dado que a função `createMenu` foi chamada com o objeto: `{ food: {}, drink: {} }`, checa se `'objetoRetornado.fetchMenu()'` retorna um objeto cujas chaves são somente `food` e `drink`.
  3. No arquivo `tests/restaurant.spec.js`, escreva um teste que verifica se o menu passado pra função `createMenu` é identico ao menu recuperado pela função `'objetoRetornado.fetchMenu()'`.
  4. No arquivo `src/restaurant.js`, crie uma função `createMenu()` que, dado um objeto passado por parâmetro, retorna um objeto com o seguinte formato: { fetchMenu: () => objetoPassadoPorParametro }.
  5. No arquivo `tests/restaurant.spec.js`, escreva um teste que verifica se `'objetoRetornado.consumption'`, após a criação do menu, retorna um array vazio.
  6. No arquivo `src/restaurant.js`, adicione ao objeto retornado por `createMenu` uma chave `consumption` que, como valor inicial, tem um array vazio.
  7. No arquivo `tests/restaurant.spec.js`, escreva um teste que verifica se ao chamar uma função associada à chave `order` no objeto retornado, passando uma string como parâmetro, como `objetoRetornado.order('coxinha')`, tal string é adicionada ao array retornado em `objetoRetornado.consumption
  8. No arquivo `src/restaurant.js`, crie uma função, separada da função `createMenu()`, que, dada uma string recebida por parâmetro, adiciona essa string ao array de `objetoRetornado.consumption`. Adicione essa função à chave `order`.
  9. No arquivo `tests/restaurant.spec.js`, escreva um teste que verifica se as três orders seguintes, de bebidas e comidas mescladas, somam três itens no array `objetoRetornado.consumption` conforme os itens pedidos.
  10. No arquivo `tests/restaurant.spec.js`, escreva um teste que verifica se a função `order` aceita que pedidos repetidos sejam acrescidos a consumption.
  11. No arquivo `tests/restaurant.spec.js`, escreva um teste que verifica que, ao chamar `objetoRetornado.pay()`, retorna-se a soma dos preços de tudo que foi pedido, conforme registrado em `objetoRetornado.consumption`.
  12. No arquivo `src/restaurant.js`, adicione ao objeto retornado por `createMenu()` uma chave `pay` com uma função que varre todo os itens de `objetoRetornado.consumption`, soma o preço de todos checando-os no menu e retorna o valor somado acrescido de 10%. DICA: para isso, você precisará varrer tanto o objeto da chave `food` quanto o objeto da chave `drink`.


  **O que será avaliado**

  * Será validado se a função `createMenu` retorna os dados esperados.
  * Será validado se o teste da função `createMenu` verifica cada um dos retornos da função e se estes retornos têm o comportamento esperado.

---

## Depois de terminar o desenvolvimento (opcional)

Para sinalizar que o seu projeto está pronto para o _"Code Review"_ das outras pessoas da sua turma, faça o seguinte:

* Vá até a página **DO SEU** _Pull Request_, adicione a label de _"code-review"_ e marque outras pessoas estudantes:

  * No menu à direita, clique no _link_ **"Labels"** e escolha a _label_ **code-review**;

  * No menu à direita, clique no _link_ **"Assignees"** e escolha **o seu usuário**;

  * No menu à direita, clique no _link_ **"Reviewers"** e digite `students`, selecione o time `tryber/students-sd-012`.

Caso tenha alguma dúvida, [aqui tem um video explicativo](https://vimeo.com/362189205).

### Revisando um pull request

Use o conteúdo sobre [Code Review](https://course.betrybe.com/real-life-engineer/code-review/) para te ajudar a revisar os _Pull Requests_.

#VQV 🚀

---

## Avisos finais

Ao finalizar e submeter o projeto, não se esqueça de avaliar sua experiência preenchendo o formulário. Leva menos de 3 minutos!

Link: [FORMULÁRIO DE AVALIAÇÃO DE PROJETO](https://be-trybe.typeform.com/to/ZTeR4IbH#cohort_name=Turma%2012)

O avaliador automático não necessariamente avalia seu projeto na ordem em que os requisitos aparecem no readme. Isso acontece para deixar o processo de avaliação mais rápido 😉.
