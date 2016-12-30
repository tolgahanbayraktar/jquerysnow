# HOW TO USE SNOW PLUGIN

Add page head tag 
<pre>
script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.1.1/jquery.min.js
snow.js
</pre>

# AFTER ADD FOOTER
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