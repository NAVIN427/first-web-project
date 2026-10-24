# FirstProject

A small, framework-free web application with a login page and a welcome page.

## Project structure

```text
FirstProject/
├── assets/
│   ├── css/
│   │   └── styles.css
│   └── js/
│       └── login.js
├── index.html
├── welcome.html
└── README.md
```

- `index.html` and `welcome.html` contain page markup.
- `assets/css/` contains shared styles.
- `assets/js/` contains page behavior.

## Run locally

Open the project folder in a static web server, such as the VS Code Live Server extension, and open `index.html`. You can also open `index.html` directly in a browser.

## Extend the project

Add new pages at the project root and link the shared stylesheet with
`assets/css/styles.css`. Put page-specific behavior in JavaScript files under
`assets/js/` and load them with a script tag using the `defer` attribute.

The current login form is a front-end demo: submitting it redirects to
`welcome.html`, but it does not authenticate credentials. Connect it to a
trusted backend before using it for real accounts.
