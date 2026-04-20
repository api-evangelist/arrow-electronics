# Arrow Electronics (arrow-electronics)
Arrow Electronics is a global provider of products, services, and solutions to industrial and commercial users of electronic components and enterprise computing solutions. With over 2,200 suppliers and more than 200,000 customers worldwide, Arrow serves as a vital link in the technology supply chain, enabling the design, manufacture, and operation of electronic components. Arrow provides REST APIs for pricing and availability lookups, order placement, and supply chain automation, enabling distributors, OEMs, and procurement teams to integrate electronic component sourcing directly into their systems.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/arrow-electronics/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Electronics, Components, Supply Chain, Procurement, Distribution

## Timestamps

- **Created:** 2024-12-03
- **Modified:** 2026-04-19

## APIs

### Arrow Electronics Pricing and Availability API
The Arrow Electronics Pricing and Availability API enables programmatic search for electronic components, retrieval of real-time pricing data, and inventory availability across Arrow's global inventory pools including ACNA/NAC, VERICAL, EUROPE, ASIA, AEP, C1S, PSG, and RFPD. Returns results in JSON or XML format.

**Human URL:** [https://developers.arrow.com/api/index.php/site/page?view=Itemservice](https://developers.arrow.com/api/index.php/site/page?view=Itemservice)

#### Tags:

 - Pricing, Availability, Electronics, Components, Inventory

#### Properties

- [Documentation](https://developers.arrow.com/api/index.php/site/page?view=Itemservice)
- [Authentication](https://developers.arrow.com/api/index.php/site/page?view=gettingStarted)

### Arrow Electronics Order API
The Arrow Electronics Order API enables automated order placement for electronic components at Arrow.com and Verical.com, and allows programmatic retrieval of order status information for existing orders. Requires SHA-256 encoded credentials and a Credit account.

**Human URL:** [https://developers.arrow.com/api/index.php/site/page?view=orderApi](https://developers.arrow.com/api/index.php/site/page?view=orderApi)

#### Tags:

 - Orders, Procurement, E-Commerce, Supply Chain

#### Properties

- [Documentation](https://developers.arrow.com/api/index.php/site/page?view=orderApi)
- [Authentication](https://developers.arrow.com/api/index.php/site/page?view=gettingStarted)

## Common Properties

- [Developer Portal](https://developers.arrow.com/)
- [Getting Started](https://developers.arrow.com/api/index.php/site/page?view=gettingStarted)
- [Best Practices](https://developers.arrow.com/api/index.php/site/page?view=bestPractices)
- [Terms and Conditions](https://developers.arrow.com/api/index.php/site/page?view=terms)
- [Arrow Electronics Website](https://www.arrow.com/)
- [API Support Email](mailto:api@arrow.com)

## Features

| Name | Description |
|------|-------------|
| Global Inventory Search | Search across up to 8 global inventory pools simultaneously including Arrow NAC, Verical, European, Asian, and specialty component inventories. |
| Real-Time Pricing | Retrieve current pricing data for electronic components including quantity breaks, lead times, and packaging options. |
| Automated Order Placement | Place orders programmatically for components at Arrow.com and Verical.com without manual web interaction, enabling supply chain automation. |
| Order Status Tracking | Retrieve status information for existing orders to track fulfillment and shipping progress programmatically. |
| Multi-Format Support | APIs return data in JSON (default) and XML formats, with JSONP support for browser-based integrations. |

## Use Cases

| Name | Description |
|------|-------------|
| ERP Integration | Manufacturers and distributors integrate Arrow's Pricing and Availability API with their ERP systems (SAP, Oracle, etc.) to automate component sourcing and procurement workflows. |
| Bill of Materials Pricing | Design engineers use the API to retrieve bulk pricing for entire Bills of Materials during product cost estimation and component selection. |
| Automated Procurement | Procurement systems use the Order API to automatically replenish component inventory when stock reaches reorder thresholds. |
| Supply Chain Visibility | Operations teams use availability data across multiple inventory pools to manage component risk and identify alternative sourcing options. |

## Integrations

| Name | Description |
|------|-------------|
| Verical | Arrow's Verical marketplace for independent distribution is accessible via the same API infrastructure, extending component sourcing to the spot market. |
| Arrow Enterprise Computing Solutions | Integration with Arrow's enterprise computing division for server, storage, and cloud component procurement alongside electronic components. |

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
