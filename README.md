# MotherDuck (motherduck)

MotherDuck is a serverless cloud data warehouse built on DuckDB. Connectivity is via DuckDB clients (Python, Node.js, Wasm, Go, JDBC) using access tokens or SSO; the service does not publicly document a separate REST management API.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/motherduck/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=motherduck-api-evangelist&utm_content=repo)

## Type
- **x-type:** company

## APIs
- **MotherDuck DuckDB Connection** - DuckDB-native protocol via `md:?token=<access_token>`. Clients: DuckDB CLI, Python, Node.js, JDBC, Wasm, Go.

## Tags
- Data Warehouse, Serverless, DuckDB, SQL, Analytics

## Timestamps
- **Created:** 2026-05-08
- **Modified:** 2026-05-08

## Common Properties
- [Website](https://motherduck.com/)
- [Developer Portal](https://motherduck.com/docs/)
- [Pricing](https://motherduck.com/pricing/)
- [Plans](plans/motherduck-plans-pricing.yml)
- [RateLimits](rate-limits/motherduck-rate-limits.yml)
- [FinOps](finops/motherduck-finops.yml)

## Notes
- Pricing reconciled (research): Lite (free, 10 GB / 10 compute hours), Business $250/mo + usage, Enterprise custom. Compute per second from Pulse $0.60/hr to Giga $36/hr; storage $0.04/GB-month; AI Functions $1.00 per AI Unit.
- No standalone REST management API — auth and queries route through the DuckDB client connection.
- No public OpenAPI spec.

## Maintainers
**FN:** Kin Lane

**Email:** kin@apievangelist.com
