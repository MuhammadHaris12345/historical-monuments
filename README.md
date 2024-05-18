# historical-monuments
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <script src="https://code.jquery.com/jquery-3.7.1.min.js"
        integrity="sha256-/JqT3SQfawRcv/BIHPThkBvs0OEvtFFmqPF/lYI/Cxo=" crossorigin="anonymous"></script>
</head>

<body>
    <script>
        $(document).ready(function () {
            $("button").click(function () {
                $("p").hide(3000,function(){alert("this paragraph is hidden")});
                // alert("this paragraph is hidden")
            })
        })
    </script>
    <button>Hide</button>
    <p>this is our paragraph which should be hide</p>
</body>

</html>
<!-- ,function(){alert("this paragraph is hidden")} -->
