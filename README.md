# Orcento

**Envie. Acompanhe. Feche.**

Orcento é uma landing page de validação para uma ideia de micro-SaaS voltada inicialmente para técnicos de ar-condicionado e outros prestadores de serviço que enviam orçamentos pelo WhatsApp.

A proposta é simples:

> Pare de perder clientes depois de enviar o orçamento.

O produto pretende permitir que o profissional crie propostas profissionais, envie pelo WhatsApp e acompanhe o que aconteceu depois do envio — incluindo visualizações, aceite e necessidade de follow-up.

## Objetivo atual

O Orcento ainda não é um SaaS completo.

Neste momento, o projeto tem como objetivo **validar a existência do problema e o interesse real de potenciais usuários antes do desenvolvimento do MVP**.

A landing page foi construída para medir sinais como:

* interesse na proposta;
* cliques nos CTAs;
* início e envio do formulário;
* quantidade de orçamentos enviados por mês;
* ferramenta utilizada atualmente;
* principal dor do profissional;
* intenção de testar o produto;
* intenção futura de pagamento;
* interesse em conversar diretamente pelo WhatsApp.

## Problema

Muitos prestadores de serviço enviam orçamentos por:

* WhatsApp;
* PDF;
* Excel;
* Canva;
* outros sistemas.

Depois do envio, frequentemente o cliente deixa de responder.

O profissional não sabe se:

* o cliente abriu o orçamento;
* achou o preço alto;
* esqueceu de responder;
* está comparando propostas;
* fechou com outro profissional.

O Orcento pretende transformar esse momento de incerteza em informação comercial útil.

## Proposta de valor

O foco não é apenas gerar orçamentos.

O principal diferencial é acompanhar o que acontece **depois que a proposta foi enviada**.

Fluxo conceitual:

```text
Criar orçamento
      ↓
Enviar pelo WhatsApp
      ↓
Cliente visualiza
      ↓
Acompanhar status
      ↓
Fazer follow-up
      ↓
Fechar o serviço
```

## Público inicial

O primeiro nicho de validação é:

**Técnicos de ar-condicionado.**

Caso a hipótese seja validada, o conceito poderá posteriormente atender outros prestadores de serviço, como:

* eletricistas;
* instaladores;
* pintores;
* marceneiros;
* profissionais de reformas;
* energia solar;
* fotógrafos;
* freelancers;
* outros profissionais autônomos.

## O que a landing demonstra

A interface apresenta uma simulação do produto futuro com recursos como:

* criação de orçamento;
* envio de proposta por link;
* visualização da proposta;
* quantidade de visualizações;
* última visualização;
* proposta aceita;
* proposta aguardando resposta;
* propostas ainda não visualizadas;
* identificação de clientes que precisam de follow-up.

Os dashboards e propostas exibidos na landing são **mockups de validação** e não representam um sistema já disponível.

## Validação

A landing captura interessados por meio de um formulário de acesso antecipado.

Atualmente são coletadas informações como:

* nome;
* WhatsApp;
* profissão;
* quantidade de orçamentos enviados por mês;
* ferramenta utilizada para criar orçamentos;
* principal dificuldade no processo atual.

Após o cadastro, o visitante também pode responder uma pergunta de intenção de pagamento e demonstrar um sinal mais forte de interesse entrando em contato pelo WhatsApp.

## Hipótese de preço

Como parte da validação, está sendo considerada inicialmente a hipótese de um plano na faixa de:

**R$ 19,90/mês**

Esse valor ainda não representa um preço definitivo do produto.

## Stack

A landing foi construída com:

* [Astro](https://astro.build/)
* Tailwind CSS
* HTML
* CSS
* JavaScript

Para captura inicial de leads:

* Formspree

A arquitetura foi propositalmente mantida simples para que o foco permaneça na validação do problema.

## Estrutura atual

```text
src/
├── pages/
│   ├── index.astro
│   └── obrigado.astro
│
└── styles/
    └── global.css

public/
├── favicon.png
└── og-image.png
```

## Executando localmente

Instale as dependências:

```bash
npm install
```

Inicie o ambiente de desenvolvimento:

```bash
npm run dev
```

O projeto estará disponível normalmente em:

```text
http://localhost:4321
```

## Build de produção

Para gerar o build:

```bash
npm run build
```

Os arquivos de produção serão gerados em:

```text
dist/
```

Para visualizar o build localmente:

```bash
npm run preview
```

## O que ainda não faz parte do projeto

Nesta fase, propositalmente não foram desenvolvidos:

* autenticação;
* login;
* dashboard real;
* cadastro de clientes;
* banco de dados próprio;
* financeiro completo;
* emissão fiscal;
* agenda;
* estoque;
* gestão de funcionários;
* aplicativo mobile;
* chatbot;
* recursos de IA.

A prioridade é validar o problema antes de aumentar o escopo.

## Possível MVP

Caso a validação seja positiva, uma primeira versão do produto poderá seguir este fluxo:

```text
Login
  ↓
Clientes
  ↓
Criar orçamento
  ↓
Gerar link público
  ↓
Enviar pelo WhatsApp
  ↓
Registrar visualização
  ↓
Cliente aceitar ou recusar
  ↓
Dashboard de propostas
```

Uma fase posterior poderá evoluir para acompanhamento de recebimentos e cobranças.

## Princípio do produto

Uma regra orienta o escopo inicial do Orcento:

> Se uma funcionalidade não ajuda o profissional a fechar uma venda ou receber dinheiro, ela não entra no produto inicial.

## Status

**Fase atual: validação da ideia.**

O objetivo neste momento é conversar com profissionais reais, observar comportamento, coletar dados da landing e decidir se existe evidência suficiente para desenvolver o MVP.

---

**Orcento**

Envie. Acompanhe. Feche.

