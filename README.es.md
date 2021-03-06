# Procesamiento de pagos con tarjeta a trav茅s de Checkout Bricks

[English](README.md) / [Portugu锚s](README.pt.md)

## :computer: Tecnolog铆as

- Node.js
- [NPM](https://www.npmjs.com) (dependency manager)
- Express

## 馃挕 Requisitos

- Node.js 10 o superior (descarga [aqu铆](https://nodejs.org/)).
- [Lee nuestras instrucciones](https://www.mercadopago.com/developers/es/docs/getting-started) sobre c贸mo crear una aplicaci贸n en el Panel de Desarrolladores de Mercado Pago para obtener la public key y el access token. Estas llaves te dar谩n acceso a las API de Mercado Pago.

## :gear: Instalaci贸n

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

## 馃専 Como ejecutar

1. Accede a la carpeta del proyecto.

```bash
cd card-payment-bricks-sample-node
```

2. Ejecuta el siguiente comando para iniciar la aplicaci贸n:

```bash
MERCADO_PAGO_SAMPLE_PUBLIC_KEY=YOUR_PUBLIC_KEY MERCADO_PAGO_SAMPLE_ACCESS_TOKEN=YOUR_ACCESS_TOKEN npm start
```

3. Recuerda cambiar los valores de `YOUR_PUBLIC_KEY` y `YOUR_ACCESS_TOKEN` por las [credenciales](https://www.mercadopago.com/developers/panel) de su cuenta.

4. Accede a [http://localhost:8080](http://localhost:8080) en tu navegador.

### :test_tube: Pruebas
En nuestras [instrucciones de prueba](https://www.mercadopago.com/developers/es/docs/checkout-bricks/integration/integration-test) encontrar谩s **[tarjetas de cr茅dito](https://www.mercadopago.com/developers/es/docs/checkout-bricks/additional-content/test-cards)** que se pueden utilizar para simular el pago de este ejemplo, junto con una gu铆a sobre c贸mo crear **usuarios de prueba**.

## :handshake: Contribuyendo

Puedes contribuir a este proyecto informando problemas y bugs. Antes de abrir una contribuci贸n, lee nuestro [c贸digo de conducta](CODE_OF_CONDUCT.md).

## :bookmark: Licencia

MIT License. Copyright (c) 2022 - Mercado Pago <br/>
Para obtener m谩s informaci贸n, consulte el archivo [LICENSE](LICENSE).
