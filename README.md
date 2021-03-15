# St. Louis Crime Incidents

This data package extends and updates the [St. Louis crime data scraping
package from OpenSTL.](https://github.com/OpenSTL/stl-crime-data). The St.
Louis Metropolitan Police Department [publishes monthly crime incident
files](http://www.slmpd.org/Crimereports.shtml), but they are very difficult to
download and use. The OpenSTL package has Jupyter notebooks for scraping and
cleaning the data, but the data included in the Github repo has not been
updated in 5 years.

This package retains the original scraper but improves the cleaning process.
See the Clean.ipynb notebok for details of the cleaning process.

## Building the Package

The metatab package builds from the data in the cache directory, which stores
the results of scraping. So, to build the latest data, the scraper must be run
first.

1. Run the Scrape.ipynb notebook
3. run ``mp build``