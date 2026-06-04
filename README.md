# Pranav Cotton Company Website

A professional website for Pranav Cotton Company with feedback form integration using SendGrid.

## Features

- Modern, responsive design
- High-quality product images
- Feedback form with SendGrid email integration
- Professional UI with Bootstrap and Tailwind CSS

## Setup Instructions



## File Structure

```
├── index.html          # Home page
├── about.html          # About page
├── feedback.html       # Feedback form page
├── netlify/
│   └── functions/
│       └── send-email.js  # Netlify serverless function
├── api/
│   └── send-email.js      # Vercel serverless function
├── package.json        # Dependencies
├── SENDGRID_SETUP.md  # Detailed SendGrid setup guide
└── README.md          # This file
```

## Environment Variables Required

- `SENDGRID_API_KEY` - Your SendGrid API key (required)
- `TO_EMAIL` - Recipient email (defaults to sharmaprakruti1@gmail.com)
- `FROM_EMAIL` - Sender email (defaults to noreply@pranavcotton.com)

## Technologies Used

- HTML5
- Bootstrap 5.3.2
- Tailwind CSS
- Font Awesome
- SendGrid (@sendgrid/mail)
- JavaScript (ES6+)

## Contact

For questions or support, please refer to the setup guide in `SENDGRID_SETUP.md`.
