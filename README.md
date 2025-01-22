# GraphQL Query to Get a Specific Character by ID

## Objective
Write a GraphQL query to retrieve a specific character’s information using their ID.

## Endpoint
Use the following GraphQL endpoint for the queries.

## Instructions
1. Write a GraphQL query using the `character(id: ID!)` field to fetch the details of a character.
2. Use IDs: 1, 2, 3, 4.
3. Include the following fields in your query:
   - id
   - name
   - status
   - species
   - type
   - gender

## Files
- `character-id-1.graphql`: Query for character with ID 1.
- `character-id-1-output.json`: Expected output for ID 1.
- `character-id-2.graphql`: Query for character with ID 2.
- `character-id-2-output.json`: Expected output for ID 2.
- `character-id-3.graphql`: Query for character with ID 3.
- `character-id-3-output.json`: Expected output for ID 3.
- `character-id-4.graphql`: Query for character with ID 4.
- `character-id-4-output.json`: Expected output for ID 4.
# Get a List of All Characters (Paginated)

This task retrieves a paginated list of characters using the `characters(page: Int)` field in the GraphQL API.

## Files

- `characters-page-1.graphql` - Query to fetch page 1 of characters.
- `characters-page-1-output.json` - Output of the query for page 1.
- `characters-page-2.graphql` - Query to fetch page 2 of characters.
- `characters-page-2-output.json` - Output of the query for page 2.
- `characters-page-3.graphql` - Query to fetch page 3 of characters.
- `characters-page-3-output.json` - Output of the query for page 3.
- `characters-page-4.graphql` - Query to fetch page 4 of characters.
- `characters-page-4-output.json` - Output of the query for page 4.

## Instructions

1. Run each query in a GraphQL client.
2. Save the JSON response in the corresponding output file.
3. Ensure each query retrieves the following fields:
   - `id`
   - `name`
   - `status`
   - `image`
