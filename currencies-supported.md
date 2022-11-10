# Currencies Supported

When creating and paying digital currency invoices, there is a difference to be made between **invoice currencies** and **payment currencies.**

The **invoice currency** is the one you choose to issue the invoice in during creation, mainly based on what is required to be compliant following your local tax & accounting laws.&#x20;

As an example: In the United States of America it is required to denominate any invoice that you have issued and/or paid in the United States Dollar (USD) for bookkeeping/accounting purposes. Payments can be made in a different currency.

{% hint style="info" %}
Stuck getting paid in cryptocurrency because you're uncertain on what your accountant will say?

Feel free to let your accountant reach out to us directly through [email](mailto:support@request.finance), or let him/her [schedule a call with us](https://calendly.com/request-invoicing) so that we can answer all questions.&#x20;
{% endhint %}

The **payment currency** is the one that you end up receiving when issuing an invoice, or spend when you're on the recipient side of an invoice. These can be traditional currencies like EUR, USD or GBP which you receive on your bank account, or digital currencies (cryptos) like ETH or DAI that you receive on your digital wallet.

{% hint style="info" %}
Need help deciding which currency is best for you to accept for your business? Our team is happy to assist you and explain the pros and cons of all of them.
{% endhint %}

## On-chain conversion with Chainlink

If you denominate your invoice in traditional fiat currency (like USD or GBP) and want to get paid in crypto, Request deals with the conversion automatically.

We partnered with Chainlink in order to offer on-chain conversion. For every currency aggregated by Chainlink (for a complete list [on Ethereum check here](https://docs.chain.link/docs/ethereum-addresses/), and [on Polygon here](https://docs.chain.link/docs/matic-addresses/)) we offer the possibility to denominate the invoice in one currency (e.g. EUR or SGD) and to accept payments in another one (e.g. GRT or USDT).

{% hint style="info" %}
In order to accept cryptos that are not valued by Chainlink oracles, you have to denominate your invoice in the same currency as the payment.&#x20;
{% endhint %}

#### How do crypto-payments for fiat invoices work?

Right before the invoice recipient hits "Pay", we estimate the amount of cryptos required, based on up-to-date rates and the invoice amount. We add to that estimation a margin to ensure the transaction succeeds even in case of slight market changes.

Once the payment gets initiated, the latest rate is fetched from Chainlink contracts and the corresponding amount is withdrawn from the payer's wallet and credited to the invoice issuer's wallet. Both parties can be sure the invoice is paid with the correct rate.

{% hint style="info" %}
We use margins to optimize the chance of transaction success while decreasing the risk of market volatility. For stable coins, this margin is 0.5% and for other coins 3%.

If your transaction fails with `Fail with error 'Amount to pay is over the user limit'` error, it means that the price of your payment currency quickly dropped and you need to pay again.
{% endhint %}

## The supported invoice & payment currencies of Request Invoicing

{% tabs %}
{% tab title="Invoice currencies supported" %}
## Traditional currencies supported

* United States Dollar (USD)
* Euro (EUR)
* British Pound (GBP)
* Swiss Franc (CHF)
* Singapore Dollar (SGD)
* Australian Dollar (AUD)
* Canadian Dollar(CAD)
* Israeli Shekel(ILS)

## Digital currencies supported

* AAVE
* Aave Dai (aDAI)
* Aave USDC (aUSDC)
* Akropolis (AKRO)
* Ankr (ANKR)
* Aragon (ANT)
* Bitcoin (BTC)&#x20;
* Celo Dollar (cUSD)
* Celo (cGLD / CELO)
* Celo Euro (cEUR)
* Dai (DAI)
* Ether (ETH)
* Euro e-money token by Monerium EMI (EURe)
* Fantom (FTM)
* The Graph (GRT)
* Gnosis (GNO)
* Indacoin (INDA)
* Maker (MKR)
* MATIC
* 88mph (MPH)
* Near (NEAR)
* Ocean (OCEAN)
* Raiden Network Token (RDN)
* Request (REQ)
* The Sandbox (SAND)
* Tether (USDT)
* USD Coin (USDC)&#x20;
* XSGD (XSGD)
* Zilliqa (ZIL)
{% endtab %}

{% tab title="Payment currencies supported" %}
## Traditional currencies supported

Ask the buyer to pay in these currencies and he will notify you when he pays.&#x20;

* Bank Transfers
* Stripe

## Digital currencies with fully support

By selecting one of these payment currencies, your invoice gets completely smart and Request Invoicing automatically detects when the payment is made.

* Dai (DAI on Ethereum or Polygon Matic)
* USD Coin (USDC on Ethereum or Polygon Matic)
* Tether (USDT on Ethereum or Polygon Matic)
* Ether (ETH)
* Maker (MKR)
* Request (REQ)
* Euro e-money token by Monerium EMI (EURe)
* Indacoin (INDA)
* Raiden Network Token (RDN)
* Gnosis (GNO)
* Olyseum (OLY)
* AAVE
* Aave DAI (aDAI)
* Aave USDC (aUSDC)
* MATIC (on Matic)
* OCEAN (on Polygon Matic and Ethereum)
* Celo DolarcUSD
* cGLD / CELO (on Celo)
* Celo Euro (cEUR on Celo)
* Celo Dollar (cUSD, on Celo)
* FTM (on Fantom)
* FUSE (on Fuse)

## Digital currencies on declarative chains

Ask the buyer to pay in these currencies and he will notify you when he pays.&#x20;

* Bitcoin (BTC)
* Zilliqa (ZIL)
* Near (NEAR) - Detection in progress, stay tuned
{% endtab %}
{% endtabs %}

{% hint style="info" %}
Among payment currencies, some are compatible with fiat denomination, and some are not.

Have a look [at this page for currencies supported by Chainlink on Ethereum](https://docs.chain.link/docs/ethereum-addresses/), and [for Polygon check here](https://docs.chain.link/docs/matic-addresses/).
{% endhint %}
