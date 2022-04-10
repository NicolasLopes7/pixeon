## 2 Weeks MVP

For our MVP we need:

- An Admin system to allow people register, we can use only oauth2 by now (this can be make with React)
  - Twitter
  - Github
  - Google
      - The person should be able to create plans with
        - Title
        - Description
        - Email Template to send the bonuses
      - Register their bank account
- A Checkout system for each registered account (this can be made with Next)
    - Should have two different routes
      - `/:userName`
      - `/:userName/:planId`
