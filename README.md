#Dash worklflow (Alfred v2)

Really simple workflow to integrate Alfred and Dash. Dash is an application to lookup developer documention and snippets. 

Right now the extension (v0.1) has two basic functionalities:

* Lookup in alfred with the keyword 'dl'

	 `dl php:array_reverse`
  => Just the results for php, for the array_reverse function
     
     `dl pop` => Results for all languages. These results are sorted based on the default sorting in Dash.
 
* Opening Dash with a keyboard shorcut and push the current selection to Dash.

 	Right now the shortcut is `Ctrl + shift + e`
 
	*I'm aware of the system service of Dash which can handle this, but for me that's not working out very well in context of an IDE like PHPStorm.*
 
To be able to use this workflow you need to have [Dash](http://kapeli.com/) installed