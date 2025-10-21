# OIKOS ORCHARD AND FARM

Welcome to the OIKOS ORCHARD AND FARM website project! This project is designed to provide an engaging online presence for the orchard and farm, featuring essential sections for visitors.

## Project Structure

The project is organized as follows:

```
oikos-orchard-website
├── src
│   ├── index.html          # Main entry point for the website
│   ├── pages
│   │   ├── home.html      # Home page showcasing features and introductory content
│   │   ├── contact.html   # Contact Us page with a contact form
│   │   └── reserve.html   # Reserve Slots page with a reservation form
│   ├── components
│   │   ├── header.html     # Header component with navigation
│   │   ├── footer.html     # Footer component with copyright and links
│   │   ├── reserve-form.html # Reservation form component
│   │   └── contact-form.html # Contact form component
│   ├── styles
│   │   ├── main.css        # Main styles for layout and typography
│   │   ├── theme.css       # Theme-specific styles
│   │   └── animations.css   # CSS animations for enhanced user experience
│   └── js
│       ├── main.js         # Main JavaScript functionality
│       └── chat-bubble.js  # JavaScript for Facebook chat bubble integration
├── package.json            # npm configuration file
├── .gitignore              # Files and directories to ignore in version control
└── README.md               # Project documentation
```

## Features

- **Home Page**: An inviting introduction to OIKOS ORCHARD AND FARM, highlighting its features and offerings.
- **Contact Us**: A dedicated page for visitors to reach out with inquiries or feedback.
- **Reserve Slots**: A user-friendly reservation system for booking slots at the orchard.

## Setup Instructions

1. Clone the repository:
   ```
   git clone <repository-url>
   ```
2. Navigate to the project directory:
   ```
   cd oikos-orchard-website
   ```
3. Install dependencies:
   ```
   npm install
   ```
4. Open `src/index.html` in your web browser to view the website.

## Usage Guidelines

- Ensure that all components are properly linked in the `index.html` file.
- Customize styles in `src/styles/main.css` and `src/styles/theme.css` to match the desired aesthetic.
- Use `src/js/chat-bubble.js` to integrate the Facebook Messenger chat bubble for user interaction.

## Contributing

Contributions are welcome! Please submit a pull request or open an issue for any enhancements or bug fixes.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.