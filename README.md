# GraphQL

-- npm i express graphql express-graphql

-- nom i nodemon

## to Run the Graph QL server

-- npm run devStart

Type this URL in browser to satrt GraphQL server http://localhost:5000/graphql


## input for Testing

query {
  books {
    id
    name
    author {
      id
      name
    }
  }
}

