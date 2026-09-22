# TONI&GUY React + Vite Website

## Run
```bash
npm install
npm run dev
```

Open the Vite URL, normally `http://localhost:5173`.

## Routes
- `/` combined website
- `/ameenpur` Ameenpur preselected
- `/bachupally` Bachupally preselected

## Main content file
Use `src/config.js` to manage:
- branch contacts and maps
- salon services
- regular offers
- service-value packages
- complete hair & beauty packages
- WhatsApp booking text

## Package section
The website now includes a dedicated `#packages` section with:

### Service Value Packages
- ₹10,000 + ₹3,000 service free
- ₹15,000 + ₹5,000 service free
- ₹20,000 + ₹7,000 service free
- ₹30,000 + ₹10,000 service free
- ₹40,000 + ₹12,000 service free

### Complete Hair & Beauty Packages
- ₹3,599
- ₹4,999
- ₹5,999
- ₹7,999
- ₹8,999

Each package has a booking button that opens the existing appointment modal and preselects the exact package. The selected service/package is also included in the WhatsApp enquiry message.

Before production, replace demo Unsplash images/reviews with authentic branch assets and confirm package terms and availability for each branch.
