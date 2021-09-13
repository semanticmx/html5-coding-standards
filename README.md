HTML5 Coding Standards
=====================

HTML5 coding standards you must consider within your projects.

## Table of contents

- [General recommendations](#General-recommendations)
- [Links and Hyperlinks](#Links-and-Hyperlinks)

## General recommendations


### Git Branching Naming

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

## Links and Hyperlinks


### ```<script>`` Placement
Script tags must be at the of the page within the footer tag. When a browser renders a webpage start parsing HTML. As soon as the browser hits the script tag, it will download the script tag and then execute it. This translates to a slower page load. This is why it goes to the end, so the HTML finishes parsing and then starts downloading the script tag.

**Incorrect placment** :-1:
```
<head>
    <script></script>
</head>
```

**Correct placment** :ok_hand:
```
<footer>
    <script></script>
</footer>
```

However, if we use the "defer" attribute, the page it'll load faster.

When we use the "defer" attribute, the webpage starts parsing HTML, and as soon it hits script tag, it'll start downloading, but unlike the script tag without the attribute, it will only execute when the HTML finishes parsing. The syntax would be like this:

```
<head>
    <script defer></script>
</head>
```