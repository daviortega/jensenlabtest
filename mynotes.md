#Meeting Notes

###*Topic: Dictionaries in Python:*
* example: a = ['first': 'Tony', 'last': 'Kukavica']
* command: a['first']
* output: 'Tony'



##**For 02/27 Meeting:**
>1. Complete Markdown tutorial

>2. Begin working on own tutorial about learning Github that will make sense to like-minded people

>3. Look at "Biowonks Github"

>4. Figure out how to get multiple line breaks in Markdown



##**Notes 02/27**:
###*Topic: Test-Driven Development*

* All test files must be formatted: [filename/name of constructor class].tests.js
* Command to run: `npm test` (need to be in correct directory)
* Use single quotes, no double quotes, even then double quotes will work to begin with
* Write specially-formatted comments for methods (include info such as "@param + [description]")
    --> makes for pseudocode documentation

Advantages:
* Simultaneously test while developing code
* Code is precisely tailored to perform desired functions

Disadvantages:
* Slower, sometimes less efficient than writing and debugging
* Frequently changing structure

**_Goal:_** Use this development method to code PhyPro in Javascript (currently on in Python)


###*Topic: FASTA Sequencing Format*

* File begins with `>header`
* Line breaks don't have meaning
* Breaks are indicated by `>[headerX]` where X is a number

**_Goal:_** Develop FastaReader.js

**_Tip:_** `[command]-d` will select the next occurance of a selected String



##**For 03/04 Meeting**:

>1. Write code with proper "FastaReader" constructor

>2. Create method headers required by the tests.

>3. Continue coding until the tests are passing.

>4. *Extra:* Read more about bioinformatics --> familiarize with concepts, etc.

>5. *Extra:* Read about Copyleft, Copyright, and public domain --> Davi considering using this for PhyPro

