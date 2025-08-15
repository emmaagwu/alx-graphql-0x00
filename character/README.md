# Get Specific Character by ID - GraphQL

This project demonstrates how to fetch a specific character’s information from the Rick and Morty API using GraphQL.

## GraphQL Endpoint
`https://rickandmortyapi.com/graphql`

## Query Fields
Each query retrieves the following fields for a given character ID:
- `id`
- `name`
- `status`
- `species`
- `type`
- `gender`

## Files Included
- `.graphql` files (character-id-1.graphql, character-id-2.graphql, etc.) containing the GraphQL query for each ID.
- Corresponding `.json` output files (character-id-1-output.json, etc.) containing the API response.

## Sample GraphQL Query
```graphql
query {
  character(id: 1) {
    id
    name
    status
    species
    type
    gender
  }
}
