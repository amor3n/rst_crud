# WHSM
Werehouse Stock Manager
- A basic product inventory tracker for a store.

``
Data shape: Item { id, name, sku, quantity, price }

Operations:

    POST /items — Add a new item to stock.

    GET /items — View all items (or filter by name).

    PUT /items/:id — Update stock count or price.

    DELETE /items/:id — Remove an item from the system.