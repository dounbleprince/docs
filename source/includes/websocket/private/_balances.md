# Balance

```json
{
	"event": "balance",
	"sequence": 42,
	"updates": [
		{
			"asset": "ETH",
			"available": "377.9934",
			"total": "9939.122"
		},
		{
			"asset": "BTC",
			"available": "18.1221",
			"total": "55.991"
		}
	]
}
```

A `balance` event is a balance update notification sent whenever one or more of your balances changes.

The `total` balance value will appear only if it has changed.