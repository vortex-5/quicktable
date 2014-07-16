quicktable
==========

###A quicktable plugin for ckeditor 4

This plugin adds a quicktable feature to the existing table plugin.

The original code was submitted by [danyaPostfactum](https://github.com/danyaPostfactum) as a pull request for the table plugin. I just extracted the code and made a seperate plugin out of it and added some options to it (see sample in plugin directory)

The original table plugin is required for this to work!

####Configuration:
```javascript
	CKEDITOR.replace( 'editor1', {
		quickTableRows: 20, // Count of rows in the quicktable (default: 8)
		quickTableColumns: 20, // Count of columns in the quicktable (default: 10)
		quickTableBorder: '1', // Border of the inserted table (default: 1)
		quickTableWidth: '90%', // Width of the inserted table (default: 100%)
		quickTableStyle: 'border-collapse: collapse;' // Content of the style-attribute of the inserted table (default: null)
	});
```
For more Information see original post [here](https://github.com/ckeditor/ckeditor-dev/pull/92)
