---
title: Getting started
description: Get started with the sphynx SDK with a step-by-step guide
category: Getting started
position: 0
---

This documentation will walk you through how to:

- Set up a sphynx account.
- Install sphynx SDK into your project.
- Create a sphynx instance to use through your project.

---

## Account setup

Before installing sphynx SDK, you will first need to create a sphynx Account to get your API credentials.

1. Sign up for a sphynx Account [here](#/signup).
2. Navigate to the developer section under settings [here](#/settings/developer).
3. Obtain your generated [public](/docs/sdk/concepts#public-keys) and [secret keys](/docs/sdk/concepts#secret-keys).

---

## Installation

### Prerequisites

The only requirement for using sphynx SDK is to have Node.js (version 16 or higher) installed on your machine.

### Install the SDK with a package manager

If you're using npm or yarn, then adding the sphynx SDK to your project is really simple. Once you've created a
directory for your project, navigate into your project's root folder in your terminal `cd your-project-folder`, and type
the following:

```bash
npm install @jam-commerce/sphynx
# or
yarn add @jam-commerce/sphynx
```

<div class="highlight highlight--note">
    <span>Note</span>
    <p>Note that examples provided using the sphynx SDK are using the latest version - available on <a href="https://www.npmjs.com/package/@jam-commerce/sphynx">npm</a>.</p>
</div>

### Instantiate sphynx with your API key

We're almost ready to go! We need to create a new sphynx instance and give it our [public
key](/docs/sdk/concepts#scope) (you can get your API keys from [sphynx Dashboard > Settings >
Developer](#/settings/developer)).

<div class="highlight highlight--info">
    <span>Tip</span>
    <p>For more information on API keys authentication, read more on <a href="/docs/sdk/concepts#authentication">how we authenticate sphynx core endpoints</a>.</p>
</div>

```js
// Import the sphynx module
import sphynx from '@jam-commerce/sphynx';

// Create a sphynx instance
const sphynx = new sphynx('{public_api_key}');
```

<div class="highlight highlight--note">
    <span>Note</span>
    <p>We've built in a console debugger into the sphynx SDK to help with debugging during development. To enable the debugger you can include the second argument <code>true</code> when you create your sphynx instance like so: <code>const sphynx = new sphynx('{public_api_key}', true);</code>. Note that a test API key has to be provided as the first argument for the console to show messages - it won't work with a live key.</p>
</div>

Awesome, you have set up your sphynx Account, installed the sphynx SDK and created your first sphynx instance! You
now have access to the `sphynx` object in your application to build out a truly unique frontend presentation layer!

---

### Next steps

Browse through the rest of our documentation to explore all the features of sphynx SDK - [listing
products](/docs/sdk/products#list-products), [add products to cart](/docs/sdk/cart#add-to-cart), or [capture an
order](/docs/sdk/checkout#capture-order). Note that all requests made using the sphynx SDK will have responses that
are returned asynchronously in a promise. Alternatively, if you want to dive more into reading a high-level overview of
sphynx SDK and its features, read more [here](/product/features).

<div class="highlight highlight--warn">
    <span>Important</span>
    <p>Please note that for all the following SDK documentation on  <b>Products</b>, <b>Cart</b>, and <b>Checkout</b>, we import <code>sphynx</code> in every example using sphynx SDK for the sake of brevity. In practice, you would follow the example of creating and exporting out your sphynx client in a file such as <code>/lib/sphynx SDK</code>.</p>
</div>

---
