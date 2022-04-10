## 2 Weeks MVP

For our MVP we need:

- [ ] An Admin system to allow people register, we can use only oauth2 by now (this can be make with React)
  - [ ] Twitter
      - [ ] The person should be able to create a plan with:
        - Title
        - Description
        - Email Template to send the bonuses
      - [ ] Register their bank account
- [ ] A Checkout system with the Pix QR Code and an input to the customer put their email:
    - Should have two different routes
      - [ ] `/:userName`
    - [ ] When a order is completed we should send an email with the confirmation and the text written by the supported person. 

- [ ] Basically we need a way to send a payment through pix, and get the response from our payment provider (OpenPix)

