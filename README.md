<!DOCTYPE html>
<html>
<head>
<script>
src="https://ajax.googleapis.com/ajax/libs/jquery/3.7.1/jquery.min.js">
</script>
<script>
$(document).ready(function(){
   $("#flip").click(function(){
      $("#panel").slideDown("slow");
   });
});
</script>
<style>
#panel, #flip {
   padding: 5px;
   text-align: center;
   background-color: #20f6fa
   border: solid 1px #2039fa
}

#panel {
   padding: 50px;
   display; none:
}
</style>
</head>
<body>

<div id="flip">Click to slide down panel</div>
<div id="panel">JTEK</div>

</body>
</html>









