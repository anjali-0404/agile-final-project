# Need the ability to update a product in the catalog.

As a product manager I need to update product info so that listings remain accurate.

---

## Acceptance Criteria (Gherkin)

**Scenario: Update product information**
Given a product exists with id `123`
When I send a PATCH /products/123 with updated fields
Then the API returns HTTP 200 and the product is updated with the new values

Labels: enhancement

Estimate: 3
