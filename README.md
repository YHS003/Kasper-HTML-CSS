# Kasper - HTML & CSS Template

A responsive front-end implementation of the **Kasper One Page PSD Template**, built from scratch using HTML5 and CSS3 as part of my front-end development learning journey.

The original visual design was created by **Graphberry**. This project focuses on implementing the design in code while adding my own layout decisions, CSS interactions, animations, and responsive improvements.

## Live Demo

[View Live Demo](https://YHS003.github.io/Kasper-HTML-CSS/)

> The project is deployed using GitHub Pages.

## Screenshots

Screenshots of the implemented project are included below to demonstrate the responsive layout and visual result across different screen sizes.

<table>
  <tr>
    <td align="center" valign="top">
      <strong>Desktop — Full Page</strong><br><br>
      <img src="screenshots/Desktop-Full.png" alt="Kasper Desktop Full Page" width="450">
    </td>
    <td align="center">
      <strong>Mobile — Full Page</strong><br><br>
      <img src="screenshots/Mobile-Full.png" alt="Kasper Mobile Full Page" width="300">
    </td>
  </tr>
  <tr>
    <td align="center">
      <strong>Desktop — Selected Section</strong><br><br>
      <img src="screenshots/Desktop-Section.png" alt="Kasper Desktop Selected Section" width="450">
    </td>
    <td align="center">
      <strong>Mobile — Selected Section</strong><br><br>
      <img src="screenshots/Mobile-Section.png" alt="Kasper Mobile Selected Section" width="300">
    </td>
  </tr>
</table>
## About the Project

This project was developed while studying front-end development through the **Elzero Web School** course.

The goal was not only to reproduce the provided design, but also to practice translating a visual design into a responsive web page using HTML and CSS.

Although the course provided the general implementation direction, several parts of the project were implemented differently or added independently based on my own understanding and experimentation.

## What I Added

In addition to implementing the main design, I introduced several improvements and custom interactions that were not part of the original tutorial implementation.

### Layout & Styling

* Used **CSS Grid** in sections where it provided a cleaner layout solution.
* Replaced some Flexbox-based layouts with Grid where appropriate.
* Used `clip-path: polygon()` to create custom visual shapes.
* Added custom spacing and layout adjustments where needed.
* Fixed and refined visual inconsistencies encountered during implementation.
* Added responsive adjustments for different screen sizes.

### Interactions & Animations

Since JavaScript has not been introduced at this stage of the learning process, CSS was used to give the interface more visual feedback and interaction.

* Added custom hover effects.
* Added CSS transitions to improve visual feedback.
* Added CSS animations.
* Added hover-based interactions to simulate some behaviors that would normally be controlled by JavaScript.
* Added visual movement and state changes to make the page feel less static.

These interactions are intentionally implemented with CSS and are not intended to replace the full functionality that would later be implemented using JavaScript.

## Technologies Used

* HTML5
* CSS3
* CSS Grid
* Flexbox
* CSS Transitions
* CSS Animations
* CSS `clip-path`
* Font Awesome
* Normalize.css

## JavaScript

**JavaScript is not used in this version of the project.**

Some interface behaviors that would normally require JavaScript were represented using CSS hover states, transitions, and animations.

The project is intended to be revisited after learning JavaScript to replace these visual simulations with real interactive functionality.

## Responsive Design

The page was implemented with responsive layouts for different screen sizes, including desktop, tablet, and mobile views.

Media queries were used to adjust:

* Navigation layout
* Section spacing
* Grid structures
* Typography
* Images
* Cards
* Content positioning
* Overall page layout

## Project Structure

```text
Kasper-HTML-CSS/
│
├── index.html
│
├── css/
│   ├── normalize.css
│   ├── all.min.css
│   └── master.css
│
├── assets/
│   ├── about.png
│   ├── awesome-video.mp4
│   ├── design-features.jpg
│   ├── landing.jpg
│   ├── logo.png
│   ├── mobile.png
│   ├── quote.jpg
│   ├── shuffle-01.jpg
│   ├── shuffle-02.jpg
│   ├── shuffle-03.jpg
│   ├── shuffle-04.jpg
│   ├── shuffle-05.jpg
│   ├── shuffle-06.jpg
│   ├── shuffle-07.jpg
│   ├── shuffle-08.jpg
│   ├── skills-01.jpg
│   ├── skills-02.jpg
│   ├── stats.png
│   └── subscribe.jpg
│
├── webfonts/
│   ├── fa-brands-400.woff2
│   ├── fa-regular-400.woff2
│   ├── fa-solid-900.woff2
│   └── fa-v4compatibility.woff2
│
├── screenshots/
│   ├── Desktop-Full.png
│   ├── Desktop-Section.png
│   ├── Mobile-Full.png
│   └── Mobile-Section.png
│
├── .gitignore
└── README.md
```

## Design Credit

The visual design implemented in this project is based on the **Kasper One Page PSD Template** created by **Graphberry**.

Original design:

**Kasper - One Page Creative PSD Template**

https://www.graphberry.com/item/kasper-one-page-psd-template

The original design, branding, and visual assets are not claimed as my own.

This repository contains my own HTML/CSS implementation and modifications made for educational and portfolio purposes.

## Learning Context

This project is part of my ongoing front-end development practice.

While following the Elzero Web School course, I used the provided design as a reference and implemented the page myself.

The project gave me practical experience with:

* Structuring pages with semantic HTML
* CSS layout systems
* Flexbox
* CSS Grid
* Responsive design
* CSS positioning
* Pseudo-elements
* Transitions
* Animations
* Hover states
* `clip-path`
* Working with external assets
* Translating a visual design into a functional webpage

## Credits

### Original Design

**Graphberry**

Kasper One Page PSD Template.

### Learning Resource

**Elzero Web School**

The project was implemented as part of my front-end development learning and practice based on the course material.

### Assets

Some images and supporting assets used during the implementation were obtained from the project resources associated with the learning material.

The ownership and copyright of third-party assets remain with their respective owners.

## Author

**Yehya Hamdy Shehata**

GitHub: [@YHS003](https://github.com/YHS003)

## License

This repository is published primarily as a **portfolio and educational showcase**.

The HTML/CSS implementation written by me is not being released as a general-purpose template or asset pack.

The original Kasper design, third-party images, fonts, icons, and other external assets remain subject to their respective owners' copyrights and licenses.

Please refer to the [`LICENSE`](LICENSE) file for the terms applicable to this repository.
