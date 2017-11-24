# Balances

## List Balances

> Response

```json
[ 
    {
        "asset": "ETH",
        "available": "9987.50070583",
        "total": "9996.72128261"
    },
    {
        "asset": "BTC",
        "available": "145.16729606",
        "total": "101.33222695"
    }
]
```

List your balances, grouped by asset.

### HTTP Request

**`GET /balances/:asset(s)`**

### Parameters

Name | Description
--------- | -------
asset(s) | Optional. One or more comma-separated assets.

Omitting `asset(s)` will return all balances on your account.

### Available balance

Your available balance is equal to your total balance minus the amount that's been placed on hold.

When you place an order, the amount used for the order is placed on hold until the order is filled or cancelled.

When you request a withdrawal, the amount of the withdrawal is placed on hold until the withdrawal is processed or cancelled.

### Response

An array of balances on your account.