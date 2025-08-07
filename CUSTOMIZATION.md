# Portfolio Configuration Guide

This file contains instructions for customizing your portfolio website.

## Quick Customization Checklist

### 1. Personal Information (index.html)
- [ ] Line 6: Update `<title>Your Name - Portfolio</title>`
- [ ] Line 25: Update navigation logo text
- [ ] Lines 39-42: Update hero title with your name and role
- [ ] Lines 43-46: Update hero description
- [ ] Lines 54-57: Update social media links
- [ ] Lines 61-62: Update profile picture
- [ ] Lines 80-88: Update about section text
- [ ] Lines 101-105: Update project statistics
- [ ] Lines 263-271: Update contact information
- [ ] Line 303: Update footer copyright

### 2. Images to Replace
- Hero section profile picture (400x400px recommended)
- About section image (500x600px recommended)
- Project screenshots (400x300px recommended)

### 3. Projects Section (index.html, lines 155-255)
Update each project with:
- Project title
- Description
- Technologies used (tags)
- Live demo link
- GitHub repository link
- Screenshot/preview image

### 4. Skills Section (index.html, lines 120-150)
Add/remove/modify skills based on your expertise:
- Frontend technologies
- Backend technologies
- Tools and software

### 5. Colors and Theme (style.css, lines 9-20)
Customize the color scheme by updating CSS variables:
```css
--primary-color: #6366f1;    /* Main brand color */
--secondary-color: #8b5cf6;  /* Secondary brand color */
--accent-color: #f59e0b;     /* Accent color */
```

### 6. Contact Information
Update your contact details in:
- Email address
- Phone number
- Location
- Social media profiles

## File Locations for Quick Edits

### HTML Content (index.html)
- **Navigation**: Lines 20-35
- **Hero Section**: Lines 36-85
- **About Section**: Lines 86-115
- **Skills Section**: Lines 116-155
- **Projects Section**: Lines 156-255
- **Contact Section**: Lines 256-295

### Styling (style.css)
- **Color Variables**: Lines 9-20
- **Typography**: Lines 25-35
- **Section Spacing**: Throughout the file
- **Animation Timing**: Lines 900-950

### Functionality (script.js)
- **Form Handling**: Lines 150-200
- **Animation Settings**: Lines 250-300
- **Mobile Menu**: Lines 25-50

## Tips for Customization

1. **Keep It Simple**: Don't overcomplicate the design
2. **Use High-Quality Images**: Ensure all images are crisp and professional
3. **Test Responsiveness**: Check on different screen sizes
4. **Optimize Performance**: Compress images and minimize code
5. **Proofread Content**: Check for typos and grammar errors

## Deployment Checklist

- [ ] All personal information updated
- [ ] Images replaced with your own
- [ ] Projects showcase your best work
- [ ] Contact form works properly
- [ ] Website tested on multiple devices
- [ ] All links are functional
- [ ] SEO meta tags updated

## Common Customizations

### Adding a New Section
1. Add HTML structure in `index.html`
2. Add navigation link
3. Style the section in `style.css`
4. Add animations in `script.js`

### Changing Animation Speed
Modify the `transition` and `animation` properties in `style.css`

### Adding More Projects
Copy the project card structure and update with your project details

### Modifying Contact Form
Update form fields in HTML and validation logic in JavaScript

## Need Help?

If you need assistance with customization:
1. Check the browser developer tools for errors
2. Validate HTML and CSS
3. Test JavaScript functionality
4. Refer to documentation for third-party libraries used
