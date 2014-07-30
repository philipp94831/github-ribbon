GitHub-Ribbons
==============

[GitHub Ribbons](https://github.com/blog/273-github-ribbons) as WebComponent using [Polymer](http://www.polymer-project.org/)

[Demo](http://philipp94831.github.io/github-ribbon/)
----

Installation
------------

`bower install philipp94831/github-ribbon --save`

Usage
-----

Import Polymer & the element (`<head>`)

    <script src="bower_components/platform/platform.js"></script>
    <link rel="import" href="bower_components/github-ribbon/github-ribbon.html">

Use it like this  
`<github-ribbon repository="philipp94831/github-ribbon"></github-ribbon>`,  
this  
`<github-ribbon repository="philipp94831/github-ribbon" color="darkblue"></github-ribbon>`  
or this  
`<github-ribbon repository="philipp94831/github-ribbon" color="green" left></github-ribbon>`

###Attributes

- `color`: red (default), green, darkblue, orange, gray and white
- `repository`: Your GitHub repository
- `left`: Wether to display the ribbon in the upper left corner or not (default)
