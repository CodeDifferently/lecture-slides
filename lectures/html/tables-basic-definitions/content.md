# Tables - Basic Definitions


-
-
## Overview
* Defining a table
* Naming the table
* `<tr>` tag
* `<td>` and `<th>` tags



-
-
### Defining a Table
* Tables are a way to represent information in a grid format
* Defined by the `<table>` with opening and closing tags

```html
    <table>
    </table>
```


-
### Naming the Table
* Defining the name of the table is done using the <caption> opening and closing tags
* The `<caption>` tag must be inserted immediately after the <table> tags
* There can only ONE `<caption>` tag specified

```HTML
<body>
  <style>
  table, th, td, caption {
    border: 1px solid black;
}
  </style>
  <table>
    <caption>Monthly Savings</caption>
  </table>
</body>
```


-
-
### `<tr>` Tag
* Tables are divided into as many rows needed for your data purposes
* Rows are created using the `<tr>` opening and closing tags
* Rows are named using the table header `<th>` opening and closing tags

```HTML

<table>
  <caption>Monthly Savings</caption>
    <tr>
      <th>Month</th>
      <th>Savings</th>
    </tr>
    <tr>
      <td>January</td>
      <td>$100</td>
    </tr>
</table>
```

-
-


### `<td>` and `<th>` Tags
* The `<td>` tag defines a standard cell that contains data
* The `<th>` tag defines an header cell or a title of a column
```HTML
<body>
  <style>
  table, th, td {
    border: 1px solid black;
}
  </style>
  <table>
    <caption>Monthly Savings</caption>
      <tr>
        <th>Month</th>
        <th>Savings</th>
      </tr>
      <tr>
        <td>January</td>
        <td>$100</td>
      </tr>
  </table>
</body>
```

-
-

### How would we add another column to our table to track money spent?
<p fragment="fade-in">1. Add another header cell using the `<th>` tag to give the column a title</p>
<p fragment="fade-in">2. Add another standard cell using the `<td>` tag with the data



-

```HTML
<body>
  <style>
  table, th, td, caption {
    border: 1px solid black;
}
  </style>
  <table>
    <caption>Monthly Savings</caption>
      <tr>
        <th>Month</th>
        <th>Savings</th>
        <th>Spent</th>
      </tr>
      <tr>
        <td>January</td>
        <td>$100</td>
        <td>$250</td>

      </tr>
  </table>
</body>
```






-
-
## Lecture Summary
* Defining a table using the `<table>` opening and closing tags and using the `<caption>` tags to name the table
* Rows are created with the `<tr>` tags
* Columns are created with the `<td>` tags and are named using the `<th>` tags
