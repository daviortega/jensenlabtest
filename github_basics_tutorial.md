#Introduction to Github & Markdown


##VisualCode Commands
```
ctrl-`
```
*-->pulls up terminal window*

##Navigating Directories
`cd ..` *--> go up one directory*
`cd [name of directory]` *--> go to specific directory*
`cd -` *--> go to previous directory (very useful!)*
`ls` *"list" --> lists contents of current directory*
`pwd` *--> gives filepath to current directory*
`rm -rf [filename]` *--> deletes a file in current directory (nuclear command)*

##Visualizing Updates in VisualStudioCode:
*Type [command-shift-v]*



##Naming Files in VisualStudioCode:
*MUST have ".md" at end of filename, otherwise Github will not register.*


##Font Formatting in Markdown:

\` *--> inicates snippet of code*

<[insert command]> *--> HTML format*



##Cloning from Github
`git clone [repository SSH key]` *--> clones Github package into current directory

**IMPORTANT: Make sure you are in correct directory before installing!**

##What is NPM and why is it important?

* **Goal:** *Use other people's code*

* *Repository that allows the user to search for packages of code that perform various tasks.*

* *Essentially acts as a search engine for code*

* *Command: "npm install [name of package]" --> automatically begins download, no dependency*

* *Command inside Directory:* `npm init` *--> will allow us to install npm packages with dependency, make sure command is run inside correct directory*
* *Use* `cd` *etc. to find correct directory*

* *Command to Install with Dependency:* `npm install [name of package] --save`  *--> links current package to downloaded package*

* *Cloned Packages:* `npm install` *--> downloads packages on which cloned package is dependent.*


Reference to cluster algorithms Wikipedia page:
*https://en.wikipedia.org/wiki/Cluster_analysis#Algorithms*
