---
description: >-
  This page answers all frequently asked questions by our users. Not finding
  your question below? Feel free to contact us through chat, social media or by
  scheduling a video call.
---

# FAQ

## **Issuing invoices**How to create an invoice using Request Finance?

Follow the [creating an invoice](getting-started-guide.md#creating-a-digital-currency-invoice-in-a-few-simple-steps) section of our Getting Started Guide, where we dive into the process step-by-step.

### **What information should I include on my invoice?**

When issuing an invoice, you need to be aware of all local and national requirements for your invoice to be compliant. This varies, but a general rule of thumb is to include your name, business name, legal address and tax number.\
\
**For more specific guidance see the following resources:**

[**European Union**](https://ec.europa.eu/taxation\_customs/business/vat/eu-vat-rules-topic/vat-invoicing-rules\_en)\
\*\*\*\*[United State of America](https://www.ionos.com/startupguide/grow-your-business/requirements-for-a-proper-invoice/)

### **How do I receive digital currencies (cryptocurrencies) for my business?**

In order to receive cryptocurrency, you need a wallet address. These wallet addresses are unique addresses (consisting of letters and numbers) that allow you to manage your funds.\
\
You control your wallet through an application, just like the online banking app you use now.\
\
To accept ETH, DAI, USDT and other \*\*\*\* Ethereum-based \*\*\*\* ERC20 tokens, you will need an Ethereum address. For beginners you can receive all these currencies on a [Coinbase account.](https://www.coinbase.com/signup)\\

Once more familiar with handling cryptocurrencies, we recommend moving your funds off exchanges and keep them on a wallet that you own the private keys to. \*\*\*\* [Here](https://ethereum.org/en/wallets/find-wallet/) is a helpful guide on how to do this.

To get paid on Polygon, Fantom, Fuse, Celo or other blockchains, you need to know how they work. [Metamask ](https://metamask.io)supports all EVM blockchains and lets you access all Request Finance features.

### How to enable my customers to pay with cryptocurrencies using Request Finance?

By creating an invoice with Request Finance your customers will receive an automatic email with a link to the invoice. All they have to do is click on accept and pay from within the invoice.

### **Can I get paid by credit card?**

Yes, you need to [setup a Stripe account](https://dashboard.stripe.com/register) first. You can setup your Stripe account right from the [Invoice creation page](https://app.request.finance/create), by picking a fiat currency as the invoice currency and then "in EUR, the payer pays in EUR" for example.

### **Can my clients pay in fiat (USD, EUR etc.) by bank transfer?**

Yes, you can denominate an invoice in fiat and then pick **How do you want to receive the funds? In fiat, the payer pays in fiat**. Your client can later notify you about the payment, and you have to do the reconciliation manually.

For EUR businesses: we partnered with Monerium to offer a smooth fiat-to-crypto payment experience. You client pays with a usual bank transfer in Euro, and you receive DeFi-ready EURe tokens. [More information here.](https://www.request.finance/fiat-to-crypto-payments)

### **Can I get paid in BTC?**

Yes, but Request Finance does not detect BTC payments. The payer will notify you when he makes the payment.

To accept BTC, you will need a Bitcoin wallet address. We recommend using [Coinbase](https://www.coinbase.com/signup).

### **What currencies can I issue an invoice in?**

All currencies which are currently supported by Request Finance [can be found here.](currencies-supported.md#the-supported-invoice-and-payment-currencies-of-request-invoicing)

### Why would I accept cryptocurrencies payments?

We're seeing an increase in clients that prefer to pay in cryptocurrency over traditional currencies. This is because the high-speed payments get processed on cryptocurrency payment networks, as well as the relatively small fees associated with larger value transfers.

Especially when dealing with international transactions, accepting cryptocurrencies can have a big positive effect on your companies' bottom line.

### What are the bookkeeping implications of getting paid in cryptocurrencies?

The same bookkeeping implications apply to regular invoices charged in traditional currencies like USD or EUR. Capital gains (if any) must be added as revenues. and receive in fiat.

For an invoice denominated in fiat currency for which you receive cryptocurrency payments, the accountant acts similar as with an international payment - taking into account exchange rate gains and losses.

In addition, there may be some capital gains or losses associated with receiving digital assets. This is mitigated by using stable tokens such as DAI or USDT for your business

### I have an accountant who does my company bookkeeping, how do I manage?

For invoices denominated in a fiat currency which payment is received in the same currency at the end of the process, the bookkeeping of the transaction is the same as usual.

The accountant does not need to be informed about using blockchain technology, as the amount received in the bank account matches the amount of the invoice.

Invoices paid in cryptocurrencies are different. Go to your [Request Finance](https://app.request.finance) dashboard, export your invoices as a CSV or download them individually as PDFs and send them to your accountant. Your accountant will then have all of the information needed to finalize your accounting.

Your accountant will manage these invoices in a similar way as a payment in a foreign currency, including exchange rate gains and losses, and additionally might also have to book capital gains.

{% hint style="info" %}
Is your accountant unsure about how to proceed? [Get in touch](https://calendly.com/christophel-1) and we will connect with him/her directly to help them out!
{% endhint %}

### How do I upload my logo on the invoice?

Customizing your invoice by adding your company logo is a feature we're currently working on and is currently unavailable.

### How do I set up recurring invoices?

Before you send the first occurrence of a recurring invoice, click on "I want this to be a recurring invoice", at the bottom. The app guides to configuring the recurrence settings.

![](.gitbook/assets/image.png)

## **Making payments**

### **How do I pay an invoice in cryptocurrency?**

In order to pay an invoice, you need to use a wallet that has Web3 capability with enough funds to cover the payment amount requested. You also need to have enough funds to pay for the gas (ex: some ETH on Ethereum).

Web3 is the new generation of technology that empowers the individual over the institution through decentralization. \*\*\*\* When managing your finances, you can think of your Web3 wallet as your online banking app -- but without the bank.\
\
Not sure which wallet to use? [Here](https://ethereum.org/en/wallets/find-wallet/) is a helpful guide.

### How do I cancel a pending payment?

You tried to make a payment but the gas price was too low and the transaction is still waiting in the mempool? There are 2 solutions.

In Metamask, you can either "Speed up" (by increasing fees) or "Cancel" a transaction. They detail the cancellation procedure in [this blog post](https://metamask.zendesk.com/hc/en-us/articles/360015489251-How-to-speed-up-or-cancel-a-pending-transaction).

For other wallets that do not offer cancellation, ask in the wallet's community or get in touch with us.

### How do I pay with a Ledger?

Select the Ledger option in the wallet selection window. If the option is not available, it means Ledger is not yet available for this network.

You have to update your Ledger's firmware to the latest version. Here is how to do it:

1. The latest version of Ledger Live
2. The latest firmware version on the Ledger
3. Update Ethereum app
4. Allow Contract data

### How do I pay with a Gnosis Safe?

In your Safe, go to Apps and select Request Finance. Sign in, open the invoice you want to pay, click on "Pay", and when prompted for a wallet selection, pick "Gnosis Safe". If your Safe is configured for multiple signatures, don't forget to tell the other owners to sign as well.

### How to batch multiple payments into one transaction?

When paying from a Gnosis Safe, you can batch payments for invoices that you have already accepted. [Have a look at this demo.](https://youtu.be/-jJvIsgxQmk)

Paying in batch without Gnosis Safe will be available soon, [don't miss future updates](https://twitter.com/RequestFinance).

### What is a digital currency or cryptocurrency?

Digital currency, or cryptocurrency, is often referred to as programmable money. Like the Internet in the 90s was for communication to become digital. Cryptocurrencies and their applications represent the internet of money. There are currently over 7000 cryptocurrencies listed on the popular tracker CoinMarketCap.

### How do I pay an invoice partially?

Partially paying a digital currency invoice is currently unavailable and will be released as a feature in a near update.

### How do I accept an invoice?

Upon receipt of the invoice, you can accept the invoice to let the issuer know if you agree with the terms & conditions.

This is done by logging into your account & clicking on the accept button above the invoice.

### How do I reject an invoice?

Upon receipt of the invoice, you can reject the invoice to let the issuer know if you disagree with the terms & conditions.

This is done by logging into your account & clicking on the reject button above the invoice.

## General questions about Request Finance

### **How do I create an account?**

We've written an in-depth [Getting Started Guide for you here](getting-started-guide.md#creating-your-request-account), including video tutorials for each step in the process.

### Who is using Request Finance?

Request Finance is built for all individuals and businesses who are looking to pay & get paid in cryptocurrencies. Some of our biggest clients involve organizations like MakerDAO, who are willing to pay their suppliers and grantees in cryptocurrency.

### How much does it cost to use Request Finance?

Issuing invoices will always be free.\
\
At the time of payment, the payer will pay the Ethereum gas fees (used to send the funds) and the Request Finance service fee.

The Ethereum gas fee is variable depending on how busy the network is at the time of payment. It is not collected by Request.

The Request Finance service fee is 0.1% of the total amount requested in the invoice, with a maximum fee of $2 per invoice.

> Example: An invoice issued through Request Finance of $3,000 will be charged 0.1% of the invoice amount, which if there was no maximum cap is $3.00. Because of the maximum cap, the service fee that is charged is $2.00.

### How to get a bank statement?

.csv and .pdf exports are available to export through the [Request Finance dashboard](https://app.request.finance).

### How do payment terms work? Do we automatically apply late fees?

Payment terms on an invoice allow the client to know when he should pay. This should be agreed and included in the commercial contract.

A reputation feature is coming soon. Paying on time will be valuable to increase the client’s reputation

We envision to apply automated late fees for late payers. This feature has yet to be prioritized based on user feedback. Let us know if this is something that's useful for you [by sending an email here](mailto:support@request.network).

### How do I use the escrow option?

The escrow feature is coming soon. We are building a decentralized escrow feature, replacing the third party by a smart contract to remove the need for trust between businesses.

Payments can be programmed to be made at a certain time or based on milestones that the client will validate.

### How much does the escrow feature cost?

Coming soon.

### How do I use the swap feature?

When you receive an invoice you may have the option to pay it using another currency than the one the invoice issuer expects.

If you choose to do so an on-chain exchange will be called at payment time, and the invoice issuer will receive the currency he expected.

For now this feature is only supported on Ethereum and Polygon between the currencies DAI and USDC.

### How much does the swap feature cost?

When using the swap feature, additional fees will be applied to the payer:

* Exchange fees (0.3% of the total amount)
* Request swap fees (0.5% of the total amount)

### What is the Reputation Score?

As a Business, you get a Reputation Score based on your behavior.

If you pay your invoices on time, you will always get 5 stars.

Please don't be late :)

## Payments

### Why do we ask for slightly more than your payment total?

There are two reasons for this, which are as follows:

1. When you are paying for an invoice denominated in fiat prices are calculated on-chain via ChainLink, we ask for a little extra during each payment to account for any exchange rate discrepancies by the time your transaction gets confirmed. e.g. imagine paying a EUR denominated with DAI and the transaction takes a few minutes to confirm, when we check with ChainLink the EUR/DAI price may have dropped slightly. Because of this, we require a small % extra to cover the full amount. After the transaction has been completed, any excess is sent back directly to the payer
2. When you are paying via our swap mechanism the swaps can occur slippage from the exchange (e.g. DAI/USDT swap may cause 0.1% slippage + also fees) so again, we ask for extra.
