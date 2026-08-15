# Al-Nouman Electronics

**Al-Nouman Electronics** is a multi-device inventory and accounting system for an electronics store. It centralizes stock operations, sales activity, profit and loss reporting, and cloud-backed data synchronization in a single workflow.

The system manages two inventory categories—**spare parts** and **ready-made electronics**—while keeping product quantities, pricing, specifications, sales, losses, and operational history organized and accessible.

| Area | Capabilities |
|---|---|
| Inventory | Add, search, organize, and manage products across spare parts and ready-made electronics. |
| Product details | Store quantities, cost and selling prices, USD values, and product specifications. |
| Sales and losses | Record sales and losses, automatically adjust stock quantities, and retain a complete operation log. |
| Financial reporting | Calculate inventory value, operating balance, expected profit, and monthly profit/loss totals per category and for the full store. |
| Currency handling | Maintain USD-based prices with an editable USD-to-SYP exchange rate for Syrian pound calculations and reporting. |
| Data portability | Export and restore backups in JSON format and export products, sales, and losses to Excel workbooks. |

## Multi-Device Synchronization

Changes to inventory, sales, losses, and exchange-rate settings are synchronized through cloud storage. When an authorized user adds, edits, sells, deletes, or records a loss, the updated store data is available across connected devices using the application.

> The system is designed to keep the team working from the same shared inventory, sales history, loss records, and exchange-rate settings.

## Approved-User Access

The mobile application provides account-based access with sign-in, sign-up, password recovery, and session handling. Access can be limited to an approved set of users so that only authorized people can operate the store’s shared data.

## Interfaces

The project includes an Arabic right-to-left web interface and a mobile application. Both provide the core store-management workflow, including inventory actions, financial summaries, history tracking, backups, and settings.

| Technology | Role |
|---|---|
| Next.js and React | Web application interface. |
| Supabase | Cloud data storage and synchronization. |
| PWA | Installable web experience on compatible devices. |
| Expo | Mobile application located in the `mobile` directory. |

## Local Development

Install dependencies and start the web development server:

```bash
npm install
npm run dev
```

Then open `http://localhost:3000`.

## Owner

**Al-Nouman Electronics**  
By **Elias Ajeep**
