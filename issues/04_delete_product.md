# Need the ability to delete a product from the catalog.

As an admin I need to delete products so that obsolete items are removed.

---

## Acceptance Criteria (Gherkin)

**Scenario: Delete a product**
Given a product exists with id `123`
When I send DELETE /products/123 as an authorized admin
Then the API returns HTTP 204 and the product is no longer retrievable (GET returns 404)

Labels: enhancement

Estimate: 3
