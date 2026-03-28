# Checkout Ignore Client Exists (WooCommerce)
# Author: Gerson Farias Briglia <briglia@gmail.com>

Prevents errors when a customer uses an already registered email during WooCommerce checkout and automatically links the order to the existing user.

## 🚀 Features

* Prevents errors when using an existing email
* Avoids duplicate account creation
* Automatically associates the order with the existing user
* Compatible with Fluid Checkout

## 📦 Installation

1. Download the plugin or clone this repository
2. Zip the `checkout-ignore-client-exists` folder
3. In WordPress, go to **Plugins > Add New > Upload Plugin**
4. Upload the `.zip` file and activate it

## 🧪 How it works

* If the email entered at checkout already exists:

  * WooCommerce does not attempt to create a new account
  * The order is automatically linked to the existing user

## ⚠️ Notes

* The plugin allows checkout without login even if the email is already registered
* This may have security implications depending on your use case

## 🔐 Recommendations

For better security, consider:

* Requiring login when an existing email is detected
* Implementing magic link or OTP authentication

## 📁 Structure

```
checkout-ignore-client-exists/
└── checkout-ignore-client-exists.php
```

## 📄 License

MIT
