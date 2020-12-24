<html> 
  <head> 
    <script src="jquery.js"></script> 
    <!-- <script> 
    $(function(){
      $("#includedContent").load("../zotprof.github.io/templates/index.html"); 
    });
    </script>  -->
    <script>
        function goPython(){
            $.ajax({
              url: "/myScraper.py",
             context: document.body
            }).done(function() {
             alert('finished python script');;
            });
        }
    </script>
  </head> 

  <body> 
     <!-- <div id="includedContent"></div> -->
  </body> 
</html>