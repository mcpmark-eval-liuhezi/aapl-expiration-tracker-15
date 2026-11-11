# Contributing

Thanks for contributing to the AAPL expiration tracker. All market figures must come from live data (Yahoo Finance), and where a number looks odd, report exactly what the source returned.

## Weekly workflow

1. Pull the latest AAPL profile and option expiration dates.
2. Take the three soonest upcoming expirations.
3. For each: find the ATM strike (closest to spot), the highest-open-interest call strike, and the highest-open-interest put strike.
4. Create tracking issues (Expiry YYYY-MM-DD) with the stats.
5. Open a PR with expirations.md and a per-expiration stats table.

## Repository hygiene

- Keep workflow runs tidy: after triggering the manual workflow, delete its logs.
- Check discussion categories when possible and report findings.
