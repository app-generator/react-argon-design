# [React Argon Design](https://appseed.us/product/argon-design-system/api-server-nodejs/react/)

Start your development with a Design System for Bootstrap, `React` and `Reactstrap`. It is open source, free and it features many components that can help you create amazing websites.
The product comes with a simple **JWT** authentication flow: `login/register/logout`. 

- 👉 [React Argon Design](https://appseed.us/product/argon-design-system/api-server-nodejs/react/) - `product page`
- 👉 [React Argon Design](https://react-argon-design.appseed-srv1.com/) - `LIVE Demo`

<br />

> 🚀 Built with **[React App Generator](https://appseed.us/generator/react/)**

- ✅ Innovative **Argon Design System** - Crafted by [Creative-Tim](https://bit.ly/3fKQZaL)
- ✅ React, Redux, Redux-persist
- ✅ Full-stack ready using **[Node JS API Server](https://appseed.us/boilerplate-code/nodejs-starter/)** (open-source project)
  - Features: Typescript / SQLite / TypeORM / Joy (validation) / Passport library - `passport-jwt` strategy.

<br />

![React Argon Design - Open-Source Fullstack starter crafted by Creative-Tim and AppSeed.](https://user-images.githubusercontent.com/51070104/206225228-85e663a2-40e6-4346-bff2-c5c3ebd7dc4b.png)

<br />

## Tests

> `Compatibility matrix` using Ubuntu `18.04 LTS` as reference.

| NodeJS | NPM | YARN | 
| --- | --- | --- |  
| `v14.0.0` | ✅ | ❌ |
| `v15.0.0` | ✅ | ❌ | 
| `v16.15.0` | ✅ | ✅ | 

<br />

## ✨ How to use it

To use the product Node JS (>= 14.x) is required and GIT to clone/download the project from the public repository.

> 👉 **Step #1** - Clone the project

```bash
$ git clone https://github.com/app-generator/react-argon-design.git
$ cd react-argon-design
```

<br >

> 👉 **Step #2** - Install dependencies via NPM or yarn

```bash
$ npm i
// OR
$ yarn
```

<br />

> 👉 **Step 3** - Edit the `.env` using the template `.env.sample`. 

```env

REACT_APP_BACKEND_SERVER='http://localhost:5000/api/'

```

<br />

> 👉 **Step #4** - Start in development mode

```bash
$ npm run start 
// OR
$ yarn start
```

<br />

## ✨ Configure the backend server

The product comes with a usable JWT Authentication flow that provides only the basic requests: login/logout/register. 

> 👉 **API Server URL** - `src/config/constant.js` 

```javascript
const config = {
    ...
    API_SERVER: 'http://localhost:5000/api/'  // <-- The magic line
};
```

<br />

> 👉 **API Server Descriptor** - POSTMAN Collection

The API Server signature is provided by the [Unified API Definition](https://docs.appseed.us/boilerplate-code/api-unified-definition)

- [API POSTMAN Collection](https://github.com/app-generator/api-server-unified/blob/main/api.postman_collection.json) - can be used to mock (simulate) the backend server or code a new one in your preferred framework. 

<br />

## ✨ Node JS API Server

The product is also open-source and is already configured to work with Berry Dashboard Template - product features:

- Typescript / Node js / Express server
- JWT authentication (`passport-jwt` strategy)
- Persistence: SQLite 

> Links

- [Node JS API](https://github.com/app-generator/api-server-nodejs) - source code
- [Node JS API](https://appseed.us/boilerplate-code/nodejs-starter) - product page

<br />

![Node JS API - Open-source API server built on top of Express Nodejs Framework.](https://user-images.githubusercontent.com/51070104/124934824-c210a700-e00d-11eb-9d01-e05bd8bfb608.png)

<br />

### Compile the API Server

> 👉 **Step #1** - Clone the project

```bash
$ git clone https://github.com/app-generator/api-server-nodejs.git
$ cd api-server-nodejs
```

> 👉 **Step #2** - Install dependencies via NPM or Yarn

```bash
$ npm i
// OR
$ yarn
```

> 👉 **Step #3** - Run the SQLite migration via TypeORM

```
$ yarn typeorm migration:run
```

> 👉 **Step #4** - Start the API server (development mode)

```bash
$ npm dev
// OR
$ yarn dev
```

The API server will start using the `PORT` specified in `.env` file (default 5000).

<br /> 

---
[React Argon Design](https://appseed.us/product/argon-design-system/api-server-nodejs/react/) - Provided by **[AppSeed](https://appseed.us/app-generator)**.
