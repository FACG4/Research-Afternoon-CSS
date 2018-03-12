# Research-Afternoon-CSS

# **CSS**

* responsive vs mobile-first design

  1. #### What is responsive design?
   * The term responsive web design, first coined by Ethan Marcote in 2010
   * Responsive design means that you only need one website.
   ![from large to small](https://cmv-ds-images.s3.amazonaws.com/wp-content/uploads/ds-mobilefirst-1.jpg)

  2. ####  What is mobile-first design?
  ![](https://cmv-ds-images.s3.amazonaws.com/wp-content/uploads/ds-mobilefirst-2.jpg)
   * the mobile-first concept means that the mobile version of a website should be at the heart of the design strategy and take into account the constraints and user browsing behaviour on mobile devices.
 3. #### Is a mobile-first strategy right for me?
   **Here are some questions you need to ask yourself:**

   * Do my customers prefer searching the web on computers or mobile devices?
   * Does my client mainly use mobile devices to browse the web?



   The **Block**, **Element**, **Modifier** methodology (commonly referred to as BEM) is a popular naming convention for classes in HTML and CSS. Developed by the team at Yandex, its goal is to help developers better understand the relationship between the HTML and CSS in a given project.

   ## Block component
   ```
    .btn {}

   ```
   block is a top-level abstraction of a new component, for example a button: `.btn { }`.

   ## Element that depends upon the block /
   .btnprice {}
   or elements, can be placed inside ,
   these are denoted by two underscores following the name of the block like `.btnprice { }`

   ## Modifier that changes the style of the block /
   ```
   .btn--orange {}
   .btn--big {}

   ```
   modifiers can manipulate the block so that we can theme or style that particular component without inflicting changes on a completely unrelated module.
   This is done by appending two hyphens to the name of the block just

   ## The benefits of BEM!

   Designers and developers can consistently name components for easier communication between team members. In other words, BEM gives everyone on a project a declarative syntax that they can share so that they're on the same page.
