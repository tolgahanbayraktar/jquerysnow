# Installing

Simple! Fork this repo or download snow.js and jquery.min.js and add the following assets to your HTML:

<code>
<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.1.1/jquery.min.js"></script>
<script src="snow.js"></script>
</code>

# Running
Once you have your elements ready you can show instructions running
<pre>
	$(document).ready(function() {
	$.fn.snow({
	        minSize: 5,
	        maxSize: 25,
	        newOn: 1000,
	        flakeColor: '#e74c3c'
	    });
	});
</pre>