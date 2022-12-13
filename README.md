# code-refactor1

## Description

### What was your motivation?

To make this webpage more accessible to users.

### Why did you build this project?

Web accessibility is an increasingly important consideration for businesses. It ensures that people with disabilities can access a website using assistive technologies such as video captions, screen readers, and braille keyboards. Making a website accessible is also good for business for many reasons, one of them being that accessible sites are better positioned in search engines like Google. It also helps companies avoid litigation that can occur when people with disabilities cannot access their website.

### What problem does it solve?

- Semantic HTML elements can be found throughout the source code.
- HTML elements follow a logical structure independent of styling and positioning.
- Image and icon elements contain accessible `alt` attributes.
- Heading attributes fall in sequential order.
- Title elements contain a concise, descriptive title.

### What did you learn?

#### [Semantic HTML](https://www.w3schools.com/html/html5_semantic_elements.asp)

![different parts of a webpage](https://www.w3schools.com/html/img_sem_elements.gif)

non-semantic elements: `<div>`, `<span>`

semantic elements: `<article>`, `<aside>`, `<details>`, `<figcaption>`, `<figure>`, `<footer>`, `<header>`, `<main>`, `<mark>`, `<nav>`, `<section>`, `<summary>`, `<time>`.

#### [Image alt attributes](https://www.w3schools.com/tags/att_img_alt.asp)

`alt` attribute will add an "**alt**ernative" string to an image which may be not displayed or loaded on a webpage. This string is usually a description of a picture.

## Usage

The appearance and functionality are almost the same as before.

![screen shot](./READMEassets/01-html-css-git-challenge-demo.png)

But I changed the title of this webpage (just for distinguishing from original code, and it is a sign of that GitHub page is updated) and the bottom information about authors. In real refactor project all the things will look the same, unless the need is changing style and texts of webpages, and this project is just an example. Now it looks like:

![screen shot after refactoring](./READMEassets/code-refactor1.png)

To check the HTML file in detail, right click a position and inspect. The alt attribute could be seen if the image is not displayed (change the URL of image so it will be blocked).

![image displayed correctly](./READMEassets/Screenshot%20from%202022-12-13%2018-24-33.png)

double left click the path of image, then replace it with a space or just delete the path, press enter

![image alt string](./READMEassets/Screenshot%20from%202022-12-13%2018-25-11.png)

## Credits

<https://www.w3schools.com/html/>

## License

MIT
