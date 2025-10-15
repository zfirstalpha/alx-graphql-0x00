# alx-graphql-0x00
# Character GraphQL Queries

This directory contains GraphQL queries to retrieve character information from the Rick and Morty API.

## Files

- `character-id-1.graphql` - Query for character with ID 1
- `character-id-1-output.json` - Expected output for character ID 1
- `character-id-2.graphql` - Query for character with ID 2
- `character-id-2-output.json` - Expected output for character ID 2
- `character-id-3.graphql` - Query for character with ID 3
- `character-id-3-output.json` - Expected output for character ID 3
- `character-id-4.graphql` - Query for character with ID 4
- `character-id-4-output.json` - Expected output for character ID 4

## Query Structure

All queries use the following structure:
```graphql
query GetCharacter {
  character(id: [ID]) {
    id
    name
    status
    species
    type
    gender
  }
}