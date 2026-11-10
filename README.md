# Facility Ops — Maintenance & Inventory

A standalone facility-management maintenance tracker for inventory, SMRF material requests, cost-saving initiatives, and monthly historical performance.

## Run it

Open `index.html` in a current desktop or mobile browser. No installation, build step, server, or internet connection is required. The application stores its data in the browser's `localStorage` on the device where it is opened.

## Modules

- **Dashboard:** inventory and low-stock totals, open requests, recorded savings, recent activity, and a six-month maintenance-spend/savings chart.
- **Inventory:** add, search, update, and remove items; set unit costs and reorder levels; export the register as CSV.
- **SMRF Requests:** create and track Store/Material Requisition Forms. Fulfillment checks available stock and deducts the requested quantity.
- **Cost Saving:** record dated savings by initiative and category; entries feed the dashboard's historical chart and can be exported.

The first launch includes sample records to demonstrate the dashboard. All changes remain in the current browser profile. Clearing browser site data removes those records, so export CSV files periodically for backup. This is a local single-user starter app and does not provide accounts, shared data, or server-side backups.
