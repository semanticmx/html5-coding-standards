General Recommendations
=====================

HTML5 coding standards you must consider within your projects.

## Table of contents

- [Git Branching Naming](#General-recommendations)
- [Attaching CSS and JS files](attaching-css-and-js-files/README.md)

## Git Branching Naming

Each branch has its default name, we must set the prefix name as the default name in order to recognize which type of branch are we working in. Example:

**Correct Naming** :ok_hand:

``` feature/cap1-mime-type  ``` 

**Incorrect Naming** :-1:

``` cap1-mime-type  ``` 

### Kebab-case names

When a web browser accesses a root folder, they'll only read camel cases or kebab cases folders to link a path. Otherwise, an error will occur. Example:

**Correct Naming** :ok_hand:

``` feature/cap1-mime-type  ``` 

**Incorrect Naming** :-1:

``` cap1_mime_type  ``` 


### Proper Use of Standards in HTML5

The correct format for using tags in HTML involves placing one tag per line, with nested tags indented appropriately. For attributes, if there is more than one, each attribute should be placed on its own line.

**Correct usage** :ok_hand:

```html
    <li>
        <a 
            href="#" 
            id="links"
        >
            home
        </a>
    </li>
    
```
    
**Incorrect usage** :-1:
    
```html
    <li><a href="#" id="links">home</a></li>
```   
    
### Proper Usage of Indentation
To enhance code readability, each element and attribute should be placed on its own line. This approach improves structure, making the code easier to read and maintain.
    
**Correct usage** :ok_hand:
```html
    
    <canvas 
            id="canva_identificado"
            onclick="dibujaforma()"
    >   
``` 
**Incorrect usage** :-1:
```html
    <canvas 
            id="canva_identificado"
            onclick="dibujaforma()">
```