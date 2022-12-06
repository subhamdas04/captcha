<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Captcha Validation</title>
    <script src="https://code.jquery.com/jquery-3.6.1.min.js" integrity="sha256-o88AwQnZB+VDvE9tvIXrMQaPlFFSUTR+nldQm1LuPXQ=" crossorigin="anonymous"></script>
    <script src="https://kit.fontawesome.com/dd09a4070a.js" crossorigin="anonymous"></script>
    <style type="text/css">
        .main{
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            width: 300px;
            height: auto;
            border: 1px solid red;
            border-radius: 10px;
        }
        .captcha{
            display: flex;
            flex-direction: row;
            align-items: center;
            justify-content: center;
            width: 95%;
            height: 80px;
            border: 1px solid red;
        }
        .child1{
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            width: 80%;
            height: 100%;
            font-size: 40px;
            background: #888;
            color: #fff;
            font-family: 'Bungee Spice', cursive;
        }
        .child2{
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            width: 20%;
            height: 100%;
            font-size: 40px;
            color: blue;
            cursor: pointer;
        }
        .textbox{
            width: 95%;
            height: 30px;
            border: 1px solid salmon;
            border-radius: 10px;
            margin-top: 20px;
        }
        .btn{
            width: 96%;
            height: 30px;
            margin-top: 20px;
            border-radius: 10px;
            border: 0;
            outline: none;
            background: blue;
            color: white;
            margin-bottom: 20px;
            cursor: pointer;
        }
        .btn:active{
            background: black;
        }
    </style>
</head>
<body>
    <center>
        <div class="main">
            <h2>Captcha Validation</h2>
            <div class="captcha">
                <div class="child1"></div>
                <div class="child2" id="btn"><i class="fa-sharp fa-solid fa-rotate-right"></i></div>
            </div>
            <input type="text" name="valid" placeholder="Enter Captcha" class="textbox">
            <button class="btn" onclick="validateFun()">Validate</button>
        </div>
    </center>

    <script type="text/javascript">
        $(document).ready(function(){
            $.ajax({
                type: "GET",
                url: "captcha.php",
                success: function(data){
                    document.getElementsByClassName("child1")[0].innerHTML = data;
                }
            });
        });
    </script>
    
    <script type="text/javascript">
        $(document).ready(function(){
            $('#btn').click(function(){
                $.ajax({
                    type: "GET",
                    url: "captcha.php",
                    success: function(data){
                        document.getElementsByClassName("child1")[0].innerHTML = data;
                    }
                });
            });
        });
    </script>

    <script type="text/javascript">
        function validateFun(){
            var a = document.getElementsByClassName("child1")[0].innerHTML;
            var b = document.getElementsByName("valid")[0].value;

            if(a == b){
                alert("Validated Successfully");
            }else{
                alert("Failed to validate");
                location.reload();
            }
        }
    </script>

</body>
</html>