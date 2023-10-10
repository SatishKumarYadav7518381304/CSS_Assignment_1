# CSS_Assignment_1

                  Assignments No -10


Ques -1

 What is CSS and why use it ?

Ans

 CSS is the language for describing the presentation of Web pages, including colors, layout, and fonts. It allows one to adapt the presentation to different types of devices, such as large screens, small screens, or printers. CSS is independent of HTML and can be used with any XML-based markup language.

Ques-2 

What are the different ways to bring CSS into an the HTML file

Ans 

CSS can be added to HTML documents in 3 ways:

1-Inline - by using the style attribute inside HTML elements.

2-Internal - by using a <style> element in the <head> section.

3-External - by using a <link> element to link to an external CSS file.


Ques-3 

What do  you mean by specificity in CSS ?

Ans 

When more than one set of CSS rules apply to the same element, the browser will have to decide which specific set will be applied to the element. The rules the browser follows are collectively called Specificity
 

Specificity Rules include:  

CSS style applied by referencing external stylesheet has lowest precedence and is overridden by Internal and inline CSS.
Internal CSS is overridden by inline CSS.
Inline CSS has highest priority and overrides all other selectors.


GEEKSFORGEEKS
CSS | Specificity
When more than one set of CSS rules apply to the same element, the browser will have to decide which specific set will be applied to the element. The rules the browser follows are collectively called Specificity
 

Specificity Rules include:  

CSS style applied by referencing external stylesheet has lowest precedence and is overridden by Internal and inline CSS.
Internal CSS is overridden by inline CSS.
Inline CSS has highest priority and overrides all other selectors.: 
 



inline internal and external css

Specificity Hierarchy :Every element selector has a position in the Hierarchy. 

1-Inline style: Inline style has highest priority. 
 
2-Identifiers(ID): ID have the second highest priority. 
 
3-Classes, pseudo-classes and attributes: Classes, pseudo-classes and attributes are come next. 
 
4-Elements and pseudo-elements: Elements and pseudo-elements have lowest priority. 



