# Andy-DB NodeJS GraphQL Implementation

This directory contains a basic GraphQL server implementation using Express and GraphQL for the Andy-DB project.

## Setup

1.  Navigate to the `nodejs`
    directory:

    cd nodejs

2.  Install dependencies:

    npm install

3.  Start the GraphQL server:

    npm start

4.  Open a browser and navigate to `http://localhost:4000` to access the GraphiQL interface.

## Testing

You can test the server by running a simple query in the GraphiQL interface:

```graphql
query {
  hello
}
```

You should see the response:

```json
{
  "data": {
    "hello": "Hello, world!"
  }
}
```
