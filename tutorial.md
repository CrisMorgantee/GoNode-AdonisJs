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

`For HTTP requests`

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

`For HTTP requests`

---

> **_Forgot Password_**

- Create new column in table users:(view code!)

  ```
  adonis migration:rollback
  ```

- Create ForgotPasswordController:

```
adonis make:controller ForgotPassword
```

`For HTTP requests`

---

> **_Send email_**

**_Install:_**

```
adonis install @adonisjs/mail
```

After this, are redirect for page with tutorial for config.
Copy this line code and paste in App.js:

```
'@adonisjs/mail/providers/MailProvider'
```

-Views(Templates):
Copy this line code and paste in App.js:

```
'@adonisjs/framework/providers/ViewProvider'
```

Create structure:

`resources/views/emails/forgot_password.edge`

---

> **_Reset Password_**

- To deal with date:

**_Install:_**

```
npm i moment
```

---

> **_Upload Files_**

- Create model, migration and controller:

```
adonis make:model File -m -c
```
