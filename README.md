#Standard setup

This repo includes my basic configuration of a development site running [generator-bones](https://github.com/matt-bailey/generator-bones)

###Template system 

1. Added a data folder inside template directory to store content and variables in JSON 
	* Page-specific JSON
	* Context-specific JSON	
2. Added [markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) folder inside template directory.
3. Added helpers folder and [custom helper](http://stackoverflow.com/questions/21503510/assemble-register-handlebar-helper-function) with testing purposes 
	* Didn't do very well. For now I've decided to learn first how to make use of built-in helper functions [handlebars-helpers](http://assemble.io/docs/Helpers.html)


###Styles 

1. The grid was generated cloning the bootstrap git repo inside bower_components folder because installing with bower caused [errors](https://github.com/twbs/bootstrap/issues/13949).
	* [semantic](http://stackoverflow.com/questions/18854927/using-mixins-in-bootstrap-3-to-avoid-unsemantic-markup-for-layout-structure) 
	* [changed default grid](https://github.com/maripac/dev-pacc/wiki/Customizing-bootstrap-3-grid-system)

