TONI&GUY Essensuals Website

A responsive website for TONI&GUY Essensuals in Hyderabad. It brings the Ameenpur and Bachupally branches together so visitors can browse salon services, explore offers and packages, and contact the branch that works for them. The site was built with React and Vite, with clear navigation and an appointment flow that helps customers enquire through WhatsApp.

What the website includes

A combined homepage and individual pages that preselect the Ameenpur or Bachupally branch.

Men's and women's hair, beauty, and grooming services with starting prices.

Service value packages and complete hair and beauty packages.

Appointment buttons that preselect the chosen service or package.

WhatsApp enquiries containing the selected service or package.

Branch contact information and directions.

Responsive layouts, animations, and icons.

Built with

Category

Technology

Languages

HTML, CSS, JavaScript, JSX

Interface

React 19

Build tool

Vite 6

Navigation

React Router

Animation

Framer Motion

Icons

Lucide React

Forms

React Hook Form

Getting started

Install Node.js and npm, then run the following commands from the project folder:

npm install
npm run dev

Open the local URL printed by Vite, usually http://localhost:5173.

To make a production build:

npm run build

Vite writes the deployable site to dist/. To inspect that build locally, run:

npm run preview

Pages

Path

Purpose

/

Combined website for both branches

/ameenpur

Website with Ameenpur preselected

/bachupally

Website with Bachupally preselected

If you deploy the site to static hosting, configure it to serve index.html for direct visits to the branch routes.

Editing website content

The main content is in src/config.js. Update this file to change branch names, phone numbers, WhatsApp contacts, map links, service prices, offers, package details, and booking messages. The page layout is in src/components/SalonLanding.jsx, and the styling is in src/styles.css.

The service value packages currently listed are ₹10,000 with ₹3,000 of free services; ₹15,000 with ₹5,000; ₹20,000 with ₹7,000; ₹30,000 with ₹10,000; and ₹40,000 with ₹12,000. The site also contains complete hair and beauty packages.

Before publishing

Confirm prices, package terms, timings, branch details, and availability with the salons. Replace sample images and reviews with approved branch material where applicable.

Website for TONI&GUY Essensuals, Ameenpur and Bachupally, Hyderabad.
