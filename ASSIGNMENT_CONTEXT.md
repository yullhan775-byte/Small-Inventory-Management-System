# Assignment Context & Requirements

This project was built as a group assignment.

## Assignment Brief

The system simulates a **PPE (Personal Protective Equipment) Inventory Management System** for a Department of Health that:
- Receives PPE items from multiple suppliers
- Distributes items to hospitals it manages

## PPE Items Tracked

| Item Code | Item Name    |
|-----------|--------------|
| HC        | Head Cover   |
| FS        | Face Shield  |
| MS        | Mask         |
| GL        | Gloves       |
| GW        | Gown         |
| SC        | Shoe Covers  |

## My Individual Contribution

- Hospital and Supplier Creation & Management
- Item Inventory Management
- Item Inventory Tracking (distribution and requests)

## Other Member Contribution (NOT SHOWN)

- User Management and Initial Inventory Creation & Management
- Searching Functionalities

## Key Restrictions & Requirements

The following constraints were imposed by the assignment brief — some design decisions were made specifically to meet these requirements:

1. **Java GUI only** — the system must use Java Swing (NetBeans GUI builder).

2. **File-based storage** — all data must be stored in `.txt` files.

3. **Fixed number of suppliers** — only 3 or 4 suppliers are allowed.

4. **Minimum 3 hospitals** — the system assumes at least 3 hospitals exist in the state.

5. **Inventory initialised at 100** — initial quantity for each PPE item is set to 100 boxes on first run only. (NOT SHOWN)

6. **Items measured in boxes** — all quantities are in boxes, not individual units.

7. **One supplier per item type** — each PPE item is supplied by exactly one supplier, though one supplier can supply multiple item types.


> Note: Some design choices (fixed supplier count, txt file storage, limited hospital entries) are intentional constraints from the assignment brief, not design limitations.
