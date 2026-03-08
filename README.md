# Probability Calculators

A single-file suite of betting and probability calculators, deployable via GitHub Pages.

## Calculators

| # | Calculator | Purpose |
|---|---|---|
| 01 | **Expected Value** | Multi-outcome EV with decimal, American, or fractional odds |
| 02 | **Base Rates** | Strip margin/vig, compare fair implied probability to your estimate |
| 03 | **Bayesian** | Update beliefs with new evidence using Bayes' theorem |
| 04 | **Kelly Criterion** | Optimal stake size — Full, Half, and Quarter Kelly |

## Deploy to GitHub Pages

1. Create a new GitHub repository (e.g. `prob-calculators`)
2. Add `index.html` to the root of the repo
3. Go to **Settings → Pages**
4. Under **Source**, select `Deploy from a branch` → `main` → `/ (root)`
5. Save — your site will be live at `https://<your-username>.github.io/<repo-name>/`

## Usage Notes

- **Odds formats**: All calculators support Decimal, American, and Fractional odds
- **Kelly Criterion**: Kelly assumes your probability estimate is accurate. Use Half or Quarter Kelly for risk management
- **Bayesian**: Bayes factor > 3 is typically considered moderate evidence; > 10 is strong
- **Base Rates**: Works best with 2-sided markets (e.g. match winner) or 3-sided (e.g. 1X2)

## Files

```
index.html   ← entire app (single file, no dependencies except Google Fonts)
README.md
```

No build step. No npm. No framework. Just open `index.html`.
