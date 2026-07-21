# bundles

`* * *`

Mix-and-match products for AICommerce on EmDash: selection, pricing, inventory,
shipping, fulfillment, and immutable order configuration. Planned package:
`@dinkuskit/bundles`.

AICommerce owns the generic parent/child line graph and checkout lifecycle.
This extension adds the optional Mix-and-Match product type, admin and
storefront configuration, and Woo migration. Stores that do not sell composed
products do not need it.

## Planned boundary

- exact or min/max integer selections with repeated concrete variations;
- fixed or per-item pricing without flattening child economic identity;
- versioned cart configuration and immutable purchased snapshots;
- atomic inventory reservation of the complete child-SKU vector;
- explicit external-promotion eligibility, shipping, tax, and refund facts;
- Woo Mix-and-Match import and parity fixtures;
- the same audited application services behind EmDash admin, REST, and MCP.

Composite/configurator products and general manufacturing kits are outside the
first product boundary.

## Status

Public design stub. There is no installable plugin or published npm package yet.
The package manifest is private at `0.0.0` to prevent accidental publication.

Part of [Dinkus](https://github.com/dinkuskit): blocks, AICommerce, commerce
extensions, and templates for [EmDash](https://github.com/emdash-cms/emdash)
sites. Commerce extensions depend on AICommerce; blocks and templates remain
independently usable.

Under construction, dogfooding in the open. MIT.
