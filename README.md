## Fast React Pizza — Order Your Favorite Pizza Online 🍕

A fast, minimal pizza ordering web app where users can browse a live menu, build a cart, and place orders with optional priority delivery and GPS-based address detection. Built with React, Redux Toolkit, and React Router v6.

---

<p align="center">
  <a href="https://fast-react-pizza.yoanaborisova.com">
    <img src="https://img.shields.io/badge/Live-fastReactPizza-F28C28?style=for-the-badge&logo=google-chrome&logoColor=white&labelColor=8B3A0E"/>
  </a>
</p>

---

## Features

🍕 Browse a dynamic pizza menu fetched from a remote API  
🛒 Add, remove, and update item quantities in the cart  
💰 Automatic total price calculation  
📍 Auto-detect delivery address via the Geolocation API  
⚡ Mark an order as priority delivery (+20% surcharge)  
🔍 Look up any existing order by ID  
✏️ Upgrade a placed order to priority after submission  

---

## How to Use

1. Enter your name on the home screen
2. Browse the menu and add pizzas to your cart
3. Review your cart and adjust quantities
4. Fill in your delivery details — or use **Get Position** to auto-fill your address
5. Optionally mark the order as priority
6. Place the order and track it by order ID

---

## Tech Stack

| Tool | Purpose |
|------|---------|
| React 18 | UI |
| React Router v6 | Client-side routing, loaders & actions |
| Redux Toolkit | Global state (cart, user) |
| Tailwind CSS | Styling |
| Vite | Build tool |

---

## Project Structure

```
src/
├── features/
│   ├── cart/       # Cart state (Redux slice) and cart UI
│   ├── menu/       # Menu fetching and display
│   ├── order/      # Order creation, display, and update
│   └── user/       # Username and geolocation state
├── services/       # API calls (restaurant, geocoding)
├── ui/             # Shared layout components (Header, Button, etc.)
└── utils/          # Helper functions (currency formatting, etc.)
```

---

## Running Locally

```bash
npm install
npm run dev      # start development server
npm run build    # production build
npm run preview  # preview production build locally
npm run lint     # run ESLint
```

## Credits

Built as part of a React learning project focused on real-world UI patterns, state management, and scalable component architecture.
