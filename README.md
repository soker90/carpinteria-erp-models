# Arroyo Erp Models

[![npm version](https://badge.fury.io/js/arroyo-erp-models.svg)](https://badge.fury.io/js/arroyo-erp-models)
![](https://github.com/soker90/arroyo-erp-models/workflows/Node.js%20CI/badge.svg)

This is a module of models for Arroyo ERP.

## Installation

```bash
  npm install arroyo-erp-models --save
```

## Available models

```javascript
  import models from 'arroyo-erp-models';

  models.mongoose // Expose a mongoose instance to connect
  models.connect() // Expose a method to connect to mongoose and response with the connection

  models.AutoIncrement // Expose a AutoIncrement model with its statics & methods
  models.AccountModel // Expose a Account model with its statics & methods
  models.ProductService // Expose a Product model with its statics & methods
  models.ProviderService // Expose a Provider model with its statics & methods
  models.DeliveryOrderModel // Expose a Delivery Order model with its statics & methods
  models.PriceModel // Expose a Price model with its statics & methods
  models.InvoiceModel // Expose a Invoice model with its statics & methods
  models.ClientModel // Expose a Client model with its statics & methods
```

