# Requirements — Expense Tracker

## Functional requirements
| ID | Requirement | Priority | Assignment |
|---|---|---|---|
| FR-01 | Create an expense with title, amount, date and category. | Must | A2 |
| FR-02 | View all saved expenses in a list. | Must | A2 |
| FR-03 | Edit an existing expense. | Must | A2 |
| FR-04 | Delete an expense after confirmation. | Must | A2 |
| FR-05 | Store records locally and retain them after restart. | Must | A2 |
| FR-06 | Search expenses by title. | Must | A2 |
| FR-07 | Filter expenses by category. | Must | A2 |
| FR-08 | Dashboard displays total spending for selected month. | Must | A2 |
| FR-09 | Sort expenses by date or amount. | Should | A3 |
| FR-10 | Capture and attach a receipt photo using camera. | Must | A3 |
| FR-11 | Display category-wise spending summary. | Should | A3 |
| FR-12 | Export records to CSV. | Could | A4 |

## Non-functional requirements
| ID | Requirement | Measurement |
|---|---|---|
| NFR-01 | Common screens load quickly. | Dashboard/list visible within 2 seconds with 500 sample records on test device. |
| NFR-02 | Expense data remains available offline. | Create in airplane mode, restart app, confirm record remains. |
| NFR-03 | Forms prevent invalid data. | Empty title and zero/negative amount rejected in validation tests. |
| NFR-04 | Interface is readable on common Android sizes. | Test on two emulator sizes; no clipped primary controls. |

Authentication is excluded. Android is the demonstration platform. SQLite is the planned local database. Camera receipt capture is the single selected device integration.
