# SGSL
Simple Grocery Shopping List
- Track items to buy, quantities, and whether they've been bought.

``
Data shape: GroceryItem { id, name, quantity, is_bought: bool }

Operations:

    POST /groceries — Add an item to the list.

    GET /groceries — List everything.

    PATCH /groceries/:id/toggle — Flip is_bought from false to true.

    DELETE /groceries — Clear the list.