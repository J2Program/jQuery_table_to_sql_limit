# DataTable demo (Server side) in Php,Mysql and Ajax
jquery table to sql limit


Grid view is a very important web component in modern web. Sorting, searching, pagination is not a easy job in HTML tables. So many grid view framework out there, DataTable.js is the most popular among them. It is open source, light weighted, highly flexible and customizable, features like AutoFill, inline editor, sticky header, responsive, Supports bootstrap, foundation. In version 1.10 DataTable has changed and improved over version 1.9. An entirely new API is available in DataTables 1.10.
In my blog I will try to explore datatable 1.10. So lets get started with most popular gridview framework in the planet.

In basic initialization datatable provides pagination, sorting, instant searching by loading whole data records at once. It can be a performance issue fetching large amount of data from server side. It will be better if you integrate server side pagination, searching and sorting, so we can break large amount data in chunk, So performance will increase significantly. Before proceed please take a look of the demo.

First i have created a index.php, where I have written html markup and basic initialization. created a table wth id “employee-grid” containing three column “Employee name”, “Salary”, “Age”.
