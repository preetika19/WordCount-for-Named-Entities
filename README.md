# WordCount-for-Named-Entities
Computing the word frequency for named entities in a large file using PySpark

Extracted only the named entities from the text using NLP Library and MapReduce. 
Output is of the form (key, value) where key is the named entity and value is it's count.
Output from the reducer is sorted in decending order of count. 
