# Need the ability to retrieve a product from the catalog.

As a shopper I need to retrieve a product by its id so that I can view product details.

---

## Acceptance Criteria (Gherkin)

**Scenario: Retrieve an existing product by id**
Given a product exists with id `123`
When I request GET /products/123
Then the API returns HTTP 200 and the product details in JSON

Labels: enhancement

Estimate: 3
