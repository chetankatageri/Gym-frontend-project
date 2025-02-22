# Naveen Fitness Website

A responsive website for Naveen Fitness gym, featuring a modern design with a dark theme and user registration functionality.

## Overview

This website serves as a landing page for Naveen Fitness gym, located in Hubli. It includes a navigation bar, contact buttons, and a registration form for new members.

## Features

- Responsive navigation bar
- Dark theme with white text for high contrast
- Background image with proper scaling
- User registration form
- Contact buttons for quick access
- Mobile-responsive design

## File Structure

```
naveen-fitness/
├── index.html
├── gym.css
└── img/
    ├── gym-1048852_1920.png
    └── man-7847247_1920.jpg
```

## Technical Details

### HTML Structure

- **Header Section**
  - Left section: Logo and gym name
  - Middle section: Navigation menu
  - Right section: Contact buttons

- **Main Content**
  - Registration form with fields for:
    - Name
    - Age
    - Gender
    - Locality
    - Phone Number
    - Email ID

### CSS Features

- Fixed background image with cover property
- Inverted logo color for better visibility
- Semi-transparent form container with blur effect
- Responsive design breakpoints
- Interactive hover effects
- Custom button styling

## Setup Instructions

1. Clone or download the project files
2. Ensure all files are in the correct directory structure
3. Make sure the image files are present in the `img` folder:
   - `gym-1048852_1920.png` (logo)
   - `man-7847247_1920.jpg` (background)
4. Open `index.html` in a web browser

## Browser Compatibility

The website is compatible with:
- Google Chrome (latest)
- Mozilla Firefox (latest)
- Microsoft Edge (latest)
- Safari (latest)

## Responsive Design

The website is responsive and adapts to different screen sizes:
- Desktop (1024px and above)
- Tablet (768px to 1023px)
- Mobile (below 768px)

## Form Handling

The form is configured to submit to `noaction.php`. To make the form functional:
1. Create a PHP file named `noaction.php`
2. Implement form handling logic
3. Add database connectivity if required
4. Set up email notifications if needed

## Customization

### Changing the Background Image
1. Place your new image in the `img` folder
2. Update the background-image path in `gym.css`:
```css
body {
    background-image: url(./img/your-new-image.jpg);
}
```

### Modifying Colors
Key color variables in use:
- Text: white (#FFFFFF)
- Buttons: black background with white text
- Form border: white
- Hover effects: grey

### Logo Customization
1. Replace `gym-1048852_1920.png` with your logo
2. Adjust the size in CSS if needed:
```css
.left img {
    width: 100px;
    height: 70px;
}
```

## Future Enhancements

Potential features to add:
1. Interactive fitness calculator
2. Member login system
3. Class schedule display
4. Trainer profiles
5. Membership plan details
6. Image gallery
7. Testimonials section
8. Blog section for fitness tips

## Contact

For any queries regarding the website, contact Naveen Fitness:
- Via the "Call Us Now" button
- Via the "Email Us" button
- Through the registration form


---

Remember to replace placeholders and add specific details about licensing, credits, and contact information as needed.# Gym-frontend-project
