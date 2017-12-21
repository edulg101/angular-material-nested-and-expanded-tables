# Angular Material Nested And Expanded Tables

This is an example of different approaches to display tabular data using Angular Material.

Let's say you have the following JSON object and you are required to display it as a table:

[

  {

    "co1": "value",

    "col2": "value",

    "col3": "value",

    "subCols": [

      {
        "co1": "value",

        "col2": "value",

        "col3": "value"

      }

    ]

  }

]

Displaying a simple Angular Material table with a nested table for "subCols" should be very easy.

Expanded tables are not as straightforward, they make you think they are nested but they aren't. In my opinion it's a nicer approach because they provide better user experience and more custom CSS flexibility. The only thing is that you'll need a bit more code to make them work.
