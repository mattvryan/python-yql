This project is not actively maintained.  It is a fork of the original, found at https://github.com/project-fondue/python-yql.
====

(Note from the original author)
Looking back at this project it's not where I would like it to be and I don't have the necessary time to 
update it so it remains here purely for posterity.


### Python YQL

Python YQL is a client library for making queries with Yahoo Query Language.



### Installation

    pip install yql

or 

    easy_install yql

### Usage

    >>> import yql
    >>> y = yql.Public(my_env, my_cb)
    >>> query = 'select * from flickr.photos.search where text=@text and api_key="INSERT_API_KEY_HERE" limit 3';
    >>> y.execute(query, {"text": "panda"})


### Source-code

Branches exist at
* https://github.com/project-fondue/python-yql
* https://github.com/mattvryan/python-yql


### Contributions

Bug-fixes/Features/Patches always welcome - please submit a pull request on github.com

