

12:50GMT+1
Contrasts Checker

	https://userway.org/contrast/f8f9fa/ffffff?fg=000000&bg=ffffff

19:51GMT+1
List of CSS inheritable properties
	https://stackoverflow.com/questions/5612302/which-css-properties-are-inherited
	
	
22nd June 2022
07:31GMT+1

	Recall that:

	v you need to use web safe fonts when programming. 
		https://www.w3schools.com/cssref/css_websafe_fonts.asp
	v Buttons comes with default grayish background and not white, so we need to change it to white and remove the default border
	v Another font to take advantage of is google fonts and
	v  https://www.1001fonts.com/
		We apply this font by: 
		i. first downloading the folder and adding/dragging and dropping it into our project folder/file system which is a ttf format file
		ii. Then we use the @font face rule in css and write the font and the name to give the font in my style sheet as follows:
		@font-face {
		src: url("Corleone.ttf");
		font-family: Corleone;
		}
	v You can use  .webp extensions for animations like images and this can be found in https://giphy.com/
	Why .webp? It does not use as must data as does gifts used when sent from a server to a client and it has better compression and it's more compact. 
	
23rd June 2022
15:05GMT+1

		
		
	v Shadow have x y z w properties which means right offset, down offset, blur and color
	v HACK! With "0px 0px 2px black" you can give a text with a white color a shadow in a white background or a text with a very similar color with it's background or the contrast between both of them is very weak, by increasing the blur which is the third value. We use the hack to make our text stand out despite the similarities between them.

