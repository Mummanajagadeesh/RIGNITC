# Website Repository

This repository contains the source code for a multi-page website with sections for **About**, **Achievements**, **Events**, **Projects**, **Team**, and **Contact**. The website includes interactive features, animations, and modular assets.

---

## Directory Structure

```
C:.
├───about
├───achievements
├───assets
│   ├───css
│   │   └── navbar.css
│   └───images
│       ├───about
│       ├───companies
│       ├───gallery
│       └───projects
├───bs               # For testing small features & code snippets
├───contact
├───events
├───projects
└───team
```

* **Each folder contains its own `index.html`**.
* **`bs/`** is for testing small features, experimental code, or transitions.
* **`assets/`** contains CSS and image assets, organized by purpose.

---

## Current Status

* **Main Page:** Done

  * Contains 4 scenes (last 2 need improvement).
  * Needs more company logos and updated social links.
  * Add photos to the gallery.
  * Be careful when editing layout – spline scenes may be affected.

* **About Page:** Done

  * Check `about/clap.html` and `bs/trans.html`.
  * Idea: open About with a clapboard animation zooming in on scroll.

* **Contact Page:** Done

  * Update social/contact links.
  * Form uses Formspree ID.
  * Can directly provide a URL with pre-filled fields in the form

* **Team Page:** Not a priority for now.

* **Achievements, Events, Projects:** Main priorities.

---

## Development Guidelines

### Adding New Companies

* Add images to `assets/images/companies/`.
* Update the main page HTML to reference these images.
* Avoid hardcoding paths multiple times; keep it consistent.

### Projects Management

* Maintain `projects.json` as a modular database of projects.
* Ensure new projects are added consistently.
* Make a dedicated projects page that dynamically reads from `projects.json`.

### UI/UX Guidelines

* Navbar CSS is located in `assets/css/navbar.css`.
* Improve UI where needed; remove anything that feels “cringe.”
* Maintain consistency with colors and layout, especially for spline scenes.
* Hidden watermarks have been masked with background colors—avoid disturbing this.

### Animations

* Consider implementing the **clapboard animation** for the About page.
* Experimental transitions can be tested in `bs/`.

---

## Notes

* All images are in `assets/images/`; refer only to these paths.
* Small experiments, UI prototypes, and feature tests should go in `bs/`.
* Keep the repository modular and maintainable.

---

## Future Work

1. Improve Main Page scenes (especially the last 2).
2. Add more company logos and gallery photos.
3. Implement clapboard animation on About page.
4. Complete Achievements, Events, and Projects pages.
5. Update Contact links and verify forms work with Formspree.
6. Gradually design the Team page when time allows.
7. Keep `projects.json` modular and easy to update.
8. Optimize page loading speed.
9. Make the layout and elements (like navbar and closing buttons) responsive for small devices.
10. Improve meta tags for SEO — add a favicon (forgot to include it earlier).
11. Maintain a black-and-white theme only and improve the overall UI.
12. Ensure accessibility: proper alt text for images, sufficient contrast, and semantic HTML.