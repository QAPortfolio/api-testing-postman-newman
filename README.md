# API Testing with Postman and Newman

## Prerequisites

- Exported JSON collection
- Exported test environment
- Newman installed

```sh
newman --version
```

## Run Tests

```sh
newman run Users.postman_collection.json -e "Test Environment.postman_environment.json"
newman run "Users - Performance.postman_collection.json" -e "Test Environment.postman_environment.json"
```

## Screens

![alt text](img/image.png)

![alt text](img/image-1.png)

![alt text](img/image-2.png)

![alt text](img/image-3.png)