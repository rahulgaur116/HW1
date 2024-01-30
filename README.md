## Rahul Sharma Challenge 1- Submission

Purpose of this project is to update an existing code to meet following webpage requirements.

## User Story
```
AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines
```
## Acceptance Criteria
```
GIVEN a webpage meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
WHEN I view the icon and image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title
```
## Mock-Up
The following image shows the web application's appearance and functionality:

![The Horiseon webpage includes a navigation bar, a header image, and cards with text and images at the bottom of the page.](./Assets/01-html-css-git-homework-demo.png)

Project Tasks Completed:

Following chnages were made to the html & css styling file to improve accesibility and html sematic and to matvh the desired mockup image for the webpage layout.

1. Changed the various repetetive "div" section to make the code follow a semantic html. 

2. Changed "div" for the First section of the code inside body element was renamed to header

3. As the elements within the header class included some click on text, those "div" was renamed to "nav"

4. Any section containing an image, the "div" was renamed to "figure"

5. Additional "div" element were renmaed/changed to "article" "section" to furthur improve the html file semantic.

6. Modified css.style file to update the names of the classes, elemets to match the respective headings in the html file

7. Remove many css styling commands and included them within the bigger umbrella of a bigger class

8. Renamed website title to be more descriptive.

9. Removed the unenccesary footer content to match the provided finihsed webpage mockup.

10. One of the elements "search-engine-optimization"in the heading/navigation ba was not functional. added the correct "id" element to this, to direct that element to the related page content upon clicking.

11. Added "alt" atribute with descriptive text to every image element to improve accessibility.

