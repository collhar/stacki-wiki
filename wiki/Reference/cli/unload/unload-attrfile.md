## unload attrfile

### Usage

`stack unload attrfile {file=string} [processor=string]`

### Description

Unload (remove) attributes from the database

### Parameters
* `[file=string]`
* `{processor=string}`

   The processor used to parse the file and to remove the data into the
	database. Default: default.

### Examples

* `stack unload attrfile file=attrs.csv`

   Remove all the attributes in file named attrs.csv and use the default
	processor.


### Related
[load attrfile](load-attrfile)


