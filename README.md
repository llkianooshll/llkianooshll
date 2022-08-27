<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        h1 {
            outline: 5px solid black;
            border-radius: 50px;
            margin-left: 40%;
            margin-right: 40%;
            padding-left: 5px;
            padding-right: 5px;
            border: 2px solid dimgray;
            background-color: darkred;
        }
         p {
            background-color: honeydew;
            border: 4px solid black;
            border-radius: 50px;
            margin-left: 35%;
            margin-right: 35%;
            font-size: 25px;
         }

         * {
            text-align: center;

         }

         #d2:focus {
            background-color: black;
            color: whitesmoke

         }

         #d2 {
            margin-right: 40px;
            border-radius: 8px;
            border-color: gold;
         }
         #d3:focus {
            background-color: black;
            color: whitesmoke
         }
         #d3 {
            margin-top: 5px;
            margin-right: 40px;
            border-radius: 8px;
            border-color: gold;
         }
         #d4,#d5 {
            margin-top: 5px;
         }
         #d7{
            margin-top: 5px;
            margin-right: 30px;
            border-radius: 8px;
            border-color: rgb(255, 0, 76);
         }
         #d7:focus{
            background-color: black;
            color: whitesmoke;

         }

    </style>
</head>
<body id="j2">

    <h1>hello Mr! </h1>
    <p>welcome to website</p>
    <h1 id="z2">enter the details!</h1>
         <label for="d2">Fname</label>
        <input id="d2" type="text"><br>
        <label for="d3">Lname</label>
        <input id="d3" type="text"><br>
        <label for="d7">email</label>
        <input id="d7" type="email"><br>
        <label for="d4">male</label>
        <input id="d4" type="radio" name="gh">
        <label for="d5">female</label>
        <input id="d5" type="radio" name="gh">
        <input onclick="clickEvent()" id="d6" type="submit" value="send">
        <div><input type="checkbox"></div>



</body>
</html> 
