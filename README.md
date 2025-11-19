## 🌏 Green Earth
Green Earth is a clean, mobile-first landing page and mini storefront for planting trees. Visitors can browse tree types, add selections to a cart, view campaign information and impact stats, and submit a donation/planting form. The project is static (no backend required) and intended for fast, easy hosting (e.g., GitHub Pages).

## ✨ Features (implemented)

Responsive navigation with a mobile dropdown and a call-to-action button.

## Choose Your Trees area:

Category sidebar and dynamic category container.

Cards grid for tree items populated by JavaScript (script/index.js).

Loading spinner element for async data states.

Cart sidebar showing selected items and total price.

Modal dialog to show tree details.

About Campaign section with image and informational bullets.

Our Impact section with key metrics (trees planted, communities, countries).

Donation form to collect name, email, and number of trees.


 ## 🧰 Technologies

HTML5 — semantic structure and content

Tailwind CSS (browser build) — utility-first styling (@tailwindcss/browser)

daisyUI — UI components built on top of Tailwind

Google Fonts — Inter font

Font Awesome — icons

Vanilla JavaScript — dynamic behavior and DOM manipulation (script/index.js)

Static assets — images and icons in /assets


## 💡 How to Run Locally

Because the project is a static site you have two easy options:

Open directly

Open index.html in your browser (double-click).

Serve with a simple static server (recommended)

If you have Node.js installed:

Install a static server like serve or http-server:

npm install -g serve
# or
npm install -g http-server


Run:

serve .
# or
http-server .


Open the provided http://localhost:PORT URL in your browser.

Deploy

Push the repository to GitHub and enable GitHub Pages from repository settings (or use any static host like Netlify or Vercel).

## 🛠️ How to Customize

-- Change copy / content: edit index.html sections (hero text, About/Campaign copy, impact numbers).

-- Add / change tree items: update data used by script/index.js (where cards are rendered). If your data is in an array or fetched JSON, edit that source.

-- Styling: modify styles/style.css or add Tailwind utility classes in the HTML.

-- Assets: replace images in /assets and update their filenames/paths in index.html.

-- Form handling / donations: the current form is static — integrate with a backend or third-party payment provider (Stripe/PayPal) to process donations.


## LIVE LINK :
https://github.com/nosib55/green-earth
