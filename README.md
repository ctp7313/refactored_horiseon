Horiseon Website Refactoring README
2020.06.14
Documented by Chris Parker
CTP7313@gmail.com

For this project, I refactored the code to improve accessibility in both the HTML and CSS files.


HTML Changes:
1. Added <title> information to properly identify site for SEO.

2. Add comments to separate code, allowing for future developers to discern various portions of the HTML and guidance on changing the background image asset.

3. Changed the <div> tags to use HTML semantics, thus improving accessibility and readability fo the code without having to view through a browser.

4. Made changes to classes and ids to reflect changes made in CSS file to remove redundancies.

5. Replaced <ul> and <li> tags with <a href> to the navigation bar.

6. Improved indentation to increase accessibility and readability.

7. Identified and fixed broken id for SEO section. Nav bar will now jump to all respective sections.


CSS Changes:
1. Identified redundancies and consolidated classes to singular class name. Reflected changes to HTML.

2. Identified and replaced classes associated with <div> tags to now reflect HTML semantics.

3. Identified and consolidated classes that were separate but associated to the same HTML element.

4. Added comments to properly identify header, main, and sidebar portions of the site. 


CHANGES:
If changes are desired, the one thing to note is the background image is linked within the CSS. Within CSS, go to .background-image class and change link with relative path to the CSS file.



