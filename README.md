# SMC Trader Backend for Hugging Face Spaces

This repository is currently a placeholder for an SMC Trader backend intended for Hugging Face Spaces with SQLite support. The tracked tree contains only a README and does not yet include Python source, requirements, a Space configuration, or an API entry point.

## Intended deployment

A future implementation should document the Space SDK/runtime, the ASGI or WSGI entry point, SQLite schema and persistence limitations, environment variables, and the API contract consumed by the SMC Trader frontend. Hugging Face Spaces storage and secrets should be configured through the platform rather than committed to Git.

## Recommended safeguards

Separate read-only market analysis from order execution, default to paper trading, validate external data, rate-limit public endpoints, and add tests for signal calculations and database migrations. Do not expose broker tokens or model-provider keys to the browser.

## Status

Initialization only. No runnable backend code is present in the current revision.
