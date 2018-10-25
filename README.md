# Python-Solr

Solr is an open source search platform that allows us to use full text search, highlighting, faceted search and real time indexing.
Pysolr provides multiple options like add, optimize, delete
  1. solr.add : It will index a list of dictionaries where each key is the field name and each value is the value to index.
  2. solr.optimize :  Tells Solr to streamline the number of segments used, essentially a defragmentation operation. If you are making a                         bulk action, wait until finish to optimize index. It’s useful in realtime indexing where application can fragment                           your index slowing your queries.
  3. solr.delete – query indicating a collection of documents to delete.
