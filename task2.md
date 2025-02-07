TaskTask 2: Styling with SASS.

1️⃣ Basic Variables & Nesting Practice

* Task:Create a simple page with a header, footer, and main content.
* Steps:

  * Define global variables for colors, font sizes, and spacing.
  * Use these variables to style the header, footer, and main content.
  * Nest the styles for the header, footer, and main content inside respective selectors.

Objective: Practice defining variables and nesting styles.

2️⃣ Mixins & Reusability Practice

* Task: Create a button component with different states (default, hover, active).
* Steps:

  * Define a mixin for button styles (e.g., background color, padding, border).
  * Use the mixin to create the base styles for a button.
  * Create separate styles for hover and active states using the mixin.

Objective: Learn how to create and reuse mixins.

3️⃣ Extend & Inheritance Practice

* Task: Create a set of button classes (primary, secondary, and danger).
* Steps:

  * Define a base button class with common styles like padding, border radius, etc.
  * Use the @extend feature to create variations (primary, secondary, danger) that inherit from the base button class.

Objective: Practice inheritance and using the @extend feature.

4️⃣ Partials & Import Practice

* Task: Create a modular stylesheet using partials.
* Steps:

  * Split your CSS into multiple files (e.g., _variables.scss,_header.scss, _footer.scss, etc.).
  * Use @import to bring all the partials together in a main file (styles.scss).
  * Update the structure to maintain modularity and organization.

Objective: Learn how to split your CSS into smaller, reusable files (partials).

5️⃣ Responsive Design with Mixins

* Task: Build a responsive layout for a blog post with a sidebar and content area.
* Steps:

  * Define a mixin for media queries to handle different screen sizes.
  * Style the blog layout to be two columns (sidebar + content) on large screens and a single column on smaller screens.
  * Use the mixin to make the layout responsive by adjusting the number of columns on smaller screens.

Objective: Practice creating responsive layouts with reusable media query mixins.

6️⃣ CSS Grid with SASS Variables

* Task: Create a responsive grid layout using CSS Grid and SASS.
* Steps:

  * Define grid-related variables (e.g., number of columns, gap size).
  * Use these variables to create a 3-column grid on larger screens and a 1-column grid on smaller screens.
  * Use media queries to adjust the grid layout for different screen sizes.

Objective: Get familiar with using CSS Grid along with SASS variables for flexibility.

7️⃣ Theming with SASS Variables

* Task: Implement a light and dark theme switcher for a webpage.
* Steps:

  * Define SASS variables for light and dark theme colors.
  * Use @mixin to apply the respective themes based on a class toggle.
  * Allow the user to toggle the theme using JavaScript by adding/removing the dark theme class.

Objective: Learn how to switch between multiple themes using SASS variables and mixins.

8️⃣ SASS Functions for Calculations

* Task: Create a page with dynamically sized elements based on a base font size.
* Steps:

  * Define a SASS function that calculates the font size relative to a base size (e.g., function font-size($size) { return $size * 1.2; }).
  * Use the function to dynamically adjust the font size for various elements (header, paragraphs, etc.).

Objective: Learn to use functions for performing calculations in SASS.

9️⃣ Advanced Nesting & Selectors

* Task: Build a custom card component with an image, title, and description.
* Steps:

  * Use advanced nesting to style the card container, image, title, and description.
  * Add hover effects to the card that change the background color and scale the image.
  * Create a :focus effect for when the user clicks on the card.

Objective: Master advanced nesting and selector specificity in SASS.

🔟 Animate Elements with SASS

* Task: Add a hover animation effect to a button and a slide-in effect for an element.
* Steps:

  * Use @keyframes to create a sliding effect.
  * Animate a button background color on hover.
  * Apply the sliding effect to a sidebar that enters from the left when hovered.

Objective: Learn how to apply animations using SASS.
