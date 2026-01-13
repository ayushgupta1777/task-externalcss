# Netflix Sign Up Form

A responsive, modern Netflix-inspired sign-up form built with HTML, CSS, and semantic markup.

## Overview

This project implements a clean and user-friendly registration interface featuring Netflix's iconic styling, including the signature red accent color and dark theme. The form includes validation fields and a professional layout suitable for production use.

## Features

- **Responsive Design**: Fully responsive layout that adapts to different screen sizes
- **External CSS**: Organized stylesheet with modular class naming conventions
- **Netflix Branding**: Authentic Netflix logo SVG and brand colors (#E50914 red)
- **Form Fields**: 
  - First Name input
  - Last Name input
  - Email address input
  - Password input
  - Confirm Password input
  - Terms & Conditions checkbox
- **User Experience Elements**:
  - Sign-up call-to-action button
  - "Already have account?" link for existing users
  - Contact Support link for assistance
  - reCAPTCHA notice for security assurance
- **Dark Theme**: Professional dark background with gradient overlay
- **Accessibility**: Proper semantic HTML structure with meaningful labels

## Project Structure

```
task-externalcss/
├── index.html                 # Main HTML file with form structure
├── README.md                  # This file
├── assets/
│   ├── css/
│   │   └── styles.css        # All styling rules
│   ├── fonts/                # Font files directory
│   ├── images/               # Image assets directory
│   └── js/                   # JavaScript files directory
└── vendor/
    ├── bootstrap/            # Bootstrap framework files
    ├── jquery/               # jQuery library files
    └── ...                   # Other dependencies
```

## Technical Details

### HTML Structure
- Semantic HTML5 markup
- Proper form input types (text, email, password)
- SVG logo implementation
- Accessibility-friendly class naming

### CSS Classes (All Lowercase)
- `.background` - Main container with gradient
- `.header` - Logo section
- `.signup_box` - Form wrapper
- `.signup_form` - Form container
- `.terms_condition` - Checkbox agreement section
- `.sign_up_button` - Primary CTA button
- `.already_have_account` - Sign-in link section
- `.contact_info` - Support link section
- `.recaptcha` - Security notice section

### Styling Features
- **Colors**: Dark theme (#221F1F, #333, #737373) with Netflix red (#E50914)
- **Dimensions**: Optimized form width (380px) for clarity
- **Spacing**: Consistent padding and margins (14px, 20px, 25px, 60px)
- **Interactions**: Hover-enabled cursor pointers on clickable elements
- **Fonts**: Arial, Helvetica, sans-serif for consistency

## File Details

### index.html
- **Size**: 140 lines
- **Content**: Complete form with Netflix branding
- **Charset**: UTF-8
- **Meta**: Responsive viewport configuration

### styles.css
- **Size**: 121 lines
- **Organization**: Top-down styling from layout to components
- **Specificity**: Component-based selectors
- **Properties**: Flexbox layouts, border-radius, rgba colors

## Usage

1. Open `index.html` in your web browser
2. Fill in the form fields with your information
3. Check the "I agree to the Netflix Terms of Use and Privacy Policy" checkbox
4. Click "Create Account" to submit

## Browser Compatibility

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Customization

### Changing Colors
Edit `assets/css/styles.css`:
- Netflix Red: `#e50914` → your preferred color
- Dark backgrounds: `#221F1F`, `#333` → your colors

### Modifying Form Fields
Edit `index.html` to add/remove input fields in the `.signup_form` section

### Updating Logo
Replace the SVG content in the `.header` section with your own logo

## Version History

- **v1.0.1** - Latest release
  - All class names converted to lowercase
  - Optimized CSS structure
  - Improved semantic HTML

## Notes

- All CSS classes follow lowercase naming convention (no camelCase or PascalCase)
- Form does not include backend validation; implement server-side validation for production
- reCAPTCHA integration requires additional setup with Google API
- External CSS approach allows for easy theme switching and maintenance

## Future Enhancements

- [ ] Form validation with JavaScript
- [ ] Backend integration for account creation
- [ ] Email verification workflow
- [ ] Password strength indicator
- [ ] Two-factor authentication option
- [ ] Social login integration
- [ ] Dark/Light theme toggle

## License

Created as a learning project for web development best practices.

## Author

Development Team | Version 1.0.1 | 2026
