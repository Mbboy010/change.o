<!DOCTYPE html>
<html>
<head>
   <title> Try It Yourself </title>
</head>
<body>
   <p id="demo"> I am a paragraph element. </p>
   <button type="button" onclick="myFunc()"> Change HTML Content </button>

   <script>
      function myFunc() {
         var text = "Hello World!";
         document.getElementById("demo").innerHTML = text;
      }
   </script>
</body>
</html>
