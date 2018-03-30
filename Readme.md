# CoinPayment.Net

This is a very simple library for consuming [Coinpayments](https://coinpayments.net).

## How to use

```c#
CoinApi api = new CoinApi(PublicApiKey,PrivateApiKey);
```

### Generate a receive payment request

```c#
api.ReceiveAsync(ReceiveTransaction transaction);
```

### Generate a withdrawal request

```c#
api.TransferAsync(SendTransaction transaction);
```

###Get it on nuget

`https://www.nuget.org/packages/jetcipher.CoinPayment.Net/`
