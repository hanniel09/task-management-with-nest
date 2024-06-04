


# Task Management


The project boils down to a Task Management, where you can register Users and associate them with your definitive tasks.

## API Reference

### Users Methods

#### Sign up

```SHELL
  POST /auth/signup
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `Username, Password` | `JSON` | **Required**. Run the server and create user in sign up.|

#### Sign in

```SHELL
  POST /auth/signin
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `Username, Password`      | `JSON` | **Required**. Username and Password to login with your user. |

### Tasks Methods

#### Get all tasks

```SHELL
  GET /tasks
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `-` | `-` | **Required**. Run the server and has loged with user.|

#### Get unique Task

```SHELL
  GET /tasks/{id}
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `string` | **Required**. Id of task to fetch and has loged with user. |

#### Crate Course

```SHELL
  POST /tasks
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `Title, Description, Status`      | `JSON` | **Required**. Parameters to create a task and has loged with user. |

#### Update Course

```SHELL
  PATCH /tasks/{id}/status
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `ID, Status`      | `String, String` | **Required**. Parameters to alter a Task and ID to update him when already loged.|

#### Delete Course

```SHELL
  DELETE /tasks/{id}
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `ID`      | `String` | **Required**. Id of task to delete and has loged with user.|



## Tech Stack


**Server:** TypeScript, Node, Nest, PostgreSQL, Docker, JWT, TypeORM

## Contact me
hannielvieira1227@gmail.com

[🔗Linkedln](https://www.linkedin.com/in/hanniel-v-aa55a1232/)

