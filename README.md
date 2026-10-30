# Stripe Design Clone

A front-end recreation of the Stripe website, built with HTML and CSS.

This project is part of my learning and portfolio work. I chose Stripe
as a reference because its website brings together many of the things I
wanted to understand better: clear page structure, typography, spacing,
imagery, navigation, and the way a long page guides someone from one
section to the next.

The goal was not to build a payment product or reproduce Stripe's
backend. It was to study a real website and practise turning a visual
reference into a working page using the fundamentals of front-end
development.

## Why I built it

When learning front-end development, it is easy to focus on individual
HTML elements or CSS properties without seeing how they work together in
a complete interface.

I wanted to take on a project that would make me think about the page as
a whole. Stripe was a useful reference because its homepage contains
several different kinds of content: a navigation bar, a hero area,
product and solution cards, statistics, customer stories, informational
sections, and a detailed footer.

Recreating that structure gave me a practical way to learn how a website
is organised and how each part contributes to the overall experience.

## What I built

The project recreates the visual structure of a Stripe-style homepage.
It includes:

-   A header with navigation links and dropdown menus.
-   A hero section with headline content and supporting visuals.
-   Customer and partner logo areas.
-   Product and solution cards.
-   A statistics section.
-   Enterprise information and customer stories.
-   Startup and platform-related content sections.
-   News and press areas.
-   A multi-column footer.

The page is made from HTML elements styled with CSS. Images and visual
assets are stored in the project, with some image resources loaded from
external URLs. Font Awesome is included through its CDN for icons.

This is a visual front-end exercise. It does not implement Stripe's
payment services, account systems, or other backend functionality, and
it is not an official Stripe product.

## How I approached the work

I treated the reference website as something to study, not just
something to copy.

### 1. Understanding the page

Before focusing on individual styles, I looked at how the original page
was divided into sections. I paid attention to the order of the content,
the relationship between headings and descriptions, and how different
types of information were grouped.

### 2. Building the structure with HTML

I used HTML to create the main page sections and their content. This
helped me understand how a large page can be organised into smaller,
understandable parts instead of being treated as one long block of
markup.

### 3. Recreating the visual layout with CSS

I then used CSS to work on the appearance of those sections. This
involved learning through practice how layout, spacing, sizing,
alignment, backgrounds, typography, and images affect the final result.

### 4. Working through the details

A page can contain the right content and still feel very different from
its reference. Small decisions matter: the size and position of a
heading, the space between sections, the proportions of an image, or the
alignment of elements inside a card.

Working through these details helped me see how many individual choices
contribute to a consistent interface.

## What I learned

The most useful part of this project was learning how the pieces of a
website fit together.

Some of the things I practised and understood better were:

-   **Page structure:** organising a long page into clear sections and
    keeping the HTML understandable.
-   **Typography:** using headings, text sizes, and line spacing to
    establish a clear reading order.
-   **Layout:** positioning and aligning content, and understanding how
    containers and spacing shape a page.
-   **Images and visual assets:** choosing where images belong and how
    their size and placement affect a section.
-   **Consistency:** reusing styling ideas so that different parts of
    the page feel like they belong to the same website.
-   **Attention to detail:** recognising that the quality of an
    interface often comes from many small decisions rather than one
    large effect.

Most importantly, I got more practice connecting what I write in HTML
and CSS with what I see in the browser.

## Learning without AI

I completed this project without using AI to generate the code. I wanted
to work through the layout and styling myself, make mistakes, understand
why something was not appearing as expected, and learn how to correct
it.

That choice was intentional. At this stage, building a strong
understanding of HTML and CSS mattered more to me than finishing the
page as quickly as possible. Writing and adjusting the code myself gave
me direct experience with the decisions involved in building a user
interface.

## Project structure

``` text
Stripe-Design-Clone/
├── index.html
├── style.css
├── esset/
├── backup/
└── wave-fallback-desktop.png
```

The `index.html` file contains the page structure, while `style.css`
contains the visual styling. The asset folders and image file provide
visual resources used by the page.

## Run it locally

No build tools or package installation are required.

1.  Clone the repository:

    ``` bash
    git clone https://github.com/bilal-extroverted/Stripe-Design-Clone.git
    ```

2.  Open the project folder.

3.  Open `index.html` in your browser.

For the page's local images to load correctly, keep the asset folders in
their existing locations relative to `index.html`.

## Conclusion

This project was a step in learning how to build interfaces from the
ground up. It helped me move beyond learning HTML tags and CSS
properties separately and start thinking about how structure, layout,
typography, and imagery work together in a complete website.

It is a learning project, and I see it as part of the foundation I am
building as a developer. The main value for me was the hands-on
experience: studying an existing interface, making my own
implementation, and understanding the choices behind what appears on the
screen.

There is still more to learn, but this project gave me a clearer
starting point for building websites with care and intention.

## A note on the reference

Stripe is the design reference for this independent educational project.
Stripe's name, branding, and referenced visual assets belong to their
respective owners. This project is not affiliated with or endorsed by
Stripe.
