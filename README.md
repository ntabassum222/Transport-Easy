<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <title>Example ofjQuery Fade-In and Fade-Out Effects</title>
    <script src="http://code.jquery.com/jquery-1.12.4.js"></script>
    <style type="text/css">
      p{
          padding:15px;
          background: #DDA0DD;
      }
    </style>
    <script type="text/javascript">
      $(document).ready(function(){
      
          $("#p1").click(function(){
            $("#p2").fadeOut();
              $("#p3").fadeOut();
         });
      });
</script>
</head>
<body>
  <b><font size="+3">I need help in ....</font><b/b>
  <p id="p1"
     style="border:2px solid red;">Destination</p>
  <p id="p2"
     style="border:2px solid red;">Personal Assistance</p>
  <p id="p3"
     style="border:2px solid red;">Delay Notification</p>
    
 </body>
 </html>
 <style>
    body{
      background: Slateblue;
  }
  p{
  color:black;
  background:dodgerblue
  }
  </style>
    
