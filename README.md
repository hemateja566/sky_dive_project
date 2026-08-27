# Sky Dive Project

A single-page website for a skydiving adventure company.

## Overview

Landing page for a skydiving business featuring tandem jumps, training courses, photo/video packages, and booking information.

## Features

- Hero section with call-to-action
- Tandem jump information
- Training programs (AFF, Static Line)
- Photo/video packages
- Safety information
- Testimonials
- Contact/booking form
- Location & weather info
- Responsive design

## Project Structure

```
sky_dive_project/
â”œâ”€â”€ index.html      # Complete single-page site
â””â”€â”€ README.md
```

## Getting Started

```bash
git clone https://github.com/hemateja566/sky_dive_project.git
cd sky_dive_project
open index.html
```

## Sections

1. **Hero** - Background video/image, headline, CTA button
2. **About** - Company story, certifications, safety record
3. **Experiences**
   - Tandem Skydive
   - AFF Course (Accelerated Freefall)
   - Static Line Course
4. **Media Packages** - Photos, video, 360Â° options
5. **Safety** - Equipment, instructors, weather policy
6. **Testimonials** - Customer reviews
7. **FAQ** - Common questions
8. **Contact/Book** - Booking form, location, contact info

## Customization

Edit `index.html` to update:
- Company name, logo, branding
- Prices and packages
- Location details
- Contact information
- Images (replace placeholder URLs)
- Color scheme (CSS variables at top)

## Technologies

- HTML5 semantic elements
- CSS3 (Flexbox, Grid, Custom Properties)
- Vanilla JavaScript (form handling, smooth scroll)
- Font Awesome icons
- Google Fonts

## Deployment

Deploy to any static hosting:
- Netlify (drag & drop)
- Vercel
- GitHub Pages
- Firebase Hosting
- AWS S3 + CloudFront

## Form Integration

Current form uses `mailto:` or Formspree. For production:
- Connect to backend API
- Add reCAPTCHA
- Integrate payment (Stripe)
- Email notifications

## SEO Ready

- Semantic HTML5
- Meta tags (title, description, OG tags)
- Structured data (JSON-LD for LocalBusiness)
- Sitemap.xml (add for production)
- Fast loading (optimized images)

## License

MIT License