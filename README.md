# Technical Documentation Page

#### Inspired by freeCodeCamp

#### Completed on <ins>August 11, 2021<ins>

## Objective

Build an app that is functionally similar to https://technical-documentation-page.freecodecamp.rocks. Do not copy this demo project.

## User Stories

1. I can see a `<main>` element with a corresponding id="main-doc", which contains the page's main content (technical documentation).
2. Within the #main-doc ( `<main>` ) element, I can see several `<section>` elements, each with a class of "main-section". There should be a minimum of 5.
3. The first element within each .main-section should be a `<header>` element which contains text that describes the topic of that section.
4. Each `<section>` element with the class of "main-section" should also have an id comprised of the `<header>` innerText contained within it, with underscores in place of spaces. The id may include special characters if there are special characters in the respective `<header>` innerText. (e.g. The `<section>` that contains the header, "JavaScript & Java", should have a corresponding id="JavaScript\_&_Java").
5. The .main-section elements should contain at least 10 `<p>` elements total (not each).
6. The .main-section elements should contain at least 5 `<code>` elements total (not each).
7. The .main-section elements should contain at least 5 `<li>` items total (not each).
8. I can see a `<nav>` element with a corresponding id="navbar".
9. The navbar element should contain one `<header>` element which contains text that describes the topic of the technical documentation.
10. Additionally, the navbar should contain link (`<a>`) elements with the class of "nav-link". There should be one for every element with the class "main-section".
11. The `<header>` element in the navbar must come before any link (`<a>`) elements in the navbar.
12. Each element with the class of "nav-link" should contain text that corresponds to the `<header>` text within each `<section>` (e.g. if you have a "Hello world" section/header, your navbar should have an element which contains the text "Hello world").
13. When I click on a navbar element, the page should navigate to the corresponding section of the "main-doc" element (e.g. If I click on a "nav-link" element that contains the text "Hello world", the page navigates to a `<section>` element that has that id and contains the corresponding `<header>`).
14. On regular sized devices (laptops, desktops), the element with id="navbar" should be shown on the left half of the screen. It should always be visible to the user and should remain stationary. You may need to enlarge the viewport or zoom out to ensure the navbar doesn't scroll with the page content.
15. My Technical Documentation page should use at least one media query.
