# RoshiTech Backend

Website for the company RoshiTech, Inc.

## Links

#### Client Site: <https://kkorrapaty.github.io/roshiTechSite/#/>

#### Front End Repo: <https://github.com/kkorrapaty/roshiTechSite/>

## Planning

The process began by looking at the original site, and understanding the essential aspects to incorporate. Then I added my own design ideas into effect by utilizing `React` and `Bootstrap`. The backend was then created to allow for successful `sign-up` and `sign-in` actions.

## Technologies Used

-   Express.js
-   Axios
-   MongoDb
-   Mongoose

## User Stories

-   As an unregistered user, I would like to see all of the services provided.
-   As an unregistered user, I would like to see what the company is about.
-   As an unregistered user, I would like to see all of the products.
-   As an unregistered user, I would like to sign up with email and password.
-   As a registered user, I would like to sign in with email and password.
-   As a signed in user, I would like to change password.
-   As a signed in user, I would like to sign out.

## API End Points
| Verb   | URI Pattern               | Controller#Action |
|--------|---------------------------|-------------------|
| POST   | `/sign-up`                | `users#signup`    |
| POST   | `/sign-in`                | `users#signin`    |
| DELETE | `/sign-out`               | `users#signout`   |
| PATCH  | `/change-password`        | `users#changepw`  |

## Future Updates

I would like to add the functionality for users to search the site and go to the respective route. Also, when signed in, the registered users should see auhtorized links and specific services that are relevant to them.
