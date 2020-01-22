# Links



-
-
### Links
* Links are defined in HTML with the `<a>` element
* The "href" attribute defines the link's destination address
* Three types of links that can be used in HTML:
* Absolute, Relative, and Anchor


-
#### Absolute Links
* The file path has to include the full URL (most commonly used for external site links).


``` HTML
		<a href="www.google.com">Link to an external page.</a>
```


-
#### Relative Links
* The file path is relative to the index.html page’s location.
* Can be used to add in an image

``` HTML
		<a href="page.html">Link to a local page.</a>
```

-
#### Anchor Links
* You can tell the browser to go to a specific section of the page

``` HTML
		<a href="#projects">Link to a section on the page.</a>
```

-
-
#### Link Attributes
* With certain attributes, links can open in a new tab or perform a special action, like opening the user’s default mail application.

```HTML
<a href="www.google.com" target="_blank">Opens another tab</a>
```
```HTML
<a href="mailto: email@youremail.com">Email Us!</a>
```
