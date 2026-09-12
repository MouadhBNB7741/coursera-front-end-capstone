# Little Lemon — Front-End Capstone (Meta Front-End Developer)

The capstone project for the Meta Front-End Developer Professional Certificate: a React implementation of the "Little Lemon" restaurant website, focused on the table reservation flow.

## Tech Stack
- React 18 (Create React App), React Router
- Formik + Yup and React Hook Form (form handling/validation across pages)
- react-bootstrap, styled-components, framer-motion
- react-icons

## Features
- Marketing pages: Home (hero + specials), About, Menu, Order Online
- Multi-field table reservation form with validation
- Reusable navigation (desktop nav + mobile nav) and footer
- Login page scaffold

## Project Structure
```
src/
├── components/     # Header, Navigation, HeroSection, Specials, Footer, Reservations UI
└── routes/          # Home, About, Menu, OrderOnline, Reservations, Login
```

## Getting Started
```bash
npm install
npm start      # http://localhost:3000
npm run build
```

## Related
Pairs with [`back-endcapstone`](../back-endcapstone-README.md), a Django REST implementation of the same restaurant, built for the companion Meta Back-End Developer certificate.
