### Description ###
PHP Anti-XSS Library developing for prevent the XSS(Cross Site Scripting) vulnerabilities on the web applications. PHP Anti-XSS Library automatically detect the encoding of the data that you want filter and if you wish its encoding your data again. Also there are 3 type of filtering option.

### Filter Options ###
  * Blacklist Filtering: Compares the data with a blacklist that you specify.
  * Whitelist Filtering: In the case of a data that does not conform to the type of data you've specified that does not allow the use of the data.
    * Data Types: "number", "string", "everything" and "default" (only number and string)
  * Graylist Filtering: Both methods are used together.

### Usage ###
  * Example 1: Setting the encoding of the data
> > Ex1: ` $data = AntiXSS::setEncoding($data, "UTF-8"); `
  * Example 2: Setting the filter for the data
> > Ex2: ` $data = AntiXSS::setFilter($data, "whitelist", "string"); `

### Version ###
  * Current Version: 1.2b