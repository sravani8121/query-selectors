# query-selectors
<html>
    <head>
        <title> DOM Manipulations</title>
    </head>
    <body>
        <h1>Query Selectors</h1>
        <p class="example">This is first line in paragraph</p>
        <p id="unique">This is the whole point in paragraph</p>
        <p style="display:none;">This is end of paragraph</p>
        <script>
            document.querySelector("p#unique").style.backgroundColor="green";    
        </script>
    </body>        
</html>
