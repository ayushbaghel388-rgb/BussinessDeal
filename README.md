# BusinessDeal

React + Firebase starter for Manufacturer/Buyer business platform.

## Features
- Role-based login (Manufacturer / Buyer)
- Manufacturer: Add products, see orders, share live location (foreground browser geolocation)
- Buyer: Browse products, add to cart, place orders (no payment)
- Orders saved in Firestore
- Location opens in Google Maps (no API key required)

## Setup
1. Clone project
2. Run `npm install`
3. Add Firebase config in `src/services/firebase.js`
4. Run `npm start`

Firestore Collections:
- users
- products
- orders
- businesses

---

Default business id used in code: `default_business`
(Replace with manufacturer UID later)

