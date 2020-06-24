# Design Web Pages with CSS

## Duckett HTML & CSS  | Chapter 10  | Introducing CSS

### CSS  
What is it?  
   
    CSS-
> **allows the user to create rules that specify how the content of an element should appear**  -Jon Duckett  

What does it do?  
- Gives html style and personality
- Can be used universally across all pages in a site
- Uses curly brackets: { } 
- Uses different selectors to target areas of html
- Uses "id" and "class" to select items
- Consists of two basic parts
    - selector 
    - declaration
      - Made up of:
        - property
        - value
-Has unique parameters, such as
    - width
    - size

CSS can be used *internally* AND *externally* **HOWEVER** it is best practices to use it externally for troubleshooting purposes.

CSS Selectors:

-  Universal Selector: applies to all elements in the document    

-  Type Selector: matches element names

-  Class Selector: matches an element whose class attribute has a value that matches the one specified after the period (full stop) symbol

-  ID Selector: matches an element whose id attribute has a value that matches the one specified after the pound symbol

-  Child Selector: matches an element that is a direct child of another

-  Descendant Selector: matches an element that is a descendant of another specified element

-  Adjacent Sibling Selector: matches an element that is the next sibling of another

-  General Sibling Selector: matches an element that is a sibling of another, although it does not have to be the directly preceding element.

**Rules**
1. If there are two or more rules, the latter will take precedence UNLESS one selector is more specific.

2. If you specify the font-family of color properties on the body element, they will apply to most child elements.

3. You can force many properties to inherit values from their parent elements by using inherit for the value of the properties.

4. CSS rules usually appear in a separate document, which is the best practice. 

## Duckett HTML & CSS  | Chapter 11  | Color

