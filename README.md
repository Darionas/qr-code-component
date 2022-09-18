# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H).

## Overview

QR code component challenge on Frontend Mentor.

### Screenshot

![QR code](/images/screenshot.png)

### Links

- Solution URL: (https://github.com/Darionas/qr-code-component)
- Live Site URL: (https://darionas.github.io/qr-code-component/)

## My process

* Set HTML layout.
* Create CSS external file to set style for HTML layout:
  * Choose to use responsive web image by using max-width property for image, and including meta viewport element in my web page. It works on Mobile (375px) and Desktop (1440px) as well.
  * Use css techniques to center vertically or horizontally:
    ```css
    /*center horizontally*/
    .im {
      display: block;
      margin-left: auto;
      margin-right: auto;
    }

    /*center horizontally and vertically*/
    .content {
      display: flex;
      justify-content: center;
      align-items: center;
    }
    ```
  * Set colors, font size and family according `style-guide.md`


### Built with

It is based on:
- Semantic HTML5 markup:
- CSS custom properties:
  - External css stylesheets
  - Viewport element
  - Flexbox
 
### What I learned

In that challenge I found out that The Markdown Guide is a new subject for me. I am new in that subject.
I had a short overwiev of [The Markdown Guide](https://www.markdownguide.org/basic-syntax/).

### Continued development

- Next learning subject is going to be The Markdown Guide. 
- I am not confortable with choosing which layout system to use when I start new webpage. There are several of them with some advantages and disadvantages. I think It comes with practice, experience.
- I still dig deeper in JavaScript.


### Useful resources

- [Center image horizontally](https://www.w3schools.com/howto/howto_css_image_center.asp) - This helped me for centering horizontally image.
- [Center element horizontally and vertically](https://www.w3schools.com/howto/howto_css_center-vertical.asp) - This is an amazing article which helped me centering vertically and horizontally element by using flexbox.
- [Using box-sizing property](https://www.w3schools.com/css/css3_box-sizing.asp) - This is a nice article which allows us to include the padding and border in an element's total width and height.
- [Method to insert external stylesheet](https://www.w3schools.com/css/css_howto.asp) - This lets us to create CSS external file, and make HTML code more readable.
- [Responsive image](https://www.w3schools.com/css/css_rwd_images.asp) - This explains how to create responsive web design (images), by using max-width property, and including meta viewport element in your web pages.

## Author

- Frontend Mentor - [@Darionas](https://www.frontendmentor.io/profile/Darionas)

## Acknowledgments

Thank you Frontend Mentor team for opportunity to try, practice, train yourself in different level challenges and gain invaluable experience.


