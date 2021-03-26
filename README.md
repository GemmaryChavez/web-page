<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ELEC1 Webpage</title>

    <style>
        *{
            margin: 0;
            padding: 0;
        }
        header {
            background-color: rgb(0, 0, 0);
            box-shadow: rgb(102, 102, 102) 0px 2px 20px;
            height: 80px;
            overflow: hidden;
        }
        header h1 {
            color: white;
            font-family: Arial, Helvetica, sans-serif;
            display: inline-block;
            margin-left: 10%;
            padding: 20px 20px 20px 20px;
        }
        ul {
            display: inline-block;
            float: right;
            margin-right: 10%;
        }
        ul li {
            float: left;
            padding: 30px 5px ;
            list-style: none;
        }
        ul li:hover {
            padding: 32px 5px;
            box-shadow: inset whitesmoke 0px 3px;
            transition: linear 0.15s;
        }
        ul li a {
            text-decoration: none;
            color: whitesmoke;
            font-weight: bold;
            font-family: Arial, Helvetica, sans-serif;
            font-size: 13px;
            padding: 30px;
        }
        ul li a:hover {
            color: rgb(199, 191, 117);
        }
        h1.marqueeh1{
            background-color: black;
            color: whitesmoke;
            margin-top: 10px;
            padding: 15px 10px 10px 10px;
            font-family: Arial, Helvetica, sans-serif;
            box-shadow: rgb(102, 102, 102) 0px 2px 20px;
            text-shadow: 0 0 10px rgb(141, 216, 185);
        }
        .wrapper {
            margin-left: 10%;
            margin-right: 10%;
        }
        p {
            font-family: Arial, Helvetica, sans-serif;
            line-height: 30px;
            padding: 10px 10px 10px 10px;
            text-align: justify;
            text-indent: 2em;
        }
        .button {
            background-color: rgb(180, 180, 180);
            color: rgb(0, 0, 0);
            padding: 15px 32px;
            text-align: center;
            text-decoration: none;
            display: inline-block;
            font-size: 16px;
            margin: 4px 2px;
            cursor: pointer;
            font-family: Arial, Helvetica, sans-serif;
        }
        .button:hover {
            background-color: #4CAF50;
            color: white;
            transition: ease-in-out 0.10s;
        }


    </style>


</head>
<body>
    <header>
        <h1>
            ELEC1 WEBPAGE PROJECT
        </h1>

        <!---ETO YUNG NAVIGATION-->

        <ul>
            <li><a href="index.html">HOME</a></li>
            <li><a href="members.html">MEMBERS</a></li>
        </ul>
    </header>

<!---ITO YUNG MAIN BODY-->

    <h1 class="marqueeh1">
        <marquee scrollamount="15">AUTOBIOGRAPHY</marquee>
    </h1>

    <br>
    <br>
    <br>
    <br>
<!--ETO YUNG TEXT SA LOOB HAHAHA-->
    <div class="wrapper">
       <p>
            Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.
       </p>
       <br>
       <br>
       <br>
       <a class="button" href="members.html">Next</a>
    </div>

</body>
</html>
