General Recommendations
=====================

HTML5 coding standards you must consider within your projects.

## Table of contents

- [Git Branching Naming](#General-recommendations)
- [Attaching CSS and JS files](attaching-css-and-js-files/README.md)
- [Formatting](#Formatting)
- [CSS Attributes](css-attributes/README.md)

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

## Formating

Formatting is pretty arbitrary, but it’s much easier to follow if everyone uses the same style. Individuals may not agree with every aspect of the formatting rules, but it's important that all project contributors follow the style rules so that they can all read and understand everyone’s code easily.

### Indentation

Indentation helps us to define where an element starts and ends. We can use four spaces that are equal to one tab.

**With Indentation** :ok_hand:

```
    <nav>
      <ul>
        <li><a href="index.html">This</a></li>
        <li><a href="index.html">is</a></li>
        <li><a href="index.html">a</a></li>
        <li><a href="index.html">Nav</a></li>
        <li><a href="index.html">Element</a></li>
      </ul>
    </nav>
```

**Without Indentation** :-1:
```
    <nav>
    <ul>
    <li><a href="index.html">This</a></li>
    </ul>
    </nav>
```

### The use of spaces

A code should only have one space between block codes.

**Correct Use** :ok_hand:
```
   <header>
        <hgroup>
            <h1>Dive into HTML5</h1>
            <h2>Semantic Elements</h2>
        <hgroup>
    </header>

    <nav>
      <ul>
        <li><a href="index.html">This is a nav</a></li>
      </ul>
    </nav>
```

**Incorrect Use** :-1:
```
   <header>
        <hgroup>
            <h1>Dive into HTML5</h1>
            <h2>Semantic Elements</h2>
        <hgroup>
    </header>



    <nav>
      <ul>
        <li><a href="index.html">This is a nav</a></li>
      </ul>
    </nav>
```

The strings shouldn't leave blank spaces

**Correct Form**

```<head></head>```

**Incorrect Form**

```<head> </head>```

### Tag's Attribute order

When a tag has more than one attribute, we should list them with spaces.

**Correct Use**
```
<link 
    rel="stylesheet" 
    type="text/css" 
    href="style.css">
```

**Incorrect Use**
```
<link rel="stylesheet" type="text/css" href="style.css">
```

