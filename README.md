# Sole Vibe Shoes Storefront

A clean, modern, and fully responsive e-commerce landing page built using semantic HTML5 and styled with Tailwind CSS. This project showcases a curated selection of footwear with product cards tailored for an optimal shopping experience across all device sizes.

## Features

- **Mobile-First Responsive Design:** Adapts fluidly from small mobile screens to ultra-wide desktop monitors using responsive Tailwind breakpoints (sm:, md:, lg:).
- **Sticky Navigation:** A sleek header that stays fixed at the top of the viewport for easy browsing.
- **Card Layout and Proportions:** Product items are structured uniformly inside flexible grid cards using standard aspect ratios to prevent image stretching or warping.
- **Micro-interactions:** Smooth CSS hover transitions (duration-300) applied to cards to elevate user engagement.
- **Semantic Structure:** Implements modern HTML tags (header, nav, main, section) for clean code architecture and optimized accessibility (SEO-friendly).

## Built With

- **HTML5** - For structural semantic architecture.
- **Tailwind CSS (via CDN)** - For modern, utility-first styling.

## Responsiveness Breakdown

The product grid utilizes an adaptive layout system that shifts columns depending on screen size to keep product images perfectly readable:
- **Mobile Screens (< 640px):** 1 Column (Full-width cards for clear mobile visibility).
- **Tablets (≥ 640px):** 2 Columns.
- **Small Desktops (≥ 768px):** 3 Columns.
- **Large Monitors (≥ 1024px):** 4 Columns.

## Project Setup

To run this storefront locally on your system, follow these steps:

1. **Clone or Download the Project:**
   Save your index.html file into a local project directory.

2. **Asset Organization:**
   Ensure you place your shoe images in the same directory as your HTML file (or update the src attribute paths to match your assets folder):
   - j-s.jpg
   - red-shoes.jpg
   - official-shoes.jpg
   - converse.jpg
   - sporty.jpg
   - download.jpg
   - zara-womens.jpg
   - white-shoes.jpg

3. **Run the Application:**
   Open the index.html file directly in any modern web browser (Chrome, Safari, Edge, Firefox), or use a development server extension like Live Server in VS Code for automatic reloading.

## Maintenance and Tailoring

- **Changing Prices:** All currencies are formatted in Kenyan Shillings (Ksh). To update pricing or text descriptions, simply edit the text elements inside the respective product card div.
- **Image Scaling:** The images use object-cover bundled with aspect-square. If your raw images are of different dimension ratios, they will automatically be cropped cleanly from the center rather than squishing out of proportion.