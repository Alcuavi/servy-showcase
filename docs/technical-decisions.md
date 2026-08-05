# Technical decisions — SERVY

Engineering choices that demonstrate **how** the system was built, not just **what** tools were used.

### Hash chain in-app

Each fiscal record links to the previous hash — tamper evidence without trusting a third-party black box.

### pgx over ORM

POS latency and explicit SQL matter more than ORM convenience here.

### Route groups per role

Kitchen staff never see cashier flows — same deploy, tailored surfaces.

