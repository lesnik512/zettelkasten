Data can be inconsistent at some moments but it will be synched in the future.

In [[micro-services]], if data duplicated in several services, update events should be triggered.

The speed of propagation of changes depends on criticality of consistency and should be clear and configurable.

If the database system only supports eventual consistency, then the application will need to handle the possibility of reading stale data.