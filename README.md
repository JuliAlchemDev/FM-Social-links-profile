# Frontend Mentor - Social links profile solution

This is a solution to the [Social links profile challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-links-profile-UG32l9m6dQ). 

### Screenshot

![social-links-profile](./design/destkop-design.jpg)


### Links

- Solution URL: [GitHub](https://github.com/JuliAlchemDev/FM-Social-links-profile)
- Live Site URL: [Netlify](https://fm-social-links-profile-julialchem.netlify.app)

## My process

1. **Exploring the Figma design system**  
   I started by analyzing the Figma file to extract all the design tokens: colors, typography, spacing, and border-radius.  
   I translated these into **CSS custom properties** to keep the code scalable and consistent.

2. **Setting up the project structure**  
   I organized my CSS into three separate files for clarity:  
   - `reset.css` to normalize styles across browsers  
   - `custom-properties.css` for colors, spacing, fonts, and other variables  
   - `style.css` for component-specific styling  

3. **Implementing semantic HTML and BEM naming**  
   I coded the profile card using semantic tags (`<main>`, `<address>`, `<section>`, `<ul>`)  
   and applied the **BEM naming convention** to keep the CSS modular and maintainable.

4. **Adding accessibility features**  
   I included `aria-label` and `role="navigation"` for screen readers and made sure decorative images had proper `alt` attributes.  

5. **Handling typography and layout**  
   - Converted pixel values from the design to `rem` units for scalability.  
   - Used CSS Grid and `gap` properties for spacing and alignment.  
   - Implemented `@font-face` with `font-display: swap` to reduce FOUT.

6. **Optimizing UX and visual details**  
   - Added hover effects, transitions, and custom cursor for interactive elements.  
   - Set `width` and `height` on images to prevent **Cumulative Layout Shifts (CLS)**.  

7. **Debugging and testing**  
   I used **Chrome and Safari DevTools** to inspect computed styles, verify rem units, spacing, font sizes, and overall layout.  
   This helped me ensure that the card looked correct and responsive across devices.

8. **Final adjustments**  
   Made minor tweaks for spacing, alignment, and accessibility, ensuring the profile card was clean, responsive, and user-friendly.


### What I learned

- Using a **design system** from Figma to define **custom properties** (`--colors`, `--spacing`, `--font-size`, etc.) makes the project more maintainable and scalable.  
- Learned how to properly set **font sizes and spacing with `rem` units** and discovered how the browser computes `rem` based on the root font size.  
- Practiced implementing **semantic HTML** and **BEM naming** to keep code organized and accessible.  
- Explored **accessibility features**, like `aria-label` and `role="navigation"`, and learned when to use them for screen readers.  
- Learned to prevent **Cumulative Layout Shifts (CLS)** by setting `width` and `height` on `<img>` elements.  
- Practiced **CSS Grid** and **gap/padding** for layout and spacing, making the profile card fully centered and responsive.  
- Implemented **custom fonts with `@font-face`** and learned about `font-display: swap` to reduce FOUT (Flash of Unstyled Text).  
- Improved **UX details**, like hover effects and cursor changes, while keeping transitions smooth.  
- Learned to organize **CSS modularly** with separate files: `reset.css`, `custom-properties.css`, and `style.css`.  
- Used **Chrome and Safari DevTools** to debug CSS, check computed styles, inspect spacing, and verify how `rem` and other units are rendered in the browser.


### Built with

- Semantic HTML5 markup
- CSS custom properties
- Mobile-first workflow
- BEM methodology
- Grid and relative units
- Figma design as reference

## Author

- Linkedin - [Julia Alkhimova](https://www.linkedin.com/in/julialkhimova/)
- Frontend Mentor - [@JuliAlchemDev](https://www.frontendmentor.io/profile/JuliAlchemDev)
