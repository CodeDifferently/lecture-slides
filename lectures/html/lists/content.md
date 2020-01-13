# Lists


-
-
## Lecture Overview
* Unordered Lists
* Ordered Lists
* Definition Lists


-
-
### Unordered Lists
* Unordered lists show up by default with bullets and have opening and closing tags, `<ul></ul>`
* Each list item starts with the `<li>` tag and ends with `</li>`

```HTML
    <ul>
       <li>Order</li>
       <li>Doesn’t</li>
       <li>Matter</li>
    </ul>
```
-
#### Styling of the Item Marker
* The CSS list-style-type property is used to define the style of the list item marker
* Three different styles to choose: discs (bullets), circle (empty circle), and square (solid square)

-
#### Discs (bullets)
```HTML
  <ul style="list-style-type:disc;">
    <li>Gold</li>
    <li>Red</li>
    <li>Black</li>
  </ul>
```


-
#### Circles (empty)
```HTML
  <ul style="list-style-type:circle;">
    <li>Gold</li>
    <li>Red</li>
    <li>Black</li>
  </ul>
```

-
#### Squares
```HTML
  <ul style="list-style-type:square;">
    <li>Gold</li>
    <li>Red</li>
    <li>Black</li>
  </ul>
```


-
-
### Ordered Lists
* An ordered list begins with the opening tag `<ol>` and ends with the closing tag `</ol>`
* List items will be by default marked with numbers and will be within the  list item opening and closing tags `<li></li>`

```HTML
  <ol>
    <li>Water</li>
    <li>Coffee</li>
    <li>Ginger Ale</li>
  </ol>
```

-
#### Styling of the Item Markers
* The type attribute of the `<ol>` tag, specifies the type of the list item marker
* List items can be numbered with numbers (default), uppercase and lowercase letters, and lowercase and uppercase roman numerals.


-
#### Numbers
```HTML
  <ol type="1">
    <li>Water</li>
    <li>Coffee</li>
    <li>Ginger Ale</li>
  </ol>
```


-
#### Uppercase Letters
```HTML
  <ol type="A">
    <li>Water</li>
    <li>Coffee</li>
    <li>Ginger Ale</li>
  </ol>
```



-
#### Uppercase Roman Numerals
```HTML
    <ol type="I">
      <li>Water</li>
      <li>Coffee</li>
      <li>Ginger Ale</li>
    </ol>
```


-
#### Lowercase Roman Numerals
```HTML
    <ol type="i">
      <li>Water</li>
      <li>Coffee</li>
      <li>Ginger Ale</li>
    </ol>
```




-
-
### Definition Lists
* A definition list is a list of terms, with a description of each term
* The `<dl>` tag specifies the definition list, the `<dt>` tag specifies the term or name, and the `<dd>` tag describes each term

```HTML
    <dl>
      <dt>Water</dt>
        <dd>- clear and flavorless</dd>
      <dt>Coffee</dt>
        <dd>- black and hot beverage</dd>
    </dl>
```
