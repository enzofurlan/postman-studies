# API testing with Postman
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