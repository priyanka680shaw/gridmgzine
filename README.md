# Grid-Magazine
## Hosted Link: https://mayankkatheriya.github.io/Grid-Magazine/
![image](https://github.com/Mayankkatheriya/Grid-Magazine/assets/128832286/790175a5-e4c5-4359-b417-bdcb74e41334)
![image](https://github.com/Mayankkatheriya/Grid-Magazine/assets/128832286/c5d94def-687e-4f09-8bbb-fa37871876ed)

HTML:

This HTML code sets up the basic structure of a webpage with a head section containing metadata and links to external resources like fonts and stylesheets. The body section is where the actual content of the webpage will be placed. It serves as the container for all visible content that users will see and interact with when visiting the webpage.

CSS:

*, ::before, ::after Selectors:

Targets all elements, their before and after pseudo-elements.\
Sets padding and margin to 0.\
Uses the border-box box-sizing to include padding and borders in the element's total width.

"html" Selector:

Targets the "html" element.\
Sets the base font size to 62.5%, making it easier to calculate em units.

"body" Selector:

Targets the "body" element.\
Sets the font family to "Baskervville", a serif font.\
Text color is "linen".\
Background color is a dark blue-gray (rgb(20, 30, 40)).

"h1" Selector:

Targets all "h1" elements.\
Overrides the font family to "Anton", a sans-serif font.

"h2, h3, h4, h5, h6" Selectors:

Targets "h2", "h3", "h4", "h5", and "h6" elements.\
Overrides the font family to "Raleway", a sans-serif font.

"a" Selector:

Targets all anchor ("a") elements.\
Removes text underlines with no text decoration.\
Text color is "linen".\
![image](https://github.com/Mayankkatheriya/Grid-Magazine/assets/128832286/acfcb215-0825-4818-8c99-6baf01ba3655)
\
\
\
![image](https://github.com/Mayankkatheriya/Grid-Magazine/assets/128832286/2d7c8345-d0f7-4267-af8b-dd8432297343)
![image](https://github.com/Mayankkatheriya/Grid-Magazine/assets/128832286/bfa1c9e1-25ad-4b0b-a6db-1009898bbafe)
![image](https://github.com/Mayankkatheriya/Grid-Magazine/assets/128832286/4480e1e1-d2d8-4260-9f01-40a4700e5566)

HTML:\
The given HTML code defines the structure of a webpage. It includes a main section with a class "heading." Inside the main section, there is a header section with a class "hero" that contains an image with a link, a heading, and a paragraph. Below the header, there are two div elements. The first div contains the author's name with a link and the publish date. The second div holds social media icons as links. This structure helps organize the content of the webpage effectively.

CSS part:

"main" Element:

Uses grid display.\
Defines 3 columns with flexible width using "minmax" function.\
Row gap of 3rem between rows.

"img" Elements:

Images fill their containers.\
Maintains aspect ratio and covers container using "object-fit: cover".

"hr" Element:

Adds a horizontal rule with a margin of 1.5rem at top and bottom.\
Border style is 1px solid with a slightly transparent gray color.

".heading" Class:

Places content in the middle column (2nd) across rows.\
Subgrid with 2 columns in the middle column.\
Row gap of 1.5rem between rows.

".text" Class:

Places content in the middle column (2nd).\
Sets font size to 1.8rem.\
Defines a column width of 25rem.\
Text aligns justified.

".hero" Class:

Spans all columns.\
Position is relative within the grid.

".hero-title" Class:

Text aligns center.\
Color is orangered.\
Font size is 8rem.

".hero-subtitle" Class:

Font size is 2.4rem.\
Color is orangered.\
Text aligns center.

".author" Class:

Font size is 2rem.\
Uses "Raleway" font, sans-serif.

".author-name a:hover" Selector:

Applies background color on anchor hover.

".publish-date" Class:

Text color is a slightly transparent white.

".social-icons" Class:

Uses grid display.\
Font size is 3rem.\
5 columns with equal width.\
Aligns items in the center.\
![image](https://github.com/Mayankkatheriya/Grid-Magazine/assets/128832286/a6610712-b0c8-4ec9-8fa7-007ba36d4f69)
\
\
\
![image](https://github.com/Mayankkatheriya/Grid-Magazine/assets/128832286/819057ae-26b5-4314-ae19-f73b1cec5ff1)
![image](https://github.com/Mayankkatheriya/Grid-Magazine/assets/128832286/fb92fa4a-0362-4b91-a99d-63184ad25a6a)

HTML:\
The code represents a section of text content on a webpage. It includes multiple paragraphs explaining the shift from coding challenges to project-based learning in the freeCodeCamp curriculum. The change involves using projects with tests for more effective learning. The code highlights the transition from explanatory text to practical projects, enhancing the learning experience. The curriculum will focus on projects, replacing traditional lessons, and learners will code and build while passing tests for a smoother learning process.

CSS:

.first-paragraph::first-letter:

Targets the first letter of elements with the class "first-paragraph".\
Increases font size to 6rem for a large initial letter.\
Changes the color to orangered.\
Applies a float to the left of the letter.\
Adds a margin to the right to create space between the letter and the following text.

.quote Class:

Targets elements with the class "quote".\
Sets the text color to a bright blue (#00beef).\
Font size is 2.4rem.\
Text alignment is centered.\
Font family is "Raleway", a sans-serif font.

.quote::before:

Adds content before elements with the class "quote".\
Inserts an opening double quotation mark.

.quote::after:

Adds content after elements with the class "quote".\
Inserts a closing double quotation mark.\
![image](https://github.com/Mayankkatheriya/Grid-Magazine/assets/128832286/333b1c43-7d15-4a0a-a90b-00ba48e27f66)
\
\
\
![image](https://github.com/Mayankkatheriya/Grid-Magazine/assets/128832286/28369a15-f2b8-49d7-9848-64c4d8789b0c)
![image](https://github.com/Mayankkatheriya/Grid-Magazine/assets/128832286/41c867c7-5924-4f7f-a6f9-bc787e361f35)

HTML:\
The code defines a section with the classes "text" and "text-with-images." Inside this section, there's an article with the class "brief-history." The article contains a heading level 3 with the class "list-title," followed by a paragraph. Within an unordered list with the class "lists," there are multiple list items. Each list item contains a heading level 4 with the class "list-subtitle" and a paragraph describing different versions (V1 to V6) of the freeCodeCamp curriculum. The versions detail the curriculum's evolution, including the addition of resources, challenges, certifications, and improvements over the years.

CSS:

.text-with-images Class:

Targets elements with the class "text-with-images".\
Uses grid display with 2 columns: the first column takes 1 fraction of available space, and the second column takes 2 fractions.\
Column gap of 3rem between columns.\
Adds margin at the bottom of 3rem.

.lists Class:

Targets elements with the class "lists".\
Removes default list bullet points using list-style-type: none.\
Adds margin at the top of 2rem.

.lists li Selector:

Targets list items ("li") within elements with the class "lists".\
Adds margin at the bottom of 1.5rem for spacing between list items.

.list-title, .list-subtitle Selectors:

Targets elements with the classes "list-title" and "list-subtitle".\
Sets text color to a bright blue (#00beef).\
![image](https://github.com/Mayankkatheriya/Grid-Magazine/assets/128832286/4d2f7ee3-27f2-4658-bc35-c0b871a511f3)
\
\
\
![image](https://github.com/Mayankkatheriya/Grid-Magazine/assets/128832286/a46c3dc9-e0b6-4f67-8da3-4d7aefa9256c)
![image](https://github.com/Mayankkatheriya/Grid-Magazine/assets/128832286/3d270728-ef4e-434b-b954-98eedf90def5)

HTML:\
Within the code, an "aside" element with the class "image-wrapper" is defined. Inside the "aside," there are three "img" elements with different source URLs, alt text, and dimensions. Each image is associated with a specific project. Additionally, there's a "blockquote" element with the class "image-quote" containing a paragraph with a quote. The quote emphasizes the value of freeCodeCamp as a resource for people learning to code. The images and quote are organized within this "aside" section.

CSS:

.image-wrapper Class:

Targets elements with the class "image-wrapper".\
Uses grid display with 2 columns: the first column takes 2 fractions of available space, and the second column takes 1 fraction.\
Defines 3 rows with a minimum content height for each.\
Gap of 2rem between grid items.\
Centers items both horizontally and vertically within the grid cells.

.image-1, .image-3 Selectors:

Targets elements with the classes "image-1" and "image-3".\
Spans both columns in their respective rows (from column 1 to the last column).\
![image](https://github.com/Mayankkatheriya/Grid-Magazine/assets/128832286/03fae786-c883-47b0-84fb-a988a958b2f0)
\
\
\
![image](https://github.com/Mayankkatheriya/Grid-Magazine/assets/128832286/dcbf6523-115d-47e4-bc0f-adc1be49babd)

@media only screen and (max-width: 720px):

Targets screens with a maximum width of 720px.\
Adjusts the column layout of .image-wrapper to 1 fraction.

@media only screen and (max-width: 600px):

Targets screens with a maximum width of 600px.\
Adjusts the column layout of .text-with-images to 1 fraction.

@media only screen and (max-width: 550px):

Targets screens with a maximum width of 550px.\
Adjusts font sizes for .hero-title, .hero-subtitle, .author, .quote, .list-title, .social-icons, and .text.

@media only screen and (max-width: 420px):

Targets screens with a maximum width of 420px.\
Further reduces the font size of .hero-title.

## our webpages is ready
# thankyou😊
