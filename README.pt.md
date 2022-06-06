# Processamento de pagamento com cartão via Checkout Bricks

[English](README.md) / [Español](README.es.md)

## :computer: Tecnologias

- Node.js
- [NPM](https://www.npmjs.com) (dependency manager)
- Express

## 💡 Requisitos

- Node.js 10 ou mais recente (você pode baixar [aqui](https://nodejs.org/)).
- [Leia nossas instruções](https://www.mercadopago.com/developers/pt/docs/getting-started) sobre como criar uma aplicação no Painel de Desenvolvedores do Mercado Pago para obter a public key e o access token. Essas chaves irão te dar acesso às APIs do Mercado Pago.

## :gear: Instalação

1. Clone o projeto.

```bash
git clone https://github.com/mercadopago/card-payment-bricks-sample-node.git
```

2. Acesse a pasta raiz do projeto.

```bash
cd card-payment-bricks-sample-node
```

3. Instale as dependências necessárias.

```bash
npm install
```

## 🌟 Como executar

1. Execute o seguinte comando para iniciar a aplicação:

```bash
MERCADO_PAGO_SAMPLE_PUBLIC_KEY=YOUR_PUBLIC_KEY MERCADO_PAGO_SAMPLE_ACCESS_TOKEN=YOUR_ACCESS_TOKEN npm start
```

2. Lembre-se de trocar os valores `YOUR_PUBLIC_KEY` e `YOUR_ACCESS_TOKEN` pelas [credenciais](https://www.mercadopago.com/developers/panel) da sua conta.

3. Acesse [http://localhost:8080](http://localhost:8080) em seu navegador.

### :test_tube: Testes

Em nossas [instruções de teste](https://www.mercadopago.com/developers/pt/docs/checkout-bricks/integration/integration-test) você irá encontrar **[cartões de crédito](https://www.mercadopago.com/developers/pt/docs/checkout-bricks/additional-content/test-cards)** que podem ser usados para simular o pagamento neste exemplo e um guia sobre como criar **usuários de teste**.

## :handshake: Contribuindo

Você pode contribuir com este projeto reportando problemas e bugs. Antes de abrir uma issue, leia nosso [código de conduta](CODE_OF_CONDUCT.md).

## :bookmark: Licença

MIT License. Copyright (c) 2022 - Mercado Pago <br/>
Para mais informações, consulte o arquivo [LICENSE](LICENSE).
