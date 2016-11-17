In this file, I want to describle some syntaxs about link. This function is very significant beacuse it will 
be used frequently. The syntax of link in Markdown has two forms.Now,if we want to creat a link that can 
skip to Google. we can do like this

	This is a [link](http://www.google.com) that can skip to Google.
	
The effect of above sentence is

This is a [link](http://www.google.com) that can skip to Google.

As we've seen, It's very easy. However, If lots of links used in our contents, then it's very difficult for
us to read and understand. So the following form will be used to replace the former form

	This is a [link][1] that can skip to Google.
	[1]: http://www.google.com
	
the effect of above sentence is 

This is a [link][1] that can skip to Google.
[1]: http://www.google.com

As we've seen, we can not see  '\[1\]: http://www.google.com' in the contents. This is hidden by interpreter 
automatically. So it can be placed in anywhere we want. It's the best idea that it is placed at the end of the file. 
So the contents we write will be similar to what we will see.  