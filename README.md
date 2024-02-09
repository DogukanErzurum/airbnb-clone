# Building a Fullstack Netflix Clone with React, TailwindCSS and Prisma
![3](https://github.com/DogukanErzurum/airbnb-clone/assets/93072322/7b8a50ec-25c9-4792-9288-c0230790ba27)

In this project I made an Airbnb clone using React TailwindCSS next js and Prisma

Project Features:
- Tailwind design
- Tailwind animations and effects
- Full responsiveness
- Credential authentication
- Google authentication
- Github authentication
- Image upload using Cloudinary CDN
- Client form validation and handling using react-hook-form
- Server error handling using react-toast
- Calendars with react-date-range
- Page loading state
- Page empty state
- Booking / Reservation system
- Guest reservation cancellation
- Owner reservation cancellation
- Creation and deletion of properties
- Pricing calculation
- Advanced search algorithm by category, date range, map location, number of guests, rooms and bathrooms
- For example we will filter out properties that have a reservation in your desired date range to travel
- Favorites system
- Shareable URL filters

  ### Necessity

**Node version 14.x**

### Cloning the repository

```shell
https://github.com/DogukanErzurum/airbnb-clone.git
```

### Install packages

```shell
npm i
```

### Setup .env file

This is the section where the person hashes the registration status given by google github and my own system after registration. It is personalized!

```js
DATABASE_URL=
GOOGLE_CLIENT_ID=
GOOGLE_CLIENT_SECRET=
GITHUB_ID=
GITHUB_SECRET=
NEXTAUTH_JWT_SECRET=
NEXTAUTH_SECRET=
```

### Start the app

npm run dev starts the application at localhost:3000.

```shell
npm run dev
```
