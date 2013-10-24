# Annotated Treasury Yield Curve

This was a simple experiment utilizing Google Docs for data scraping from a web site. In the A1 cell of a spreadsheet, I utilized the ImportHTML function:

`=ImportHTML("http://www.treasury.gov/resource-center/data-chart-center/interest-rates/Pages/TextView.aspx?data=yieldYear&year=2013", "table", 66)

to parse the 66th `table` element out of a page on the Treasury's website

## [Demo](http://jeremiak.github.io/treasury-yield-gdocs)

