# pricing-table

Welcome to the "Flexbox Pricing Table" project! In this project, I recreated a responsive pricing table for a website. The pricing plans are initially displayed in a row, but they stack on top of each other when the browser window becomes too small. This responsive behavior was achieved using CSS Flexbox and a media query. Additionally, each pricing plan was styled to ensure an appealing and user-friendly design, all accomplished using internal CSS.

## Project Overview

- **Title**: Flexbox Pricing Table
- **Objective**: Create a responsive pricing table using Flexbox CSS and style each pricing plan.

### HTML Structure

The project's HTML structure includes a container with three pricing plans:

- **`.pricing-container`**: This container utilizes Flexbox properties like `display`, `justify-content`, and `align-items` to arrange pricing plans in a row with proper spacing and alignment.

- **`.pricing-plan`**: Each pricing plan represents a flex item with a maximum width, padding, background color, and border radius for styling.

- **`.plan-title`**: Titles of the pricing plans are styled with font size and weight properties.

- **`.plan-price`**: Prices of the pricing plans are displayed with an emphasized font size and weight.

- **`.plan-features`**: Features of each pricing plan are listed using an unordered list (`<ul>`) with customized margin and list style properties.

- **`.plan-button`**: Sign-up buttons are styled with padding, background color, and text color properties.

### CSS Styling

- **Flexbox Layout**: Flexbox CSS properties are used to create a responsive layout, ensuring that pricing plans stack vertically when the viewport becomes narrow.

- **Styling Elements**: Each pricing plan is styled with background colors, padding, and border-radius to enhance their visual appeal.

- **Font**: The 'Sono' font from Google Fonts is imported and applied to the entire page.

- **Media Query**: A media query with `@media` is used to switch to a vertical layout for pricing plans when the viewport width falls below 1250 pixels.

## Usage

Feel free to explore the HTML and CSS files to see how the responsive pricing table was achieved. By leveraging Flexbox CSS and media queries, the pricing plans adjust their layout to provide an optimal viewing experience on various devices and screen sizes.

Enjoy navigating the responsive Flexbox pricing table!