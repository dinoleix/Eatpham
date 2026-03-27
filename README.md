Eatpham — Official Website
Website for The Categorical Eat-Pham, Delhi's celebrated Manipuri restaurant located in Safdarjung Enclave. Built as a single-file HTML/CSS/JS site, ready to deploy to eatpham.com.
About
Eatpham brings the authentic flavours of Manipur — from Eromba and Kangshoi to traditional thalis — to the heart of Delhi. The site tells that story through elegant typography, real photography from Google Maps, and a full menu showcase.
Address: 168 Humayunpur, Safdarjung Enclave, New Delhi
Phone: +91 11 4181 2089
Instagram: @thecategoricaleatpham
Google Rating: 4.3★ (1,380+ reviews)
Features

Fully responsive single-page design (index.html)
Real photography sourced from Google Maps
Interactive tabbed menu (Mains, Sides, Drinks, Specials)
Photo gallery with lightbox — keyboard and click navigation
Smooth scroll-reveal animations throughout
Click-to-call reservation button
Embedded Google Maps location card

Structure
Eatpham/
└── index.html      # Entire site — HTML, CSS, and JS in one file
Deployment
Drop index.html onto any static host — Netlify, Vercel, GitHub Pages, or a traditional server. No build step, no dependencies.
GitHub Pages (quickest option):

Push this repo to GitHub
Go to Settings → Pages → set source to main branch / root
Done — live at https://<username>.github.io/<repo>/

Custom domain (eatpham.com):
Add a CNAME file containing eatpham.com to the repo root, then point the domain's DNS to GitHub Pages.
Tech
Pure HTML5, CSS3, and vanilla JavaScript. No frameworks, no build tools, no dependencies beyond Google Fonts.
