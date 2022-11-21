# Wingspan
Serving data from my recent favorite game Wingspan

## Project Structure Visual
I am working on it ....

## Skills
Through this project I am practicing the following concept

- Basic Controller, Services, Model Folder Structure 
- Test Driven Design
- Basic GraphQL ([Hot chocolate](https://chillicream.com/docs/hotchocolate/v13/get-started) from ChilliCream)
- Basic GraphQL Testing
- Basic Dependencies Injection 
- DBContext
- gRPC


## Project Related
### GraphQL

Run the following schema as example
```
{
  birds(first: 3) {
    edges{
      node {
        common_name
        ability_description
        egg_capacity
      }
    }
  }
} 
```
