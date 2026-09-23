# Market IQ Prototype

This repository hosts the standalone, interactive dealer-facing Market IQ prototype.

**Prototype:** https://havenschris.github.io/market-iq-prototype/#inventory-pricing-module

## Prototype boundaries

- This is a static demonstration with sample dealer, inventory, market, and performance data only.
- It does not connect to dealer, customer, AI, or production services.
- Market IQ signals are calculated from the included sample data using the documented deterministic business rules.
- Pricing Strategy changes are stored only in the current browser and immediately recalculate the sample inventory's Aging and Aged signals.
- This Pages site and deployment workflow are independent of the Market IQ Admin prototype and all other prototype repositories.

Only the compiled dealer-facing static site is published here. Internal source packages, environment files, analytics, unrelated application screens, and the Market IQ Admin prototype are intentionally excluded.
