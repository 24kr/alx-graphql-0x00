
**README.md for Episodes:**

```markdown
# Episodes

This project provides information about various episodes, including their id, name, air_date, and episode code.

## Example GraphQL Query

To fetch details of specific episodes, use the following GraphQL query:

```graphql
query {
  episode1: episode(id: "1") {
    id
    name
    air_date
    episode
  }
  episode2: episode(id: "2") {
    id
    name
    air_date
    episode
  }
  episode3: episode(id: "3") {
    id
    name
    air_date
    episode
  }
  episode4: episode(id: "4") {
    id
    name
    air_date
    episode
  }
}
