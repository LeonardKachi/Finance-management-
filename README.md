# Financial Framework

A free, single-file, client-side financial literacy tool. No backend, no sign-up, no data collection - everything a visitor types is calculated in their own browser and never leaves their device.

Built for anyone starting to take their money seriously: students, early-career professionals, or anyone who's never had a clear picture of where their income actually goes.

## What it does

- **Adaptive budget targets** - financial independence portfolio size, monthly investing target, housing and rent ceilings, guilt-free spending, and emergency fund target. The percentages behind these automatically shift based on how much room your income gives you over your expenses (see "Budget modes" below).
- **Debt, insurance, and affordability** - debt-to-income ceiling and your actual ratio, a car/transport spending cap, and a starting life insurance benchmark.
- **Growth and time** - Rule of 72 (years to double your money at a given return) and an age-based retirement savings benchmark.
- **Compound growth calculator** - projects a starting amount plus monthly contributions at an expected return, and separates the final value into what you contributed versus what the market added.
- **Investing 101** - plain-language explanations of nine investment types (savings accounts, CDs, bonds, individual stocks, index funds/ETFs, mutual funds, REITs, retirement accounts, cryptocurrency), each with a risk level, typical return range, and what to watch for.
- **How the stock market works** - what a share actually is, how volatility and diversification work, and why time in the market matters more than timing it.
- **Study budget for a block account** - built for students living on a blocked account (Sperrkonto) during study. Rent is entered directly since it's a known, fixed cost; everything else (feeding, transport, phone & data, household items, laundry) is split by percentage, each with an optional comfortable ceiling. Any amount over a ceiling is automatically redirected to savings instead of being spent.
- **Downloadable PDF reports** - two separate one-click reports (financial breakdown, and study budget) built from whatever is currently filled in, generated via the browser's native print-to-PDF, no external service involved.
- **Light/dark mode** - follows the visitor's system preference by default, with a manual toggle that's remembered on their device.

### Budget modes

The core budget percentages aren't fixed. They adjust based on the ratio of monthly net income to monthly expenses:

| Mode | When it applies | What it does |
|---|---|---|
| Building stability | Net income is close to expenses | Leans toward covering needs first (higher housing/rent allowance, smaller guilt-free spending), with a small but real 5% investing habit and a 3-month starter emergency fund |
| Balanced | Income comfortably clears expenses | The standard, widely used split: 20% invested, 60% housing cap, 30% rent ceiling, 20% guilt-free, 6-month emergency fund |
| High performer | Income clears expenses by a wide margin | Mirrors research on self-made millionaires' saving habits: investing rises toward 30%, while housing and rent ceilings tighten to resist lifestyle inflation |

This only activates once both net income and expenses are entered - without both, it defaults to the balanced/standard figures.

## Running it

This is a single static HTML file with no build step and no dependencies beyond Google Fonts-free system fonts.

**Locally:** open `financial-framework.html` directly in a browser.

**On GitHub Pages:**
1. Push this repo to GitHub.
2. In the repo settings, enable GitHub Pages for the branch you're using.
3. Either rename `financial-framework.html` to `index.html`, or point GitHub Pages at it directly if your Pages settings allow a custom entry file.

## Project structure

```
.
├── index.html   # the entire site - HTML, CSS, and JS in one file
└── README.md
```

## Disclaimer

This tool applies general, widely used rules of thumb to the numbers a visitor provides. It is not financial advice and doesn't account for taxes, dependents, local cost of living, or individual circumstances. It's a starting point for thinking about money, not a final answer - the site says as much in its own "About" section.

## License
MIT License 
