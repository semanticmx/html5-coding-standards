Attaching CSS and JS files
=====================

## Table of contents
- [General Recommendations](/html5-coding-standards/README.md)
- [Script Placement](#```<script>```-Placement)

## ```<script>``` Placement
```<script>``` tags must be at the end of the page within the ```<footer>```  tag. When a browser renders a web page starts parsing HTML. As soon as the browser hits the ```<script>``` tag, it will download the ```<script>``` tag and then execute it. After finishing the execution of the ```<script>``` tag, it will continue parsing the HTML structure.  

This translates to a slower page load. This is why it goes to the end, so the HTML finishes parsing and then starts downloading the script tag.

**Incorrect placement** :-1:
```
<head>
    <script></script>
</head>
```

**Correct placement** :ok_hand:
```
<footer>
    <script></script>
</footer>
```

However, if we use the "defer" attribute, the page it'll load faster.

When we use the "defer" attribute, the webpage starts parsing HTML, and as soon it hits ```<script>``` tag, it'll start downloading, but unlike the script tag without the attribute, it will only execute when the HTML finishes parsing. The syntax would be like this:

```
<head>
    <script defer></script>
</head>
```
