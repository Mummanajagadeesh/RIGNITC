# Website Repository

This repository contains the source code for a multi-page website with sections for **About**, **Achievements**, **Activities**, **Projects**, **Team**, and **Contact**. The website includes interactive features, animations, and modular assets.

---

## Directory Structure

```
C:.
├───about
├───achievements
├───activities
├───assets
│   ├───css
│   └───images
│       ├───about
│       ├───achievements
│       │   └───competitions
│       ├───activities
│       ├───companies
│       ├───gallery
│       ├───main
│       ├───projects
│       ├───startups
│       └───team
│           ├───b19
│           ├───b21
│           ├───b22
│           ├───b23
│           ├───b24
│           └───dev
├───bs # use this for testing
├───contact
├───projects
└───team
```

* **Each folder contains its own `index.html`**.
* **`bs/`** is for testing small features, experimental code, or transitions.
* **`assets/`** contains CSS and image assets, organized by purpose.

---

## Current Status

* **Main Page:** Done

  * Needs more company logos and updated social links.
  * Add photos to the gallery.
  * Be careful when editing layout – spline scenes may be affected.

* **Contact Page:** Done

  * Update social/contact links.
  * Form uses Formspree ID.
  * Can directly provide a URL with pre-filled fields in the form

* **Activities** Main priority now

---

## Development Guidelines

### Adding New Companies

* Add images to `assets/images/companies/`.
* Update the main page HTML to reference these images.
* Avoid hardcoding paths multiple times; keep it consistent.

### Projects Management

* Maintain `.json` files neatly.
* Ensure new projs are added consistently.

### UI/UX Guidelines

* Navbar CSS is located in `assets/css/navbar.css`.
* Improve UI where needed; remove anything that feels “Cringe”.
* Maintain consistency with colors and layout, especially for spline scenes.
* Hidden watermarks have been masked with background colors—avoid disturbing this.

---

## Notes

* All images are in `assets/images/`; refer only to these paths.
* Small experiments, UI prototypes, and feature tests should go in `bs/`.
* Keep the repository modular and maintainable.

---

## Future Work

* Improve the main page.
* Add more company logos and gallery photos.
* Complete the Activities page.
* Keep all `.json` files modular and easy to update.
* Optimize page loading speed.
* **Enhance mobile optimization:** make the layout and elements (like navbar and closing buttons) fully responsive on all devices.
* Improve meta tags for SEO.
* Maintain a black-and-white theme only and improve the overall UI.
* Ensure accessibility: provide proper alt text for images, maintain sufficient contrast, and use semantic HTML.
