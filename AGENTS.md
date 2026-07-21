# Agent Contract

This public repository owns the Dinkus Mix-and-Match Bundles extension for
AICommerce on EmDash. Keep it generic: site copy, customer data, Smoky branding,
credentials, and production configuration do not belong here.

## Boundary

- AICommerce owns the catalog/cart/order/payment lifecycle, canonical line
  graph, promotion pipeline, and inventory-provider contracts.
- This extension owns Mix-and-Match definitions, configuration validation,
  storefront/admin UX, line-graph expansion, snapshots, and migration.
- Never flatten child fulfillment/economic identity or become a second stock or
  promotion writer.
- Composite/configurator products and manufacturing/MRP are not owned here.

## Bootstrap State

This is a design stub. Add implementation only through an isolated branch and
worktree with tests, proof, and a documented `@dinkuskit/commerce-sdk` range.
Keep the package private until its dogfood and release gates pass.

## Gates

Do not publish to npm, list in an EmDash marketplace or registry, deploy,
merge, or mutate a production site without Bobby's explicit approval. Keep
EmDash pre-1.0 compatibility claims bound to exact proof.
