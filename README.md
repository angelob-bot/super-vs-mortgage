# Divergent Wealth Home Loan Stress Test Calculator

A static, browser-based calculator for modelling home loan repayments, rate stress testing, ownership costs, investment-property cashflow and projected equity.

## Current status

This is version 1. It is deliberately simple, transparent and self-contained.

## Files

- `index.html` - offline/internal version. Open directly in a browser. No server required.
- `squarespace-embed.html` - suggested Squarespace embed approach.
- `assumptions.md` - model assumptions, compliance boundaries and known exclusions.

## Intended use

This calculator is intended to help Divergent Wealth model scenarios such as:

- owner-occupier mortgage repayment sensitivity
- investment-property cashflow before tax
- simplified after-tax investment cashflow
- rate-rise and rate-fall comparison
- property value and equity projection
- offset and extra repayment modelling

## Important compliance position

This is general information only. It is not personal financial advice, tax advice, legal advice, credit assistance or a lending recommendation.

The calculator does not assess borrowing capacity, loan eligibility, product suitability, affordability, refinancing costs, stamp duty, depreciation, CGT, land tax thresholds or client objectives and circumstances.

## Offline use

1. Download or clone the repository.
2. Open `index.html` in Chrome, Edge or Safari.
3. Enter the scenario inputs.
4. No data is saved or transmitted.

## Squarespace use

The recommended Squarespace approach is to host the static calculator and embed it with an iframe. This is more reliable than pasting a large script directly into a Squarespace code block.

See `squarespace-embed.html` for the starter embed snippet.

## Future improvements

Possible version 2 improvements:

- separate interest-only period modelling
- stamp duty estimator by state
- refinance break-even calculator
- rent-versus-buy comparison
- detailed capital growth sensitivity table
- downloadable PDF summary
- client-safe export without storing data
- branded printable assumptions page
