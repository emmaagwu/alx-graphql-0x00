# GraphQL Queries - Rick and Morty API

This project demonstrates how to use GraphQL to fetch character data from the Rick and Morty API.

## GraphQL Endpoint
`https://rickandmortyapi.com/graphql`

---

## Task 0 - Get Specific Character by ID
Queries and outputs for retrieving a single character by their ID.

Files:
- `character-id-1.graphql` … `character-id-4.graphql`
- `character-id-1-output.json` … `character-id-4-output.json`

---

## Task 1 - Get a List of All Characters (Paginated)
Queries and outputs for retrieving a paginated list of characters.

### Fields Retrieved:
- `id`
- `name`
- `status`
- `image`

### Example Query:
```graphql
query {
  characters(page: 1) {
    results {
      id
      name
      status
      image
    }
  }
}
