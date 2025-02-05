# Technical Challenge 3: Convert a Fixed Layout to a Fluid One
## CSS Box Model, Box-Sizing, CSS Units, Margin Collapse, and Overflow Handling.
## Deadline: 10am on February 10th, 2025

---

### Overview

In this challenge, you will:
- Convert a fixed layout to a fluid layout.
- Explore the CSS box model (content, padding, border, and margin).
- Compare content-box vs. border-box for box-sizing.
- Examine `px`, `em`, `rem`, `vh`, and `vw` units.
- Investigate margin collapse and how vertical margins interact.
- Learn how to handle overflow when content exceeds its container.

### Resources

  - [What is CSS?](https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Styling_basics/What_is_CSS)
  - [Box Model](https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Styling_basics/Box_model)
  - [Responsive Design](https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/CSS_layout/Responsive_Design)

### Requirements

1. **Fixed to Fluid Layout**  
   - You are given starter files in the `site/` folder.  
   - Open `fixed.html` to see a simple layout. Carefully review its structure, then modify widths and positioning and change/add as much or as little content as you wish to create a fixed version that displays consistently across various screen sizes.  
   - Next, create `fluid.html` by copying over `fixed.html` and applying fluid widths (e.g., percentages or viewport units). This will allow the layout to adapt and resize when the browser window changes.

2. **CSS Box Model**  
   - Examine the `styles.css` file to observe how `padding`, `border`, and `margin` are used.  
   - Change at least three elements to have different values for padding, border, and margin to illustrate the box model visually.  
   - Ensure the changes you make reflect both minimal and more pronounced spacing strategies.

3. **Box-Sizing Property**  
   - Locate `box-sizing` in `styles.css`. Switch between `content-box` and `border-box`, and observe how total element size is calculated differently.  
   - Document these differences in your report so you can explain your decision.

4. **CSS Units**  
   - Replace or mix `px`, `em`, `rem`, `vh`, and `vw` in your layouts to find an optimal balance for a fluid design.  
   - Use a combination of units to see how text and containers respond to browser size changes.

5. **Margin Collapse**  
   - In both `fixed.html` and `fluid.html`, add margin to adjacent `<div>` elements:
   ```css
   .content-section {
     margin: 20px 0;
   }
   .sidebar {
     margin: 30px 0;
   }
   ```
   - Observe how the total space between elements is not the sum of their margins.
   - Document the actual spacing vs. expected spacing in your report.

6. **Overflow Handling**  
   - In `fluid.html`, modify a container to demonstrate overflow:
   ```css
   .sidebar {
     height: 200px;
     overflow: hidden; /* Try: scroll, auto */
   }
   ```
   - Add enough content (like paragraphs of text) to exceed the height.
   - Test different overflow properties to see how content behaves.

## Report

Write a brief report in `writing/report.md` describing your design approach.

## Submission

Commit your updated files (including the starter HTML/CSS) to the repository with meaningful commit messages.

## Evaluation

1. [ ] A functional fixed layout version.  
2. [ ] A functional fluid layout version.  
3. [ ] Proper demonstration of the box model.  
4. [ ] Use of both `content-box` and `border-box`.  
5. [ ] Demonstration of multiple CSS units.  
6. [ ] Clear example of margin collapse.  
7. [ ] Explanation of overflow handling.  
8. [ ] A completed report (including one screenshot).  
9. [ ] All files committed with descriptive messages.  
10. [ ] Completed tasks checked off.
