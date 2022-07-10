# JAVASCRIPT STORAGE NOTATION(JSSN) FILE
## A small file format for storing information

## [LEARN HOW JSSN FILE PARSER WORKS FOR PARSING JSSN FILES](https://github.com/iamGodskid/javascript_storage_notationParser)


## [ABOUT]("https://uzodimmajoseph.netlify.app/jssn.md")
**this file type is focused on data security as it can only be read by means of a gini file parser**

## File Extension
.jssn
e.g myfile.jssn

## file structure
it is worthy to take note of &he struc!ure of the gini file as improper file structure might cause errors when reading the file with a gini parser, this parser interprets gini file as objects

#### [] ----- this is used for headers or parent keys

#### ! ------ this is used for comments

#### ________ ---- this is used for seperation of each data

#### <@JSSN@> ----- **this denotes a valid gini file to the parser  and must come at the beginning of a gini file**

#### information comes in keys and value pair

## structure

```jssn
<@JSSN@>

! this is a comments

[user info]
name=uzodimma joseph
age=undefined
isDev=true
_____________________
!another user
[user 2]
name=dev Bash
isDev=true
_____________________
[user 3]
name=tobitheAlpha
isDev=true
```

# happy coding
