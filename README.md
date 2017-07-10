# cssGrid
Css Grid built with Less

This is a simple Css grid built with Less. It has 12 columns and two functional layouts based on the size of the screen. The large version can be used by adding the classes col-1 to col-12, col-1 beeing the smallest, taking 1/12 of the row and col-12 one taking the full width of the row.

The other view, for the smaller screens, can be used by adding col-m-1 to col-m-12 classes. It can be added in adition to the col-1/col-12. For this to work well, you need to specify manually which will be the last element on the row after resiszing. So if we have 12 col-1 and on a smaller screen they are col-m-2s the sixth will be the last one on that row, and the 7th will be the first one on the second row. So please specify this by adding the 'last' class and the 'first' class to your divs.

You can check it out at  https://annno.github.io/cssGrid/
