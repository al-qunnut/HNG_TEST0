# Personal Portfolio Website

This project is a multi-page personal portfolio website built with HTML, CSS, and vanilla JavaScript. It features a profile card, contact form with validation, and an about page with personal reflections.

## Pages

### 1. Profile Card (index.html)
- Displays personal information in a card layout
- Features:
  - User name with `test-user-name`
  - Biography with `test-user-bio`
  - Live-updating timestamp with `test-user-time`
  - Profile avatar with `test-user-avatar`
  - Social links list with `test-user-social-links`
  - Hobbies section with `test-user-hobbies`
  - Dislikes section with `test-user-dislikes`

### 2. Contact Page (Contact.html)
- Interactive contact form with validation
- Features:
  - Required fields:
    - Full name (`test-contact-name`)
    - Email (`test-contact-email`)
    - Subject (`test-contact-subject`)
    - Message (`test-contact-message`)
  - Form validation:
    - All fields required
    - Email format validation
    - Message minimum length: 10 characters
  - Error messages (`test-contact-error-<field>`)
  - Success message (`test-contact-success`)
  - Submit button (`test-contact-submit`)

### 3. About Page (About.html)
- Personal reflection and goals
- Sections:
  - Bio (`test-about-bio`)
  - Goals in the program (`test-about-goals`)
  - Areas of low confidence (`test-about-confidence`)
  - Note to future self (`test-about-future-note`)
  - Extra thoughts (`test-about-extra`)

## Technical Features

### Accessibility
- ARIA labels and descriptions
- Proper heading hierarchy
- Keyboard navigation support
- Form input labels and error associations
- Alt text for images
- Semantic HTML structure

### Responsive Design
- Mobile-first approach
- Flexible layouts
- Responsive typography
- Touch-friendly interactions
- Adaptive navigation

### Form Validation
- Real-time validation
- Clear error messages
- Accessible error notifications
- Success confirmation
- Email format checking
- Minimum length requirements

### Performance
- Vanilla JavaScript
- No external dependencies
- Optimized assets
- Minimal CSS

## How to Run

1. Clone the repository
2. Open any of the HTML files in a modern web browser:
   - `index.html` for the profile card
   - `Contact.html` for the contact form
   - `About.html` for the about page

No build step or server required. The project runs directly in any modern browser.

## Testing

Each interactive element has a `data-testid` attribute for automated testing:
- Profile elements: `test-user-*`
- Contact form: `test-contact-*`
- About sections: `test-about-*`

## Browser Support

Tested and working in:
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

