# Regular Expressions

## Summary

Regular expressions are a syntactic standard for searching for patterns in text. They are a powerful way to process textual data and facility in working with regular expressions is an essential part of your toolkit. This syntax is available in most (if not all) programming languages. 

## What

Regular expressions (regex, for short) describes a _standard_. By that I mean that it is a generally-agreed-upon format for describing the search parameters and methods to a computer system. The syntax of regex involves a series of characters which describe classes or groups of characters that you are searching for, along with parameters for grouping those characters and wildcards specifying missing characters, boundaries, and other features of the text. 

For example....





## Exercises

1. Navigate to [https://regexr.com/](https://regexr.com/). Using the cheatsheet they provide at the left of the page, try the following:
- Find words with "at" in them
- Find words that end in "s"
- Find all the words that have two consecutive vowels
- Find all the words that have two "t"s in them.

2. Using [regexr](https://regexr.com), type or paste in a longer version of a text. (You could use something like Project Gutenberg to find a good text). Think of some patterns you would like to find in this text. Do you want to find examples of a particular set of words?  Would you like to know, for example, whether the text uses British or American spellings? How would you write a regex expression to search for that? Do you want to find words that end in -ful and -full (like beautiful)? Or do you want to find simple adverbs (ending in -ly)? Do you want to find all the examples of a particular verb, in all its tenses and forms (walks, walking, walked). Try out your searches and see what you find

3. What do you think `^(http|https|ftp):[\/]{2}([a-zA-Z0-9\-\.]+\.[a-zA-Z]{2,4})(:[0-9]+)?\/?([a-zA-Z0-9\-\._\?\,\'\/\\\+&amp;%\$#\=~]*)` does?

4. You can use regex in many places. Let's start with openrefine. Load the dantetweets data into openrefine. For any given column, click on the arrow and filter the text using a regex expression. What might you be able to find using this method? 



## Resources

For lots of links, check out this stackoverflow answer: [https://stackoverflow.com/questions/4736/learning-regular-expressions](https://stackoverflow.com/questions/4736/learning-regular-expressions)

There are numerous tutorials and resources to help you learn regular expressions. I highly recommend xxx

There are also great interactive sites for you to test out your regular expressions. 

[regexr](http://regexr.com)
