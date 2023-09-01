<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>
    <div class="container">
        <div class="transition">
            <div class="cover cover3">
                hlio dosto tihs is about us page
                <div class="lallu">
                    <a href="">click</a>
                </div>
            </div>
        </div>
    </div>
    <div class="service-alert-content">
        <div class="content2">
            <h2>PAge Transition animation</h2>
            <a href="./about.html" class="link2">About us</a>
        </div>
    </div>
    
    <div class="service-alert-content">
        <div class="content2">
            <h2>PAge Transition animation</h2>
            <a href="./about.html" class="link3">About us</a>
        </div>
    </div>



    <script>
        const link = document.querySelector(".link2");
        const transition = document.querySelector(".cover3");
        link.addEventListener("click", (e) => {
            e.preventDefault();
            transition.classList.add("slide");
        });
    </script>
    <script>
        const link3 = document.querySelector(".link3");
        const transi = document.querySelector(".cover");
        link.addEventListener("click", (e) => {
            e.preventDefault();
            transi.classList.add("slide");
        });
    </script>

    <script>
        var rem = document.querySelector(".lallu");
        rem.addEventListener("click",function(){
            transition.classList.remove("slide");
        })
    </script>
</body>

</html>
