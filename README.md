# Nestora — Real Estate Website Demo

A premium, responsive React + Vite multi-page real estate platform concept using JavaScript/JSX, React Router DOM, Lucide React and modern CSS. No backend is required for the demo.

## Requirements
- Node.js 18+ (Node.js 20 LTS recommended)
- npm

## Run locally
```bash
npm install
npm run dev
```
Open the local URL printed by Vite, normally http://localhost:5173.

## Production build
```bash
npm run build
npm run preview
```

## Routes
- `/` Homepage and property search
- `/properties` Listings, filters, grid/list and sorting
- `/property/:id` Property details, image gallery, agent and enquiry form
- `/favourites` Saved properties
- `/compare` Compare up to three properties
- `/agents` Agent directory
- `/agent/:id` Agent profile and agent listings
- `/list-property` Property submission form with image preview
- `/contact` Contact form and map placeholder
- `/about` About Nestora
- `/admin` Demo admin overview
- `/admin/properties` Add/edit/delete demo inventory
- `/admin/agents` Demo agent management
- `/admin/enquiries` Sample enquiry list

## Included interactions
- Location, purpose, property type and budget search
- Listing filters for purpose, type, location, min/max price, bedrooms and property area
- Sorting by newest, price ascending/descending and name
- Grid/list view and Load More
- Property detail route and gallery image switching
- Favourites and compare (up to 3) persisted in LocalStorage
- Contact/enquiry and property listing frontend validation
- Local image previews for submitted properties
- Demo admin navigation and local add/edit/delete property UI

## Demo limitations and publishing checklist
All property listings, prices, photos, agents, testimonials, contact details and dashboard figures are illustrative sample content, not verified real listings or people. Contact forms validate in the browser only and do not send data to a server. Property submissions are stored in browser LocalStorage only. The admin UI has no authentication, database, server persistence or real roles. Unsplash images need an internet connection. The map and social links are placeholders. Replace all demo content and connect backend/API, CRM, map and authentication before production use.

## Backend integration
Sample data is isolated in `src/data/properties.js`. Replace local data operations with API services when a backend is ready.
