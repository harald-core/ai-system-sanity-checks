# Input Boundaries

Question:
Do we actually know what inputs this system can receive?

Not what we documented.
Not what we intended.

What inputs does the system receive in practice?

Consider:
- inputs created by other systems
- retries, partial failures, cached states
- user behavior that optimizes against the system

If an input cannot be described clearly,
it cannot be bounded.

If it cannot be bounded,
it cannot be made safe.
