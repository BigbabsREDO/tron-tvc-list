# Adding new token
The JSON schema for the tokens includes: address, name, decimals, symbol, logoURI, official homepage, MarketCap link, existing Markets.

Follow the steps below to add a new token：
1) Fork this repo.
2) change the JSON file `tokenlist.json`, adding such as: (PLEASE DO NOT REMOVE EXISITING TOKENS)
```
{
      "address": "TEMZsMYSC8VJJGddpjYeXS4UN29dWa5Zij",
      "symbol": "DZfun",
      "name": "Decentralized Zone",
      "decimals": 18,
      "logoURI": "https://www.canva.com/design/DAGPG5Su6lU/OfO6vnhvuJ90ABAAjUFwOg/edit?utm_content=DAGPG5Su6lU&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton",
      "homepage": "https://decentralizedzone.my.canva.site/",
      "MarketCapLink": "https://sunpump.meme/token/TEMZsMYSC8VJJGddpjYeXS4UN29dWa5Zij",
      "existingMarkets": [
          {
              "source": "Sunpump",
              "pairs": [
                  "DZfun/USDT",
                  "WIN/TRX"
              ]
          },
          {
              "source": "Poloniex",
              "pairs": [
                  "WIN/USDT"
              ]
          },
          {
              "source": "KuCoin",
              "pairs": [
                  "WIN/USDT"
              ]
          }
    ]
}
```
* `address`[Required]: your token address.
* `symbol`[Required]: your token symbol.
* `name`[Required]: your token name.
* `logoURI`[Required]: the logo URI of your token.
* `homepage`[Required]: the home page of your token.
* `MarketCapLink`[Optional]: the coinmarketcap or coingecko link for your token.
* `existingMarkets`[Required]: where to trade with your token.
3) Submit PR with the changed JSON file.


