# NEXA Login UI

A polished and responsive login interface created with HTML, CSS, and vanilla JavaScript.

The design uses a premium dark copper theme, subtle animations, custom form controls, and a dedicated password visibility toggle.

## Preview

The interface includes:

- Responsive login card
- Dark copper visual theme
- Custom NEXA branding
- Username and password fields
- Custom show-and-hide password button
- Browser-native password reveal suppression
- Remember-me checkbox
- Basic client-side form validation
- Reduced-motion accessibility support
- Mobile-responsive layout

## Technologies

- HTML5
- CSS3
- Vanilla JavaScript

No frameworks, build tools, packages, or external dependencies are required.

## Project Structure

```text
nexa-login-ui/
├── index.html
├── style.css
└── README.md
```

## Running Locally

Clone the repository:

```bash
git clone https://github.com/YOUR-USERNAME/nexa-login-ui.git
```

Open the project folder:

```bash
cd nexa-login-ui
```

Then open `index.html` in a web browser.

You can also run it through a local development server.

Using Python:

```bash
python -m http.server 5500
```

Visit:

```text
http://localhost:5500
```

## GitHub Pages

This project can be hosted directly with GitHub Pages.

1. Open the repository on GitHub.
2. Select **Settings**.
3. Select **Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch.
6. Select the `/root` folder.
7. Save the settings.

The website will become available at:

```text
https://YOUR-USERNAME.github.io/nexa-login-ui/
```

## Authentication

This repository currently contains the frontend login interface only.

The form does not authenticate users against a real server. Replace the placeholder login submission code in `index.html` with a request to your authentication API.

Do not place passwords, API keys, private tokens, database credentials, or other secrets directly in the HTML or JavaScript.

## Accessibility

The interface includes:

- Semantic form elements
- Accessible labels
- Keyboard-focus indicators
- Password-toggle state attributes
- Reduced-motion support
- Responsive mobile behavior

## Browser Support

The interface is designed for current versions of:

- Google Chrome
- Microsoft Edge
- Mozilla Firefox
- Safari

Browser-native password reveal controls are suppressed where supported so that only the custom password visibility button is displayed.
