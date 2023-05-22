# Student_Rest_API_Newman

## How to run this project
- Clone this project
- Open with Postman / Command Shell
- Run Command:  
```console 
newman run StudentDetails.postman_collection.json -e StudentDetails.postman_environment.json 
```
- Run Command for Report: 
```console 
newman run StudentDetails.postman_collection.json -e StudentDetails.postman_environment.json -r cli,htmlextra
```

## Technology used:
- Postman
- Newman

## Prerequisite:
- Jdk
- Node Js
- Newman
- Html Report Library

## Newman and Report Installation Process:
- Newman Install Command:
```console
npm install -g newman-reporter-htmlextra
```
- Newman Html Report Install Command:
```console
npm install -g newman-reporter-htmlextra
```

## API Documentation:
- https://documenter.getpostman.com/view/13082503/2s93Xwz4Az

## Newman Report Summary:

![newmanrun](https://github.com/Mahir-Afsar/Student_Rest_API_Postman_Newman/assets/123372012/f37175dd-7ea0-4143-b2f3-b024a5f3ca41)

![newman2](https://github.com/Mahir-Afsar/Student_Rest_API_Postman_Newman/assets/123372012/d03d8073-d73b-408e-886a-423a1a2922c1)
