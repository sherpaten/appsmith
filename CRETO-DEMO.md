# Creto Studio Demo Plan — Appsmith

This repository is the upstream Appsmith low-code application platform. The Creto demo will be a separately configured sample business dashboard running on Appsmith; it is not a claim that the upstream project was authored by Creto Studio.

## Demo concept
**Creto Operations Dashboard**

- Build a realistic sample operations dashboard with KPI cards, charts, customer/order tables, filters, and a detail view.
- Use synthetic data only. No real client, customer, employee, or business records.
- Demonstrate how Creto Studio can design and integrate internal tools and admin applications.
- Apply Creto branding to the demo app and its presentation, without removing required Appsmith branding/notices.

## Implementation boundary
Appsmith is a full application platform, not a small embeddable widget. The demo should run as an isolated Appsmith Community Edition instance with a separately configured sample application and data source. Do not attempt to bundle the Appsmith platform into the Creto Next.js website.

## Deployment prerequisites
- Follow the official self-hosted installation path for the selected Community Edition release (typically Docker-based).
- Provision persistent storage and the platform's required supporting services.
- Use a read-only or synthetic-data database for the public demo.
- Disable public write actions and protect any editor/admin console.

## Licensing and attribution
The repository root LICENSE is Apache 2.0. Retain the required licence, copyright, NOTICE (if present), and modification notices. Confirm the licence of each included module and avoid features or assets that require a separate commercial entitlement.

## Status
- [x] Demo scope documented.
- [ ] Confirm Community Edition boundaries and component-specific licences for the selected release.
- [ ] Build the sample operations dashboard with synthetic data.
- [ ] Deploy an isolated instance with public viewer access and protected editor access.
- [ ] Add the verified demo URL to Creto Studio Projects.
