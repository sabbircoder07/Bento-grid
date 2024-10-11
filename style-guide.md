.container {
background-color: #eee;
max-width: 144rem;
margin: 0 auto;
padding: 2rem;
height: 50rem;

display: grid;
grid-template-rows: repeat(2, 1fr);
//grid-template-columns: repeat(2, 30rem) 1fr;
grid-template-columns: repeat(3, 1fr);
gap: 2rem;
}

.item {
padding: 2rem;
font-size: 3rem;
font-family: sans-serif;
color: white;
&--1 {
background-color: Orange;
/_
grid-row-start: 2;
grid-row-end: 3;
grid-column-start: 2;
grid-column-end: 3;
_/
grid-row: 2/3;
grid-column: 2/3;
}
&--2 {
background-color: Green;
}
&--3 {
background-color: Violet;
}
&--4 {
background-color: Pink;
}
&--5 {
background-color: Blue;
grid-row: 2/1;
grid-column: 3/4;
}
&--6 {
background-color: Brown;
grid-row: 1/2;
grid-column: 2/3;
}
}

<div class="container">
      <item class="item item--1">1: Orange</item>
      <item class="item item--2">2: Green</item>
      <item class="item item--3">3: Violet </item>
      <item class="item item--4">4: Pink</item>
      <item class="item item--5">5: Blue</item>
      <item class="item item--6">6: Brown</item>
    </div>

Social Media 10x Faster with AI
Over 4,000 5-star reviews

Manage multiple accounts and platforms.

Maintain a consistent posting schedule.

Schedule to social media.
Optimize post timings to publish content at the perfect time for your audience.

Grow followers with non-stop content.

> 56% faster audience growth

Create and schedule content quicker.

Write your content using AI.

# Front-end Style Guide

## Layout

The designs were created to the following widths:

- Mobile: 375px
- Desktop: 1440px

> 💡 These are just the design sizes. Ensure content is responsive and meets WCAG requirements by testing the full range of screen sizes from 320px to large screens.

## Colors

- Purple 100: hsl(254, 88%, 90%)
- Purple 500: hsl(256, 67%, 59%)

- Yellow 100: hsl(31, 66%, 93%)
- Yellow 500: hsl(39, 100%, 71%)

- White: hsl(0, 0%, 100%)
- Black: hsl(0, 0%, 7%)

## Typography

### Body Copy

- Font size (paragraph): 18px

### Font

- Family: [DM Sans](https://fonts.google.com/specimen/DM+Sans)
- Weights: 400, 500

> 💎 [Upgrade to Pro](https://www.frontendmentor.io/pro?ref=style-guide) for design file access to see all design details and get hands-on experience using a professional workflow with tools like Figma. The design file for this challenge also includes a design system and tablet layout to help you build a more accurate solution faster.
