# Pancake Swap Listing Tutorial

So, youÃƒÆ’Ã‚Â¢ÃƒÂ¢Ã¢â‚¬Å¡Ã‚Â¬ÃƒÂ¢Ã¢â‚¬Å¾Ã‚Â¢ve come, youÃƒÆ’Ã‚Â¢ÃƒÂ¢Ã¢â‚¬Å¡Ã‚Â¬ÃƒÂ¢Ã¢â‚¬Å¾Ã‚Â¢ve tasted our secret sauce ÃƒÆ’Ã‚Â°Ãƒâ€¦Ã‚Â¸Ãƒâ€šÃ‚Â¥Ãƒâ€¦Ã‚Â¾ and now youÃƒÆ’Ã‚Â¢ÃƒÂ¢Ã¢â‚¬Å¡Ã‚Â¬ÃƒÂ¢Ã¢â‚¬Å¾Ã‚Â¢re wanting to be a part of the PancakeSwap kitchen.

If youÃƒÆ’Ã‚Â¢ÃƒÂ¢Ã¢â‚¬Å¡Ã‚Â¬ÃƒÂ¢Ã¢â‚¬Å¾Ã‚Â¢re interested in listing on the PancakeSwap exchange, follow this guide closely.

## Requirements

If you are seeking to be added to the [Pancakeswap.finance](https://pancakeswap.finance/) exchange, you should open a [listing request issue](https://github.com/pancakeswap/pancake-swap-interface/issues/new?assignees=Chef-Chungus&labels=listing&template=listing-request.md&title=%5BListing%5D+Request+listing+for+%7BADD+TOKEN+NAME+HERE%7D). Someone from the team will review your application. Once it's validated, you can jump to the next step.

## Adding Tokens

1. Fork the [BudzSwap Dex Frontend](https://github.com/budzswap/budz-frontend-dex/) repository on GitHub
2. Upload your **logo** in a 96\*96px transparent .png format to the `/public/images/coins` directory. Please name the logo as your symbol in uppercase.

3. Add your **token information** using the example format provided below to `budzswap.json` in the `/src/constants/token/` directory.

4. Create a **pull request** detailing information about your project, website address, and contact details (telegram)

## Examples

**Logo format:**

`SYRUP.png`

**Token information format:**

```json
{
"name": "BudzSwap Token",
"symbol": "BUDZ",
"address": "0x1f546ad641b56b86fd9dceac473d1c7a357276b7",
"chainId": 56,
"decimals": 18,
"logoURI": "/images/coins/BUDZ.png"
},
```

If you're not comfortable with GitHub pull requests, please open a [new issue](https://github.com/budzswap/budz-frontend-dex/issues/new) requesting to be added.

## Reviews

Once added, tokens are also re-reviewed at regular intervals in order to maintain quality assurance in-line with the below criteria, and may be removed should severe and/or unresolved issues be encountered.

### Criteria

- Volume
- Liquidity
- Community feedback