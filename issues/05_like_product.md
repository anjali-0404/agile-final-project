# Need the ability to Like a product in the catalog.

As a shopper I need to like a product so that popular items can be surfaced.

---

## Acceptance Criteria (Gherkin)

**Scenario: Like a product**
Given a user is authenticated
When the user sends POST /products/123/like
Then the product's like count increments by 1 and API returns HTTP 200

Labels: enhancement

Estimate: 3
