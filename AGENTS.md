## Testing / e2e

- **E2E:** critical journeys (signup/login/checkout/create-then-list), cross-layer wiring (UI→API→DB→email/webhook), browser/network-only regressions, thin release smoke.
- **Prefer unit/integration** for pure logic, single-service contracts, and flaky/heavy infra asserts.
- **Rule of thumb:** few high-value e2e; push the rest down the pyramid.
- See `.cursor/rules/e2e-testing.mdc` for the full rule.
