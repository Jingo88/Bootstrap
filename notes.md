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


Now we have a button!

<button type="button" class="btn btn-primary btn-lg" data-toggle="modal" data-target="#biggerBoat">
Click Me!
</button>

To use this we will need a Modal code

<!-- Modal -->
<div class="modal fade" id="biggerBoat">
<div class="modal-dialog">
  <div class="modal-content">
    <div class="modal-header">
      <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
      <h4 class="modal-title" id="myModalLabel">Chief Brody</h4>
    </div>
    <div class="modal-body">
      We're going to need a bigger boat.
    </div>
  </div>
</div>
</div>

* fade means it fades in and out
* modal dialog and content is what brings modal in
* the button with type of button and class of close will bring in the x 
* 

