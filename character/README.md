# Characters

This project provides information about various characters, including their id, name, status, species, type, and gender. 

## Example GraphQL Query

To fetch details of specific characters, use the following GraphQL query:

```graphql
query {
  character(id: "1") {
    id
    name
    status
    species
    type
    gender
  }
  character(id: "2") {
    id
    name
    status
    species
    type
    gender
  }
  character(id: "3") {
    id
    name
    status
    species
    type
    gender
  }
  character(id: "4") {
    id
    name
    status
    species
    type
    gender
  }
}
