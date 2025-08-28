# Niyantri — Professional & Clean Online Store

This repository contains a small multi-page website for "Niyantri", a professional and clean online store. The site is built with plain HTML, Tailwind CSS (via CDN), and vanilla JavaScript.

Files
- index.html — Landing / shop page with hero, product grid, colourful quotations, and a simple cart sidebar. Includes search and add-to-cart functionality (demo).
- about.html — About page with company story, founders (GSR and CVSR), and large colourful quotations.
- contact.html — Contact page with contact details and a submission form with basic validation.
- README.md — This file.

Design & Behavior
- Styling uses Tailwind CSS utility classes directly in the HTML.
- Google Fonts are referenced at the top of each HTML file via comments in the format required by the generator. The fonts used are Poppins (headings) and Inter (body).
- All main content wrappers are full-width (w-full / max-w-none) to ensure the site fills the viewport width on all devices.
- Product images and other imagery use placeholders in the format:
  <img src="https://pixabay.com/get/gb98f4c67014d8418723cb5b9f641bb09abbcd2a8ac71cd79e76ddbd710502efeac045f8f6e812d6dcde35bebd1fed9cba82bac604e560c05ba0c02046da775a0_640.jpg" />
  The system that uses this project will attempt to fetch appropriate images from image sources.
- The site includes colourful quotation blocks with gradients and subtle hover animations.
- Interactive elements include:
  - Search filter for products
  - Add to cart, quantity adjust, and a cart sidebar
  - Contact form with validation
  - Sign-up CTA on the About page

How to use
- Open index.html in a modern browser to view the home/shop page.
- Navigate to About and Contact pages using the header links.
- The project is static, so no build step is required.

Customization
- You can replace the https://images.unsplash.com/photo-1683193063549-b8a50825cbc0?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w3ODkyNDZ8MHwxfHNlYXJjaHw1fHwuLi58ZW58MHwwfHx8MTc1NjI4MTYwOHww&ixlib=rb-4.1.0&q=80&w=1080 placeholders with real image URLs or keep the placeholder format if your environment supports automatic image fetching.
- Update product data in index.html inside the products array to add/remove items or change prices and descriptions.
- Tailwind is loaded via CDN; for production you may wish to integrate a build step and purge unused styles.

Founders
- The site mentions the founders: GSR and CVSR in multiple locations as requested.

License
- This template is provided as-is for demonstration and quick prototyping.

Enjoy building your clean, professional store with Niyantri!