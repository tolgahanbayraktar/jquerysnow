# HOW TO USE SNOW PLUGIN

Add page head tag 

<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.1.1/jquery.min.js"></script>
<script src="snow.js"></script>

# AFTER ADD FOOTER

<script type="text/javascript">
    $(document).ready(function() {
    $.fn.snow({
            minSize: 5,
            maxSize: 25,
            newOn: 1000,
            flakeColor: '#e74c3c'
        });
    });
</script>
