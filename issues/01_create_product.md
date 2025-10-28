# Need the ability to create a product in the catalog.

As a product manager I need to create a product in the catalog so that new items can be sold and tracked.

---

## Acceptance Criteria (Gherkin)

**Scenario: Create a new product successfully**
Given I am an authenticated product manager
When I submit valid product data (name, description, price, stock)
Then the product should be created and return HTTP 201 with the created product ID

Labels: enhancement

Estimate: 3
