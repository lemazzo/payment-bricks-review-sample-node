# Payment Brick with Review Step

## :computer: Technologies

- Node.js
- [NPM](https://www.npmjs.com) (dependency manager)
- Express

## 💡 Requirements

- Node.js 10 or higher (you can download it [here](https://nodejs.org/)).
- [Read our instructions](https://www.mercadopago.com/developers/en/docs/getting-started) on how to create an application at the Mercado Pago Developer Panel in order to acquire your public key and access token. They will grant you access to Mercado Pago's public APIs.

## :gear: Installation

1. Clone the project.

```bash
git clone https://github.com/mercadopago/payment-bricks-review-sample-node
```

2. Go to the project's folder.

```bash
cd payment-bricks-review-sample-node
```

3. Then install the dependencies.

```bash
npm install
```

## 🌟 How to run it

1. Run the following command to start the application:

```bash
MERCADO_PAGO_SAMPLE_PUBLIC_KEY=YOUR_PUBLIC_KEY MERCADO_PAGO_SAMPLE_ACCESS_TOKEN=YOUR_ACCESS_TOKEN npm start
``` 

2. Remember to replace the values of `YOUR_PUBLIC_KEY` and `YOUR_ACCESS_TOKEN` with the corresponding [credentials](https://www.mercadopago.com/developers/panel/app) from your account.

3. Navigate to [http://localhost:8080](http://localhost:8080) in your browser.

### :test_tube: Testing

On our [testing instructions](https://www.mercadopago.com/developers/en/docs/checkout-bricks/integration-test/test-payment-flow) you'll find **[credit cards](https://www.mercadopago.com/developers/en/docs/checkout-bricks/additional-content/your-integrations/test/cards)** that can be used along with this sample and a guide on how to create **test users**.

## :handshake: Contributing

You can contribute to this project by reporting problems and bugs. Before opening an issue, make sure to read our [code of conduct](CODE_OF_CONDUCT.md).

## :bookmark: License

MIT License. Copyright (c) 2023 - Mercado Pago <br/>
For more information, see the [LICENSE](LICENSE) file.
