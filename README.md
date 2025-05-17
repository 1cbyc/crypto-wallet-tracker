# Crypto Wallet Tracker

Allows users enter one or more wallet addresses from EVM to non-EVM chains then tracks and displays balances, recent transactions, and token holdings via a CLI interface and a web ui.

Looking at fixing these features first:
- Input Address
- Using Etherscan API
- Fetching EVM chain, token  and latest tx (w/ timestamps, value and gas used, and tx status)
- Clean display in terminal or web UI
- Auto refresh every 10 seconds (or maybe manual refresh)


Looking at fixing these features later:
- Multi chain support (Sol, and BTC)
- Portfolio aggregation + PnL tracking
- Historical graphing (price vs time with chart.js or Plotly)
- Address tagging (like exchange lables, defi wallets)
- Telegram/Discord bot notifications
- Live Web app