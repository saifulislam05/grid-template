# Grid Template Ass-8 CSS

## Hosted Link
You can view the project live at [View Live Project](https://saifulislam05.github.io/grid-template/)

## Project Description
The "Grid Template" project is a web page that demonstrates the use of CSS Grid for creating a testimonial grid. It showcases several testimonials, each with a unique background color and content.

## UI
![image](https://github.com/saifulislam05/grid-template/assets/73392705/98a29d93-5a90-4691-a0a5-50de05175fa0)

## HTML Explanation

### Main Container (`.testimonial-grid`)
- The main container holds all the testimonial articles.
- It uses CSS Grid to arrange testimonials in a grid layout.
- The grid is divided into five areas: "one," "two," "three," "four," and "five."

### Testimonial Articles (`.testimonial`)
- There are five testimonial articles with different backgrounds and content.
- Each testimonial article is a distinct block within the grid.

### Writer Info (`.writter-info`)
- Inside each testimonial, there is a container for writer information.
- It uses Flexbox to align items horizontally and add spacing between them.

### Writer Image (`.writter-image`)
- Contains the writer's profile image.
- It ensures the image maintains its aspect ratio and has rounded corners.

### Writer Details (`.writter-details`)
- Contains the writer's name and position.
- It adjusts the font size for name and position.

### Testimonial Content (`.content`)
- Contains the testimonial text.
- The first paragraph has a larger font size and font weight.
- The second paragraph has a smaller font size and lower opacity.

## CSS Explanation

### Global Styles (`*`)
- `margin: 0;`: Resets margin for all elements.
- `padding: 0;`: Resets padding for all elements.
- `box-sizing: border-box;`: Includes padding and border in element dimensions.

### Body (`body`)
- `width: 100%;`: Sets the body width to 100%.
- `height: 100vh;`: Sets the body height to 100% of the viewport height.
- `display: flex;`: Uses flexbox for layout.
  - `justify-content: center;`: Horizontally centers content.
  - `align-items: center;`: Vertically centers content.
- `font-family: 'Barlow Semi Condensed', sans-serif;`: Sets the font family.
- `background: rgb(236, 242, 248);`: Sets the background color.

### Primary and Secondary Colors (`.primary-color` and `.secondary-color`)
- `.primary-color`: Sets the text color to white (`#ffffff`).
- `.secondary-color`: Sets text opacity to 80% (`opacity: 0.8`).

### Testimonial Grid (`.testimonial-grid`)
- `width: min(95%, 70rem);`: Sets a maximum width with responsiveness.
- `display: grid;`: Uses CSS grid for layout.
- `gap: 1.5rem;`: Defines the gap between grid items.
- `grid-auto-columns: 1fr;`: Sets column sizing.
- `grid-template-areas`: Defines grid areas for articles.

#### Testimonial Articles (`.testimonial`)
- `padding: 2rem;`: Adds padding to testimonial articles.
- `-webkit-border-radius: .5rem;`, `-moz-border-radius: .5rem;`, `-ms-border-radius: .5rem;`, `-o-border-radius: .5rem;`: Applies border radius to round corners.

##### Testimonial First (`.testimonial.first`)
- `background: rgb(117, 65, 200);`: Sets the background color.

##### Testimonial Second (`.testimonial.second`)
- `background: rgb(72, 85, 106);`: Sets the background color.

##### Testimonial Third (`.testimonial.third`)
- `background: rgb(255, 255, 255);`: Sets the background color.
- `color: rgb(72, 85, 106);`: Sets the text color.

##### Testimonial Fourth (`.testimonial.fourth`)
- `background: rgb(25, 33, 46);`: Sets the background color.

##### Testimonial Fifth (`.testimonial.fifth`)
- `background: rgb(255, 255, 255);`: Sets the background color.
- `color: rgb(72, 85, 106);`: Sets the text color.

#### Testimonial Quote Background (`.testimonial.quote`)
- `background-image: url("./images/bg-pattern-quotation.svg");`: Sets a background image.
- `background-repeat: no-repeat;`: Prevents background image repetition.
- `background-position: top right 10%;`: Positions the background image.

#### Writer Info (`.writter-info`)
- `display: flex;`: Uses flexbox for layout.
- `gap: 1rem;`: Defines spacing between child elements.
- `align-items: center;`: Vertically centers items.

##### Writer Image (`.writter-image`)
- `width: 28px;, height: 28px` Sets dimensions for the writer's image.

- Writer Image img (`.writter-image img`)
    - `max-width: 100%;`: Limits the image width.
    - `border-radius: 50%;`, `-webkit-border-radius: 50%;`, `-moz-border-radius: 50%;`, `-ms-border-radius: 50%;`, `-o-border-radius: 50%;`: Rounds the image corners.

##### Writer Details (`.writter-details`)
- Contains the writer's name and position.

 - Writer Name (`.writter-details .name`)
   - `font-size: 0.8125rem;`: Sets font size for the writer's name.

  - Writer Position (`.writter-details .position`)
    - `font-size: 0.6875rem;`: Sets font size for the writer's position.

#### Testimonial Content (`.testimonial .content`)
- Contains the testimonial paragraphs.

##### First Paragraph (`.testimonial .content p:first-child`)
- `font-size: 1.25rem;`: Sets font size.
- `font-weight: 500;`: Sets font weight.
- `line-height: 1.2rem;`: Sets line height.
- `margin-top: 1.25rem;`: Adds top margin for spacing.

##### Second Paragraph (`.testimonial .content p:nth-child(2)`)
- `font-size: 0.8125rem;`: Sets font size.
- `line-height: 1.25rem;`: Sets line height.
- `margin-top: 1.25rem;`: Adds top margin for spacing.
- `font-weight: 400;`: Sets font weight.

### Imports (`@import`)
- Imports the Google Fonts 'Barlow Semi Condensed' for the project's font.

