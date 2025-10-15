# Episode GraphQL Queries

This directory contains GraphQL queries to retrieve episode information from the Rick and Morty API.

## Files

- `episode-id-1.graphql` - Query for episode with ID 1
- `episode-id-1-output.json` - Expected output for episode ID 1
- `episode-id-2.graphql` - Query for episode with ID 2
- `episode-id-2-output.json` - Expected output for episode ID 2
- `episode-id-3.graphql` - Query for episode with ID 3
- `episode-id-3-output.json` - Expected output for episode ID 3
- `episode-id-4.graphql` - Query for episode with ID 4
- `episode-id-4-output.json` - Expected output for episode ID 4

## Query Structure

All queries use the following structure:
```graphql
query GetEpisode {
  episode(id: [ID]) {
    id
    name
    air_date
    episode
  }
}