# Helping Hands Community Centre Website

## Overview
A comprehensive website for Helping Hands Community Centre, a non-profit organization based in Johannesburg, South Africa, dedicated to combating hunger and homelessness since 2015. The website features information about the organization's services, volunteer opportunities, contact information, and community impact.

## Project Structure
```
helping-hands-website/
│
├── index.html              # Home page
├── about.html             # About Us page
├── services.html          # Services page
├── enquiry.html           # Volunteer registration page
├── contact.html           # Contact Us page
│
├── css/
│   └── style.css         # Main stylesheet
│
├── js/
│   └── script.js         # JavaScript functionality
│
├── images/               # Image assets
│   ├── FoodParcels.jpg
│   ├── clothingdonation.jpg
│   ├── temporaryaccomodation.jpg
│   ├── education.jpg
│   ├── Generational Care.png
│   ├── Johndoe.jpg
│   ├── Janesmith.jpg
│   ├── MikeWilson.jpg
│   └── SarahBrown.jpg
│
└── README.md             # This file
```

## Features

### 1. **Responsive Design**
- Mobile-first approach
- Adaptive layouts for all screen sizes
- Accessible navigation

### 2. **Interactive Elements**
- Lightbox image gallery with keyboard navigation
- Form validation for volunteer applications and contact forms
- Hover effects and transitions
- Active page highlighting in navigation

### 3. **Comprehensive Pages**
- **Home**: Mission, vision, services preview, impact statistics
- **About Us**: History, team, values, mission & vision
- **Services**: Detailed service descriptions with images and statistics
- **Volunteer**: Multi-section application form with various opportunities
- **Contact**: Multiple locations, contact form, interactive map

### 4. **Accessibility Features**
- Semantic HTML structure
- ARIA labels and roles
- Keyboard navigation support
- High contrast ratios for text

## Changelog

### Version 1.0.0 (Current Release)
**Release Date:** December 13, 2024

#### Added
- Complete website structure with 5 main pages
- Responsive CSS framework
- Lightbox image gallery functionality
- Form validation systems
- Interactive navigation
- Team member profiles with images
- Service statistics and impact metrics
- Multiple contact locations with details
- Emergency contact information
- Volunteer application form with multiple sections
- Footer with quick links and contact info

#### Features Implemented:
- Home page hero section with call-to-action buttons
- Mission & vision section with cards
- Services preview grid
- Impact statistics counter
- About page with history timeline
- Team member profiles
- Values section with core principles
- Service details with lightbox image viewing
- Volunteer opportunities listing
- Multi-step volunteer application form
- Contact information cards
- Interactive contact form
- Map section with location markers
- Emergency assistance banner

#### Technical Improvements:
- Optimized image loading
- CSS animations and transitions
- JavaScript form handling
- Lightbox with keyboard shortcuts (arrow keys, Escape)
- Responsive image containers
- Cross-browser compatibility
- Mobile touch-friendly interactions

## Dependencies
- No external libraries required
- Pure HTML, CSS, and JavaScript
- Google Maps embed (optional - iframe)
- Font system uses system fonts for optimal performance

## Browser Support
- Chrome 60+
- Firefox 55+
- Safari 11+
- Edge 79+
- Mobile browsers (iOS Safari, Chrome Mobile)

## Installation & Usage

### Option 1: Local Development
1. Clone or download the project files
2. Open any HTML file in a web browser
3. For development, use a local server (e.g., Live Server in VS Code)

### Option 2: Web Hosting
1. Upload all files to your web hosting server
2. Ensure file structure is maintained
3. Update contact information in HTML files as needed

## Customization

### To Customize Content:
1. **Text Content**: Edit HTML files directly
2. **Images**: Replace images in `/images/` folder
3. **Contact Information**: Update in `contact.html` and footer sections
4. **Team Members**: Update in `about.html`
5. **Services**: Modify in `services.html`

### To Customize Styles:
1. Edit `/css/style.css` for all visual changes
2. Color scheme is defined in CSS variables
3. Typography uses system fonts for performance

## Form Integration

### Current Form Handling:
- Client-side validation
- Form submission placeholders
- For production use, implement backend processing:
  - PHP mailer for contact forms
  - Database integration for volunteer applications
  - Form data sanitization and validation

## Image Specifications
- Recommended size: 800x600px for gallery images
- Format: JPEG or PNG
- Compression: Optimize for web (70-80% quality)
- File naming: Use descriptive names with lowercase

## Performance Notes
- Images are lazy-loaded
- CSS is minified (production-ready)
- JavaScript is non-blocking
- Uses system fonts for faster loading
- No external dependencies

## SEO Features
- Semantic HTML5 structure
- Meta descriptions on each page
- Proper heading hierarchy
- Alt text for all images
- Mobile-responsive design
- Fast loading times

## Future Enhancements Planned
1. Backend form processing
2. Donation payment integration
3. Blog/news section
4. Event calendar
5. Multilingual support
6. Live chat support
7. Newsletter subscription
8. Social media integration
9. Advanced analytics
10. Volunteer portal with login

## Troubleshooting

### Common Issues:
1. **Images not loading**: Check file paths and file names
2. **Forms not submitting**: Backend processing required
3. **Lightbox not working**: Check JavaScript console for errors
4. **Mobile layout issues**: Test with responsive design tools

### Debugging:
- Check browser console for JavaScript errors
- Validate HTML using W3C validator
- Test CSS with different browsers
- Verify image file permissions

## Support
For issues or questions:
1. Check the HTML comments for documentation
2. Review the JavaScript console for errors
3. Validate file paths and naming
4. Ensure all required images are in place

## License
This project is open for modification and distribution. Attribution to the original author is appreciated.

## Acknowledgments
- Design inspired by modern non-profit websites
- Images are placeholder - replace with actual organization photos
- Community-focused content structure
- Accessibility best practices implementation

---

**Note:** This is a static website template. For production use, implement proper backend services for form handling, security measures, and database integration.
