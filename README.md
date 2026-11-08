# IDL integration flows: ALPHA ORDERS (Act 5 demo repository)

Versioned package of the Lobster flow ALPHA ORDERS (EDIFACT D.96A) to canonical order 1.1, promoted through three stages:

| Stage | Lobster instance | Profile |
|---|---|---|
| Dev | lobster-poc-ldp | TEST_ACT5_ALPHA_ORDERS_DEV |
| Test | lobster-poc-ldp | TEST_ACT5_ALPHA_ORDERS_TEST |
| Prod | demo-test | IDL_ACT5_ALPHA_ORDERS |

- `packages/ALPHA_ORDERS.package.json`: the flow's version (parsing, mapping, output), without stage-specific values (name, address, folder).
- `change_requests/`: the change requests the versions implement.
- `pipeline/`: the test results of each pipeline run (T1 to T6 of the regression test set).

Prod is changed only after an approval by a second person, with that person's own Lobster account.
