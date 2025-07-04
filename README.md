# Ecommerce platform (fullstack project) Spring boot 3, Angular 18, Tailwind CSS, PostgreSQL, Kinde 
Monorepo of the Ecommerce platform app. 

### Key Features:
- 🛠️ Admin panel for products and categories 
- 🔍✨ Filter engine
- 🌐⚡ Angular SSR 
- 💳 Stripe integration
- 🏢 Hexagonal architecture (Backend)



## Usage
### Prerequisites
- [NodeJS 20.17 LTS](https://nodejs.org/dist/v20.17.0/node-v20.17.0.pkg)
- [Angular CLI v18](https://www.npmjs.com/package/@angular/cli)
- IDE ([VSCode](https://code.visualstudio.com/download), [IntelliJ](https://www.jetbrains.com/idea/download/))
- [JDK 21](https://adoptium.net/temurin/releases/)
- Docker ([Docker Desktop](https://docs.docker.com/engine/install/))

### Fetch dependencies
``npm install``

Create an .env file at the root of the ecom-backend folder with the following values :

````
KINDE_CLIENT_ID=<client-id>
KINDE_CLIENT_SECRET=<client-secret>
STRIPE_API_KEY=<stripe-api-key>
STRIPE_WEBHOOK_SECRET=<stripe-webhook-secret>
````

## Manage the frontend

To run the dev server for your app, use:

```sh
npx nx serve ecom-frontend
```

To create a production bundle:

```sh
npx nx build ecom-frontend
```

To see all available targets to run for a project, run:

```sh
npx nx show project ecom-frontend
```

## Manage the Backend

To run the dev server for your app, use:

```sh
npx nx serve ecom-backend
```

To create a production bundle:

```sh
npx nx build ecom-backend
```

To see all available targets to run for a project, run:

```sh
npx nx show project ecom-backend
```
# springboot-angular-ecommerce
![Image](https://github.com/user-attachments/assets/7e87d637-91dd-4016-87bb-5226cf346c5d) 




## Screenshots
![Image](https://github.com/user-attachments/assets/18b2f0f3-bb99-44bb-ae3b-bf1c2b4aedd1)

![Image](https://github.com/user-attachments/assets/e18eb53c-57a9-49c8-aab7-8235f5828edf)

![Image](https://github.com/user-attachments/assets/5dea7808-fde6-416c-9a9e-69a814a198a8)

