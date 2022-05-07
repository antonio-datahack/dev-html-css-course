<a id='section0'></a>
<h2>Table of contents</h2>

+ [Defining Colors in CSS](#section1)
+ [Pseudo-classes](#section2)
+ [Styling Links](#section3)
+ [Resolving Conflicting Declarations](#section4)

<hr>

<a id='section1'></a>
<h3><strong>Defining Colors in CSS</strong></h3>

[Back to Index](#section0)


<img src="https://github.com/antonio-datahack/dev-html-css-course/blob/main/img/css/defining-colors-in-css.png" />

<a id='section2'></a>
<h3><strong>Pseudo-classes</strong></h3>

[Back to Index](#section0)

```css

li:first-child {
  font-weight: bold;
}

li:last-child {
  font-style: italic;
}

li:nth-child(odd) {
  /* I can put numbers or odd / even
  /* color
  
```

<a id='section3'></a>
<h3><strong>Styling links</strong></h3>

[Back to Index](#section0)

```css 
a:link { /* this will basically target all the anchor elements that have an href attribute */
  color: #1098ad;
  text-decoration: none; /* this take out the highlight in the words */
}

a:visited {
  /* color: #777; */
  color: #1098ad;
}

a:hover {
  color: orangered;
  font-weight: bold;
  text-decoration: underline wavy orangered;
}

a:active {
  background-color: black;
  font-style: italic;
}

```

<a id='section4'></a>
<h3><strong>Resolving Conflicting Declarations</strong></h3>

[Back to Index](#section0)

<img src="https://github.com/antonio-datahack/dev-html-css-course/blob/main/img/css/resolving-conflicting-declaration.png" />
