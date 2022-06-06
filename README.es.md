# Procesamiento de pagos con tarjeta a través de Checkout Bricks

[English](README.md) / [Português](README.pt.md)

## :computer: Tecnologías

- Node.js
- [NPM](https://www.npmjs.com) (dependency manager)
- Express

## 💡 Requisitos

- Node.js 10 o superior (descarga [aquí](https://nodejs.org/)).
- [Lee nuestras instrucciones](https://www.mercadopago.com/developers/es/docs/getting-started) sobre cómo crear una aplicación en el Panel de Desarrolladores de Mercado Pago para obtener la public key y el access token. Estas llaves te darán acceso a las API de Mercado Pago.

## :gear: Instalación

1. Clona el proyecto.

```bash
git clone https://github.com/mercadopago/card-payment-bricks-sample-node.git
```

2. Accede a la carpeta.

```bash
cd card-payment-bricks-sample-node
```

3. Instala las dependencias necesarias.

```bash
npm install
```

## 🌟 Como ejecutar

1. Accede a la carpeta del proyecto.

```bash
cd card-payment-bricks-sample-node
```

2. Ejecuta el siguiente comando para iniciar la aplicación:

```bash
MERCADO_PAGO_SAMPLE_PUBLIC_KEY=YOUR_PUBLIC_KEY MERCADO_PAGO_SAMPLE_ACCESS_TOKEN=YOUR_ACCESS_TOKEN npm start
```

3. Recuerda cambiar los valores de `YOUR_PUBLIC_KEY` y `YOUR_ACCESS_TOKEN` por las [credenciales](https://www.mercadopago.com/developers/panel) de su cuenta.

4. Accede a [http://localhost:8080](http://localhost:8080) en tu navegador.

### :test_tube: Pruebas
En nuestras [instrucciones de prueba](https://www.mercadopago.com/developers/es/docs/checkout-bricks/integration/integration-test) encontrarás **[tarjetas de crédito](https://www.mercadopago.com/developers/es/docs/checkout-bricks/additional-content/test-cards)** que se pueden utilizar para simular el pago de este ejemplo, junto con una guía sobre cómo crear **usuarios de prueba**.

## :handshake: Contribuyendo

Puedes contribuir a este proyecto informando problemas y bugs. Antes de abrir una contribución, lee nuestro [código de conducta](CODE_OF_CONDUCT.md).

## :bookmark: Licencia

MIT License. Copyright (c) 2022 - Mercado Pago <br/>
Para obtener más información, consulte el archivo [LICENSE](LICENSE).
