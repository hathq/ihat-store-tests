# Shared placement conformance

Package: `@hathq/ihat-store-tests`, immutable development version **0.10.0**.

Run `pnpm install --offline --frozen-lockfile`, then `pnpm test`. Dependencies resolve immutable local 0.10.0 archives. The test directory is included in this package; Playwright is observation tooling, not a product runtime dependency.

Compound scenarios cover exact local/web parity, bounded queries/cursors, stale source rejection, real loopback source reads, desktop/mobile native rendering, CSP data safety, confirmed install request identity and cleanup. The command spy cannot prove actual installation. Root `tools/hatter-delivery-store-proof.mjs` separately checks a signed current HAT through an isolated installed Hatter binary and the normal browser path.

No semantic, control, installation, credential or renderer authority is transferred
to iHat. Acceptance and remaining work are recorded in
`docs/architecture/ihat-online-architecture.json` at the Wonderland root.
