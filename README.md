# Product Management Portfolio Website

A modern, responsive single-page portfolio website designed specifically for Product Managers. This portfolio showcases your skills, case studies, and professional information in an engaging and interactive way.

## Features

- Responsive design that works on all devices
- Smooth scrolling navigation
- Animated sections and skill bars
- Mobile-friendly navigation menu
- Contact form
- Social media integration
- Back to top button
- Modern and clean UI with subtle animations

## Getting Started

1. Clone this repository to your local machine
2. Open `index.html` in your web browser
3. Customize the content to match your personal information

## Customization

### Personal Information
1. Open `index.html`
2. Update the following sections with your information:
   - Name and title in the hero section
   - About me text in the introduction section
   - Profile image (replace the placeholder image)
   - Skills and their proficiency levels
   - Case studies with your own projects
   - Social media links
   - Contact information

### Styling
1. Open `styles.css`
2. Customize the color scheme by updating the CSS variables in the `:root` selector:
   ```css
   :root {
       --primary-color: #2563eb;
       --secondary-color: #1e40af;
       --text-color: #1f2937;
       --light-text: #6b7280;
       --background: #ffffff;
       --section-bg: #f3f4f6;
   }
   ```

### Case Studies
1. Replace the placeholder images in the case studies section with your own project screenshots
2. Update the project titles and descriptions
3. Add links to your case study PDFs or detailed project pages

### Contact Form
The contact form is currently set up to log form submissions to the console. To make it functional:
1. Set up a backend server to handle form submissions
2. Update the form submission handler in `script.js` to send data to your server

## Technologies Used

- HTML5
- CSS3 (with CSS Grid and Flexbox)
- JavaScript (ES6+)
- Font Awesome Icons
- Google Fonts (Inter)

## Browser Support

The website is compatible with all modern browsers:
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Performance Optimization

The website is optimized for performance with:
- Lazy loading of images
- Smooth scrolling
- Efficient CSS animations
- Mobile-first responsive design

## Contributing

Feel free to fork this repository and submit pull requests for any improvements.

## License

This project is open source and available under the MIT License. 