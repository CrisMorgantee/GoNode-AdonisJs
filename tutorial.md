# AdonisJs

### Bootcamp - Rocketseat

> **_Concepts & Structure_**

**_Install:_**

```
sudo npm install -g @adonisjs/cli
```

- Create Project:

```
adonis new gonode --api-only
```

- Up the server:

```
adonis serve --dev
```

---

> **_ESLint configurations[AdonisJS]_**

**_Install:_**

```
npm install -D eslint
```

**_To configure:_**

```
npx eslint --init
```

`use a popular style guide`, _enter_  
`Standard`, _enter_  
`Json`, _enter_

---

> **_Database_**

**_Install:_**

```
npm i --save pg
```

---

> **_Register users_**

- Create UserController:

```
adonis make:controller User
```

`For HTTP requests

List routes of application:

```
adonis route:list
```

---

> **_JWT authentication [AdonisJS]_**

- Create SessionController:

```
adonis make:controller Session
```

`For HTTP requests
