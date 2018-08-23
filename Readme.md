This is fork of Juggling Lab project: http://jugglinglab.sourceforge.net/ with support of command line arguments

To build project - just run "ant" on project root

Command line arguments:

First argument  (optional) - string in siteswap notation. Documentation of notation: http://jugglinglab.sourceforge.net/html/ssnotation.html
Example (open juggling panel with trick 441):
```
java -jar JugglingLab 441
```
 
Second argument (optional) - string "gif". If exists, juggling lab export picture with trick to gif file and exit after that. It useful for batch gif creating. Filename of exported picture is equal to first argument.
Example (will create file 534.gif): 
```
java -jar JugglingLab 534 gif
```

