# GraphQL Queries - Rick and Morty API (Episode Queries)

This folder contains queries for retrieving episode data from the Rick and Morty API using GraphQL.

## GraphQL Endpoint
`https://rickandmortyapi.com/graphql`

---

## Task 2 - Get Specific Episode by ID

### Objective:
Fetch details of a specific episode using its ID.

### Fields Retrieved:
- `id`
- `name`
- `air_date`
- `episode`

### Example Query:
```graphql
query {
  episode(id: 1) {
    id
    name
    air_date
    episode
  }
}
