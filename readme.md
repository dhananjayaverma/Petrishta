roject 4 — E-Commerce Platform with Reliable Checkout
Priority: P1 — A useful demonstration of transactional business logic.

Build a small commerce platform that demonstrates much more than displaying products.
Stack
- Next.js and TypeScript.
- Node.js API.
- PostgreSQL.
- Redis where useful.
- Payment provider sandbox.
- Background jobs.
- Docker and GitHub Actions.
Modules
catalog/
customers/
cart/
pricing/
inventory/
checkout/
payments/
orders/
notifications/
Important workflows
1. Browse products and manage a cart.
2. Calculate prices and discounts on the server.
3. Reserve or validate inventory.
4. Create an order.
5. Initiate payment.
6. Process payment-provider webhooks.
7. Update order status.
8. Notify the customer.
What you need to demonstrate
- Idempotent checkout requests.
- Duplicate webhook handling.
- Database transactions.
- Inventory consistency.
- Payment failures and retries.
- Correct separation between payment state and order state.
- Audit-friendly order history.
Use sandbox payments and synthetic data. Never store raw card details.

This project can be particularly useful for product-engineering roles because it demonstrates how software protects business operations and money.