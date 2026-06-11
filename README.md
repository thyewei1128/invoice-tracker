# Invoice Tracker

A simple, single-file tracker for invoice cases with partial payment support.

- Track each case: invoice issued → payment from customer → cash from supplier → cash paid to client
- Partial payments on every leg, with automatic No / Partial / Full status
- Cash Book with running cash-on-hand balance (including own money in/out)
- Profit & loss summary, CSV export, JSON backup/restore

**Note:** All data is stored locally in your own browser (localStorage). Nothing is uploaded to any server. Use the in-app **Backup** button to download your data, and **Restore** to load it on another device.
