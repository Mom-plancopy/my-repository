<!DOCTYPE html>
<html>
<head>
<style>
    .comicsans {
    font-family: 'Comic Sans MS', sans-serif;
    }
</style>
</head>
    <body>
        <h1 class="comicsans">Welcome to my repository!</h1>
        <input class="comicsans" placeholder = "Search here"></input><button class="comicsans">Submit</button>
        <hr>
        <script>
            document.querySelector('button').addEventListener('click', function() {
                document.querySelector('h1').innerText = document.querySelector('input').value;
            });
        </script>
    </body>
</html>
