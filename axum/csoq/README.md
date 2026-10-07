# CSOQ
Coffee Shop Order Queue
- Track incoming orders for a cafe and update their status.

``
Operations:

    POST /orders — Place an order (starts as "Pending").

    GET /orders — View active orders.

    PUT /orders/:id/status — Change status to "Preparing" or "Completed".

    DELETE /orders/:id — Cancel/remove an order.