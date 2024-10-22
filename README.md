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

**Correct use**

    <li>
        <a 
            href="#" 
            id="links"
        >
            home
        </a>
    </li>
    
**Incorrect use**
    
    <li><a href="#" id="links">home</a></li>
    
    
### Correct Use of Indentation
To improve code readability, all elements and attributes should be placed on separate lines.
    
**Correct use**
    
    <canvas 
            id="canva_identificado"
            onclick="dibujaforma()"
    >   
    
**Incorrect use**
    
    <canvas 
            id="canva_identificado"
            onclick="dibujaforma()">
