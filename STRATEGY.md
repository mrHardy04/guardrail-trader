# Simple strategy

Pair: BTCUSDT
Timeframe : 4 hour

Rules:
1. Pull live price and 24-hour change with Binance MCP.
2. If 24-hour change is down more than 2 percent, signal WAIT.
3. If 24-hour change is between -2 percent and +2 percent, signal NO TRADE.
4. If 24-hour change is up more than 2 percent, signal TINY LONG only.
5. Any TINY LONG must be prepared first and wait for yes.
6. Never withdraw.
7. Never use more than 2 USDT.

Prompt:
Run the Guardrail strategy on BTCUSDT. Show price, 24-hour change, signal, and reason. If the signal is TINY LONG, prepare the smallest Spot DOGEUSDT buy and wait for yes. Otherwise do not prepare an order.