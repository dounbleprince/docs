# Deposit

```json
{
	"event": "deposit",
	"sequence": 661,
	"amount": "3.556",
	"asset": "BTC",
	"timestamp": "1511482279491"
}
```

A `deposit` event indicates that a new deposit has been detected on your account. It will only be sent once per deposit.

The deposit may still be unconfirmed. Use the `balance` event to get notified when the deposit is credited to your balance.