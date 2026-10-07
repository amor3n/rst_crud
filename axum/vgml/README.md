# VGML
Vehicle Garage & Mod Log
- Track vehicles, custom installed parts, and specs.

``
Data shape: Vehicle { id, make, model, year, odometer_km }

Operations:

    POST /vehicles — Register a vehicle.

    GET /vehicles/:id — Get vehicle details.

    PATCH /vehicles/:id/odometer — Update just the mileage.

    DELETE /vehicles/:id — Remove a vehicle.