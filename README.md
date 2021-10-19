# API Developed on NLW HEAT
---

### Description
Rest API built with NodeJs, Typescript, Prisma, Postgresql and other cool stuffs and stacks. This API uses github OAuth to get user information to post a message. And shows messages on dashboard or something like that.

---
### API Endpoints
| NAME                | METHOD | ENDPOINT        | BODY        | HEADERS                     |
|:-------------------:|:------:|:---------------:|:-----------:|:---------------------------:|
| Authenticate User   | POST   | /authenticate   | code: ""    | -                           |
| Create Message      | POST   | /messages       | message: "" | Authorization: Bearer token |
| Get Last 3 messages | GET    | /messages/last3 | -           | -                           |
| Get User Profile    | GET    | /profile        | -           | Authorization: Bearer       |


### Technologies used in this project:
![Typescript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![NodeJS](https://img.shields.io/badge/Nodejs-43853D?style=for-the-badge&logo=node.js&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-283140?style=for-the-badge&logo=prisma&logoColor=white)
![PostgresSql](https://img.shields.io/badge/Postgresql-313340?style=for-the-badge&logo=postgresql&logoColor=white)
![Socket.Io](https://img.shields.io/badge/socket.io-313340?style=for-the-badge&logo=socket.io&logoColor=white)

### Contributions:

Feel free to open a PR with upgrades to this API :)

### Thanks:

Thanks [Rocketseat](https://www.rocketseat.com.br/) for another amazing Next Level Week. 

\#neverstoplearning