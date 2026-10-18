<a href="https://bellchain.app/en/">
  <img src="https://github.com/bellchain-app/.github/raw/main/profile/banner.png" alt="Bellchain: Alerts only when it all lines up. Crypto alerts you build yourself, no code." width="100%">
</a>

<p align="center">
  <a href="https://bellchain.app/en/"><b>Website</b></a>
  &nbsp;·&nbsp;
  <a href="https://app.bellchain.app/"><b>Open the app</b></a>
  &nbsp;·&nbsp;
  <a href="https://docs.bellchain.app/en/"><b>Docs</b></a>
  &nbsp;·&nbsp;
  <a href="https://t.me/bellchainapp"><b>Telegram channel</b></a>
</p>

**Bellchain** lets you build crypto alerts from nodes on a board, without code. Say you want to know when Bitcoin's RSI on the 1-hour chart drops below 30, but only while the price is above the EMA 200, and at most once every four hours. In Bellchain that's one chain: a candle, two indicators, two conditions, an AND and a Telegram node. Before it goes live, the replay shows how often it would have fired over the last 90 days of Binance prices.

### How it works

1. **Drag.** 25 nodes: candle source, indicators such as RSI, EMA, MACD and Bollinger Bands, conditions, logic and actions. Or start from a template.
2. **Connect and test.** Wire outputs to inputs. The replay runs the chain over the last 90 days of real Binance prices and lists every alert it would have sent.
3. **Activate.** Alerts arrive via Telegram, push or email. After an alert, each action waits 4 hours by default before the next one.

### Built in the open

- **Same rules for every node.** Our own nodes follow the same node specification that community nodes will use.
- **Checked math.** The indicators calculate like TradingView's Pine functions (`ta.rsi`, `ta.ema`, `ta.macd` and so on) and are tested against an independent recalculation on 500 real BTC/USDT hourly candles.
- **Chains are JSON.** Export a chain and share it. Importing it creates a copy of your own.
- **Coming soon:** the node specification, the official nodes and the templates as MIT-licensed repositories right here, with discussions for node requests and templates.

### Good to know

- Bellchain is **free during the beta**. Every new account gets 14 days of every feature, no credit card, no API keys.
- Prices come from Binance, for every spot pair including euro pairs like BTC/EUR. More exchanges are planned.
- Bellchain sends alerts. It doesn't trade, hold funds or give investment advice.

### News and contact

News and changelog in the Telegram channel [t.me/bellchainapp](https://t.me/bellchainapp), alerts from [@BellchainBot](https://t.me/BellchainBot), questions to [hello@bellchain.app](mailto:hello@bellchain.app).

<details>
<summary><b>Auf Deutsch</b></summary>
<br>

Mit Bellchain baust du dir Krypto-Alarme aus Bausteinen, ohne Code: etwa „RSI unter 30, aber nur, solange der Kurs über dem EMA 200 liegt“. Bevor eine Chain live geht, zeigt dir das Replay, wie oft sie mit den echten Binance-Kursen der letzten 90 Tage ausgelöst hätte. Alarme kommen per Telegram, Push oder E-Mail. In der Beta ist alles kostenlos.

[Website](https://bellchain.app/de/) · [App öffnen](https://app.bellchain.app/) · [Doku](https://docs.bellchain.app/de/) · [Telegram-Kanal](https://t.me/bellchainapp)

</details>
