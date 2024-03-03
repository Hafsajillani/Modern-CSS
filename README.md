Here's an explanation of CSS elements used in this project:

1. Custom Properties (--variables): 🎨

   - `--column-count`, `--row-count`, `--column-size`, `--row-size`: Custom properties are used to define variables that can be reused throughout the stylesheet. They are prefixed with -- and can be used to store values like colors, sizes, etc.

2. CSS Grid (`display: grid`): 📏

   - `.speakers-grid`: This class is used to create a grid layout for the speakers.
   - `grid-template-columns`, `grid-template-rows`: These properties define the number and size of columns and rows in the grid, including the use of repeat notation (`repeat(var(--column-count), var(--column-size))`) and named grid lines (`[list-start]`, `[list-end]`).

3. Positioning (`position: absolute`): 🧭

   - `img`: The `position: absolute` property is used to position the images within their container.

4. Transitions (`transition: 500ms`): 🔄

   - `img`: The `transition` property is used to create a smooth transition effect when the images change size or position.

5. Animations (`@keyframes`): 🎬

   - `z-index-hack`: An animation is defined to change the `z-index` property of images, creating a stacking effect.

6. Pseudo-classes (`:hover`, `:focus`): 👆👀

   - `a:is(:hover, :focus)`: This selector is used to apply styles to the anchor (`a`) element when it is hovered or focused.

7. Logical Properties (`margin-inline`): ↔️

   - `.wrapper`: The `margin-inline` property is used to set the left and right margins of the `.wrapper` element, respecting the writing mode (e.g., left margin in LTR languages, right margin in RTL languages).

8. Other Styles: 🎨

   - `*::before`, `*::after`: These are used to target pseudo-elements before and after elements.
   - `html { color-scheme: dark light; }`: This sets the preferred color scheme for the document.
   - `h1, h2, h3, h4`: These styles are applied to different heading elements.
   - `.flow > * + *`: This selector targets elements that are siblings and follow another element.
   - `.visually-hidden`: This class is used to hide content visually while still allowing it to be accessible to screen readers.
   - `img`: Additional styles for images, such as setting the maximum width and ensuring they are displayed as block elements.

These modern CSS elements provide a flexible and powerful way to style web pages, allowing for more dynamic and responsive designs.




https://github.com/Hafsajillani/Modern-CSS/assets/103882246/cf6c7c78-2ee7-459f-a275-3a3915204d5a






