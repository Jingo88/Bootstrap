# Bootstrap

you can get the links to the css and js files on the website

you can set up each with a div class of row, and inside the row put multiple divs with their respective column sizes (how many columns it takes up). Bootstrap knows how to be responsive and will change the format to the correct screen size.

''' <div class = "container">
	  	<div class='row'>
	  		<div class='col-md-4'> Hello </div>
	  		<div class='col-md-4'> Princess </div>
	  		<div class='col-md-4'> Peach </div>
	  	</div>
  	</div>
'''

How do you overrite Bootstraps responsiveness? You can make another class 
'''<div class = "container">
	  	<div class='row'>
	  		<div class='col-md-4'> Hello </div>
	  		<div class='col-md-4 col-xs-6'> Princess </div>
	  		<div class='col-md-4'> Peach </div>
	  	</div>
	  	</div>'''
In this example it is saying, if the screen is smaller the columns containing "PRINCESS" will take up six columns instead of four