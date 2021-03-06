<h1 id='ticker-websocket'>Ticker</h1>

### Snapshot

```json
{
	"type": "snapshot",
	"channel": "ticker",
	"product": "ETH-BTC",
	"data": {
		"price": "0.04771",
		"bid": "0.04770",
		"ask": "0.04773",
		"bid_size": "33.881",
		"ask_size": "12.913",
		"timestamp": "1511482279491.883"
	}
}
```

When you first subscribe to the `ticker` channel, you'll receive a snapshot of the ticker.

### Event

```json
{
	"event": "ticker",
	"sequence": 211,
	"product": "ETH-BTC",
	"price": "0.04771",
	"bid": "0.04770",
	"ask": "0.04773",
	"bid_size": "33.881",
	"ask_size": "12.913",
	"timestamp": "1511482279491.883"
}
```

The `ticker` event provides real-time price updates and is sent every time a match occurs.