# SWHSFBLADatasciencewebsite
# South Windsor FBLA Data Science Website

## Project Overview
This is a single-page website developed for South Windsor FBLA to promote data science education and resources. The website serves as a hub for FBLA members interested in developing their data science skills and preparing for business leadership in the data-driven era.

## Features
- **Responsive Design**: Fully responsive layout that works on desktop, tablet, and mobile devices
- **FBLA Branding**: Incorporates official FBLA blue and gold color scheme
- **Key Sections**:
  - Hero section with chapter branding
  - Educational content about data science in business
  - Curated resource directory
  - FBLA membership application form

## Technical Specifications
- HTML5
- CSS3 with Custom Properties (CSS Variables)
- No external dependencies
- Semantic HTML structure
- Mobile-first design approach

## Color Scheme
- Primary Color (FBLA Blue): `#003087`
- Secondary Color (Gold): `#FFD700`
- Accent Color (Dark Blue): `#002266`
- Text Color: `#333333`
- Background Light: `#F9F9F9`

## File Structure
```
root/
│
├── index.html          # Main HTML file
└── README.md          # This documentation file
```

## Installation
1. Clone or download the repository
2. No build process required - open `index.html` in a web browser
3. For deployment, upload all files to your web hosting service

## Customization
### Modifying Colors
The website uses CSS variables for easy theme customization. To modify colors, update the values in the `:root` selector:

```css
:root {
    --primary-color: #003087;
    --secondary-color: #FFD700;
    --accent-color: #002266;
    --text-color: #333;
    --light-bg: #F9F9F9;
}
```

### Content Updates
- Hero Section: Update text in the `<section class="hero">` element
- Main Content: Modify text in the `content-section` classes
- Resources: Update links and descriptions in the `resources-grid` section
- Contact Form: Customize form fields in the `contact-section`

## Browser Support
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Opera (latest)

## Maintenance
To maintain the website:
1. Regularly review and update resource links
2. Keep content relevant to current FBLA programs and competitions
3. Update contact information as needed
4. Check for broken links
5. Update copyright year in footer annually

## Contact
For questions or support regarding this website, please contact South Windsor FBLA Chapter.

## License
This website is intended for use by South Windsor FBLA. All rights reserved.

---
Created for South Windsor FBLA Chapter - Future Business Leaders of America
