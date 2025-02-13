- Navigate to the [sskhoo/tron-tvl-list](https://github.com/sskhoo/tron-tvl-list) repository page on GitHub.
- Click the "Fork" button to create a copy of the repository under your GitHub account.
- Clone the forked repository by running the following command in your terminal:
  ```
  git clone https://github.com/YOUR_USERNAME/tron-tvl-list.git
  ```
- Navigate to the cloned repository:
  ```
  cd tron-tvl-list
  ```
- Open the `defiProjectList.json` file in a text editor.
- Add the new Defi project details for "Sunmax" without removing existing content:
  ```json
  [
      {
          "name": "Sunmax",
          "logoURI": "https://coin.top/production/upload/logo/sun10.png",
          "homepage": "http://sun.io/",
          "MarketCapLink": "https://coinmarketcap.com/currencies/sun-token",
          "url": "https://apilist.tronscan.org/api/tvl",
          "category": "DEX",
          "poolAddresses": [
              "TKcEU8ekq2ZoFzLSGFYCUY6aocJBX9X31b",
              "TAkrcKsS5FW9f3ZfzvWy6Zvsz9uEjUxPoV"
          ]
      }
  ]
  ```
- Stage the updated file:
  ```
  git add defiProjectList.json
  ```
- Commit the changes with a message:
  ```
  git commit -m "Update defiProjectList.json" -m "Add new Defi project details for Sunmax."
  ```
- Push the committed changes to your forked repository on GitHub:
  ```
  git push origin main
  ```
- Navigate to the original [sskhoo/tron-tvl-list](https://github.com/sskhoo/tron-tvl-list) repository page on GitHub.
- Click the "Compare & pull request" button.
- Provide a title and description for your pull request, following the provided PR template:
  ```
  ## **Please provide the following information for your Defi project.**
  Please include change to the `defiProjectList.json` file in the PR.
  DON'T modify any other project's contents.

  ##### Twitter Link:
  https://twitter.com/defi_sunio

  ##### List of audit links if any:
  https://sun.io/docs/slowmist_audit_report_cn_sun.pdf

  ##### Homepage:
  http://sun.io/

  ##### Logo (High resolution, preferably in .svg and .png, for application on both white and black backgrounds. Will be shown with rounded borders):
  https://coin.top/production/upload/logo/sun10.png

  #### URL to get TVL:
  https://apilist.tronscan.org/api/tvl

  ##### Current TVL:
  $3298643126.37

  ##### CoinMarketCap ID (so your TVL can appear on Coinmarketcap or Coingecko: (https://coinmarketcap.com/currencies/#TOKEN or https://www.coingecko.com/en/coins/#TOKEN)
  https://coinmarketcap.com/currencies/sun-token

  ##### Short Description:
  SUN is first integrated platform for stablecoin swap, stake-mining and self-governance on TRON.

  ##### Token address and ticker if any:
  TSSMHYeV2uE9qYH95DqyoCuNCzEL1NvU3S

  ##### Pool addresses:
  TKcEU8ekq2ZoFzLSGFYCUY6aocJBX9X31b, TAkrcKsS5FW9f3ZfzvWy6Zvsz9uEjUxPoV.

  ##### Category (Yield/DEX/Lending/Minting/Assets/Insurance/Options/Indexes/Staking) *Please choose only one:
  DEX

  ##### Oracle used (WINkLink/Chainlink/Band/API3/TWAP or any other that you are using):
  WINkLink

  ##### forkedFrom (Does your project originate from another project):

  ##### methodology (what is being counted as tvl, how is tvl being calculated):
  All tokens staked in the pool MINUS borrowed assets are counted as TVL. Borrowed assets are not included in the TVL.
  ```
- Monitor the pull request for any feedback or requested changes from the repository maintainers.
- Address any feedback or requested changes by making additional commits to your forked repository and updating the pull request accordingly.
