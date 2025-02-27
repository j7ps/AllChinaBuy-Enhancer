# AllChinaBuy Price Converter 💸

A lightweight Tampermonkey userscript that converts Chinese Yuan (CNY) prices to US Dollars (USD) on [allchinabuy.com](https://www.allchinabuy.com/). This script fetches the latest exchange rate and dynamically updates prices across the site, making shopping easier for international users. 🌍

## Features ✨
- Automatically converts CNY prices to USD. 💰
- Updates prices in real-time as you browse. ⏱️
- Works on product pages, totals, and more. 🛒

## Installation 🚀

Follow these steps to install the script using Tampermonkey:

### Step 1: Install Tampermonkey 🛠️
If you don’t already have Tampermonkey, install it for your browser:
- [Tampermonkey for Chrome](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo) 🌐
- [Tampermonkey for Firefox](https://addons.mozilla.org/en-US/firefox/addon/tampermonkey/) 🦊
- [Tampermonkey for Edge](https://microsoftedge.microsoft.com/addons/detail/tampermonkey/iikmleipfamncoeapigifbpdjkcldcnb) 🖥️
- [Tampermonkey for Safari](https://apps.apple.com/us/app/tampermonkey/id1482490089) 🍎

### Step 2: Add the Script 📜
1. Click this link to access the script: [AllChinaBuyEnhancerLoader.user.js](https://raw.githubusercontent.com/j7ps/AllChinaBuy-Enhancer/main/AllChinaBuyEnhancerLoader.user.js) 🔗
2. Tampermonkey will detect the script and prompt you to install it. Click **Install**. ✅
3. Once installed, the script will automatically run on [allchinabuy.com](https://www.allchinabuy.com/). 🎉

### Step 3: Verify It Works 👀
- Visit [allchinabuy.com](https://www.allchinabuy.com/). 🏪
- Look for prices (e.g., "¥100")—they should now show USD equivalents like "¥100 ($14.50 USD)" within a second or two. 💲

## How It Works 🔍
- The script is hosted externally and loaded via a small loader script. 📥
- It uses a free exchange rate API to get the latest CNY-to-USD rate. 📈
- Prices are updated dynamically as you browse, even when new content loads. 🔄

## Troubleshooting 🐛
- **Prices not converting?** Ensure Tampermonkey is enabled and the script is active. Refresh the page. 🔄
- **Errors?** Open your browser console (F12 > Console) and check for messages. Report issues [here](https://github.com/j7ps/AllChinaBuy-Enhancer/issues). 🚨

## Contributing 🤝
Feel free to fork this repo and submit pull requests with improvements! Suggestions are welcome via [issues](https://github.com/j7ps/AllChinaBuy-Enhancer/issues). 🌟

## License 📝
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details. ⚖️
