# HTML

## Table

A table is a grid view of data, which makes it easy to display complex data.

### Basic table structure

To use table in HTML we use `<table>` as the first step, then to create a row we use `<tr>` and at the end, we use `<td>` to insert data in the cell of the table.

To represent the heading for a row or a column we use `<th>`, and we can use the ***scope*** attribute to indicate whether it is heading for a row or a column.

For long tables, we can use:

1) `<thead>`: The headings of the table shoulf sit inside the `<thead>`element.

2) `<tbody>`: The body should sit inside the `<tbody>` elemant.

3) `<tfoot>` : The footer belongs inside the `<tfoot>` element.

These tags are distinguishing between the main content of the table and the first and the last rows.

We can use some attributes to change the table style but we should not use them because we can use CSS for styling.