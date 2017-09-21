# A brief summary on how to write SAS code

This style guide is mostly based on: 
[Style for writing and polishing programs](http://www.sascommunity.org/wiki/Style_guide_for_writing_and_polishing_programs)

## Case

* Use lower case. DATA and PROC are exceptions, they should be all caps. 
* Use initial and/or internal caps for nouns, eg:
  * names of data sets
  * variables
  * arrays
  * macro names

For example:

* MyArray
* DataFromExperiment
* Value1


## Comments

Use \* and the macro comment %\*. Reserve the /\* comment for banner type
comments

>  /\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*  
> some comment  
> \*\*\*\*\*\*\*\*\*\*\*/

## Indentation and whitespace

* Use hanging indent style, indent word-1 of succeding lines to align with word-2 in first line.
* Use spaces and not tab.
* align similar tokens in columns
* use empty line to separate logical blocks

For example:

> if SomeCondition then do;  
>    Assignment1 = 'value;  
>    Assign2     = value;  
>    end;  
> 
> some more code

## Linesize

The maximum line length is 72.

## Naming convention

uou
* use \_SomeTempVar for temporary variables as this allows for:

> drop \_:;

* use leading zeros if suffixes exceed 9, eg: Var01, Var02, ..., Var10, ...



