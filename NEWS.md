# implyr 0.3.0

* Added more SQL translations including stringr and lubridate functions
* Updated for compatibility with dplyr 0.8.3
* Fixed errors when `na.rm = TRUE` is specified in some aggregate functions
* Added `src_databases()` function (#36)
* Made minor bugfixes and improvements

# implyr 0.2.4

* Made minor bugfixes and improvements
* Added rJava to Suggests (#26)

# implyr 0.2.3

* Updated for compatibility with dplyr 0.7.4
* Added tidyselect to Imports
* Required newer versions of Depends and Imports packages
* Added experimental support for complex types (`ARRAY`, `MAP`, `STRUCT`)
* Made bugfixes and improvements

# implyr 0.2.2

* Moved DBI from Imports to Depends (#9)
* Made minor bugfixes and improvements

# implyr 0.2.1

* Updated for compatibility with dbplyr 1.1.0
* Added and changed some SQL translations
* Enabled auto-disconnect by default
* Made minor bugfixes and improvements

# implyr 0.2.0

* Updated for compatibility with dplyr 0.7.0 (#5)
* Added automated tests (#6)
* Documented how to use `in_schema()` to specify the database containing the table (#2, #3)
* Made minor bugfixes and improvements
