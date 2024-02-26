### Overview

My first NestJS project. Simple app to create/get message from a file. Its main pourpus was to learn basic of this freamwork.

### Usage

Copy the repository, go to root directory and install all dependencies:

```npm
npm install
```

next start server locally:

```npm
npm run start:dev
```

- to create a message make POST request on `localhost//:3000/messages` with body:

```json
{
  "content": "content of message"
}
```

- to read all messages make a GET request on `localhost//:3000/messages`
- to read a single message make a GET request on `localhost//:3000/messages/:id`
