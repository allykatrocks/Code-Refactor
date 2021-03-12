# homework-code-refactor

In this assignment, we were tasked with going through an exisitng code and making sure it met accessibility standards and had proper semantic elements. The exisitng code worked properly for the most part but had several semantic elements to be improved, such as the overuse of the "div" element. For example, the original HTML for this section had the header and nav elements classified as div elements. I re-wrote them to be actual header and nav elements as that made more semantic sense and improved the code's functionality.
[Code Header snippet](./assets/images/header.png)

As we went through the HTML, we were also responsible for updating the CSS so it reflected the changes we were making. Again, the original code had made classes out of most of the HTML elements, so when I went into the CSS, I had to change the selectors from class selectors to universal selectors so they would reflect the desired CSS styles. I also consolidated some elements into one solid CSS styling block, as they were originally listed as individuals unnecessarily. This is what the finished code looked like:
[CSS Consolidated Code](.assets/images/blocks.png)

Lastly, we needed to make the site follow accessiblity standards. Accessibility is important because you as a web developer are ensuring that all potential users, including those with disabilities, have a good ser interface experience and can easily access the site's information. This was best shown in the image tags where there were missing alt tags. For every image, I went in and added descriptive alt tags definig the image so that someone using a screen reader could properly access the site. Here is an example:
[HTML Alt Tag](.assets/images/tag.png)