# GraphQL Restaurant Data Exercise

## Overview
This project is designed to cover the basics of GraphQL by working with restaurant data. GraphQL server in this occasion allows querying and mutating restaurant information.

## Features
- Query restaurant details
- Add new restaurants
- Update existing restaurant information
- Delete restaurants

## Getting Started

### Prerequisites
- Node.js
- npm or yarn

### Installation
1. Clone the repository:
    ```bash
    https://github.com/AlvisPr/GraphQL-Restaurant-Data-Exercise
    ```
2. Navigate to the project directory:
    ```bash
    cd graphql-restaurant-data-exercise
    ```
3. Install dependencies:
    ```bash
    npm install
    ```
    or
    ```bash
    yarn install
    ```

### Running the Server
Start the GraphQL server:
```bash
npm start
```
or
```bash
yarn start
```

The server will be running at `http://localhost:4000/graphql`.

## Usage
You can use tools like [GraphiQL](https://github.com/graphql/graphiql) or [Postman](https://www.postman.com/) to interact with your GraphQL server. You can modify and add data as you want as long as the server is running. It doesn’t rewrite the data object in the code.

### Example Queries
- **Get all restaurants:**
    ```graphql
    {
      restaurants {
        id
        name
        cuisine
        location
      }
    }
    ```

- **Add a new restaurant:**
    ```graphql
    mutation {
      addRestaurant(name: "New Restaurant", cuisine: "Italian", location: "New York") {
        id
        name
      }
    }
    ```



## License
This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for details.


