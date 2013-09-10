jmSelectSearchable
==========================
###Directive to select from list of objects with search input box     
It's not "typeahead", because in typeahead you can input any text in inputbox, and here you can only select from list.  

###Attributes

* **objects** - model which should contain list of objects to select
* **ng-model** - model will be set on select
* **print-attrs** - template for output attributes of object in list, attributes should be in curly braces (for example: "{{ first_name }}: {{ mobile }}") 

###Example
Included HTML template is an example, currently designed for Twitter Bootstrap 3.0.0    
Usage [example in Plunker](http://plnkr.co/edit/UVzDiNZKbjDE1ZxY9hJD)  

###Improvements
Any pull-requests for improvements and optimizations are very welcomed!   
