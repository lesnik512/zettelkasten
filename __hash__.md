To make a class hashable, it has to implement both the `__hash__(self)` method and  [[__eq__]]

## gotchas
- The hash of an object must never change during its lifetime
- Hashable objects which compare equal must have the same hash value (and vice versa)