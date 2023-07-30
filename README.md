# Left Panel
![image](https://github.com/kaverichougule/Weekly_Test_2-HTML/assets/101037685/90bde6b7-e7ca-4f26-9159-b8f33d90ac58)

The left panel is defined using an 'iframe' with the 'src' attribute set to "left.html" <br>
The content of the left panel is sourced from the "left.html" file, which contains a list of project titles along with preview images.

# Project 1 ,Project 2, Project 3, Project 4
![image](https://github.com/kaverichougule/Weekly_Test_2-HTML/assets/101037685/62593d32-3305-41c7-b81b-8c57a9fa7c92)

Each project title is displayed as a paragraph 'p' element, and a horizontal rule 'hr' separates each title from its corresponding preview image. <br>
Each project has an anchor 'a' tag that links to a specific URL of the project. The target attribute is set to "rightpanel," which means when a link is clicked, the content of the linked project will be displayed in the right panel (iframe with the name "rightpanel").

'p': Represents a paragraph of text, used to display project titles.
<br>
'hr': Represents a horizontal rule, used as a visual divider between project titles and images.
<br>
'a': Represents an anchor (link), used to create clickable links to other projects. The href attribute specifies the URL of the linked project, and the target attribute is set to "rightpanel" to open the linked content in the right iframe named "rightpanel."
<br>
'img': Represents an image, used to display project preview images. The src attribute specifies the image URL, and the alt attribute provides alternative text for accessibility. The height and width attributes set the dimensions of the image.

# Right Panel
![image](https://github.com/kaverichougule/Weekly_Test_2-HTML/assets/101037685/f839910e-9ed8-4c37-ac0f-15be9cc3fd10)
The right panel is defined using another iframe with the src attribute set to an external URL ("https://kaverichougule.github.io/Assignemnt1_Resume/").<br>
'iframe': Creates an inline frame, used to embed another HTML document ("left.html") within the main page. The src attribute specifies the source of the content to be displayed in the iframe. The width and height attributes set the dimensions of the iframe, and the frameborder attribute defines whether to display a border around the iframe.

