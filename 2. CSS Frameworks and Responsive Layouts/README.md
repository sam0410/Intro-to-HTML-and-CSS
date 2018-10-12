<h2> Notes for this lesson : 

+ For responsive design : use percentages for width and height. Also one can use customized Mobile/Tablet/Desktop view using 
```
@media only screen and (max-width: 300px){
	p{
		background-color: blue;
	}
}
```
   In this case the background color of all the paragraphs is turned blue when the window size is smaller than 300px.

+ The css classes one should create columns of all sizes from 1/12, 2/12 ... , 12/12 of the page width

+ ``` display: flex; ``` or ``` flex-wrap: wrap; ```

+ Margins (creates space outside the element) and padding (creates space inside the element) is used for negative spaces for better readability.

+ ``` overflow: auto; ``` is used when you have a lot of text in a small area.

+ To add compatibility across browsers add ```normalize.css``` in the head of the html file. Download the css code from https://necolas.github.io/normalize.css/8.0.0/normalize.css.

+ We can use a placeholder image from http://placekitten.com/

+ The fonts can be used from https://fonts.google.com/
