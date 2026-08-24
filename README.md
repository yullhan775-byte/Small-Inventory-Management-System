My individual module from a group Java project. My portion specifically implements a **staff-facing PPE inventory management system** for hospitals.

## What This Module Does

### Staff Menu (Homepage)
The main entry point with navigation to three sections — Hospitals, Suppliers, and Inventory.

### Hospitals
Manage hospital records and their PPE stock levels. Each hospital entry tracks stock quantities across six PPE categories:
- HC (Head Cover), FS (Face Shield), MS (Mask), GL (Gloves), GW (Gowns), SC (Shoe Covers)

Supports full **Create, Update, Delete** operations with a Save function to persist data.

### Suppliers
Manage supplier records showing which PPE types each supplier carries, displayed as true/false per category. Supports full **Create, Update, Delete** operations with a Save function.

### Inventory
View and manage the full PPE stock list with:
- **Low stock alert** — "Below 25" filter to quickly identify items running low
- **Item code search** — filter inventory by item code
- **Date range search** — filter transaction history by start and end period
- **Distribute Items** — record outgoing stock distribution to hospitals
- **Request Item** — submit a stock replenishment request
- **Print** — print the current inventory table

## Requirements

- Java 21 or above
- Apache NetBeans IDE

## How to Run

1. Open NetBeans
2. Go to **File → Open Project** and select the project folder
3. Right-click the project and select **Clean and Build**
4. Run the project — it will open the Staff Menu homepage

## Data Storage

This project uses text files for data persistence. The following files must remain in the project root directory:

- `Hospital.txt` — hospital records and PPE stock levels
- `Supplier.txt` — supplier records and PPE categories
- `ppe.txt` — PPE inventory items
- `transaction.txt` — distribution and request transaction history

## Notes

- The project was built using NetBeans GUI designer (Swing), so `.form` files are required alongside `.java` files
- Data is saved manually using the "Save Table Data" button — changes are not auto-saved
