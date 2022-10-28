# API testing with Postman
[![Postman API Tests](https://github.com/enzofurlan/postman-studies/actions/workflows/postman-ci.yml/badge.svg)](https://github.com/enzofurlan/postman-studies/actions/workflows/postman-ci.yml)

Simple repo to save API testing course progress.

## Requirements

-   Postman;
-   API link: https://github.com/vdespa/Postman-Complete-Guide-API-Testing/blob/main/simple-grocery-store-api.md;
-   postman_collection.json in here;
-   Newman

## How to Run with Newman

```
newman run collections/Simple\ Grocery\ Store\ API.postman_collection.json -e environments/Production.postman_environment.json
```
