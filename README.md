# flexbox


all code for flexbox revision


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Flexbox Tutorial</title>
    <style>
        .container{
            height: 544px; 
            width: 100%;
            border: 2px solid black;
            display: flex; /* Initialize the container as a flex box */
            
            /* Flex properties for a flex container */

            /* flex-direction: row; (Default value of flex-direction is row) */
            /* flex-direction: column;
            flex-direction: row-reverse;
            flex-direction: column-reverse; */
            

            /* flex-wrap: wrap; (Default value of flex-direction is no-wrap) */
            /* flex-wrap: wrap-reverse; */

            /* This is a shorthand for flex-direction: and flex-wrap: ;; */
            /* flex-flow: row-reverse wrap; */ 

            /* justify-content will justify the content in horizontal direction */
            /* justify-content: center; */
            /* justify-content: space-between; */
            /* justify-content: space-evenly; */
            /* justify-content: space-around; */

            /* justify-content will justify the content in vertical direction */
            /* align-items: center; */
            /* align-items: flex-end; */
            /* align-items: flex-start; */
            /* align-items: stretch; */ 
        }
        .item{
            width: 200px;
            height: 200px;
            background-color: tomato;
            border: 2px solid green;
            margin: 10px;
            padding: 3px;
        }

        #item-1{
            /* Flex properties for a flex item */
            /* Higher the order, later it shows up in the container */
            /* order: 2; */

            /* flex-grow: 2;
            flex-shrink: 2; */

        }
        #item-2{
            /* flex-grow: 3;
            flex-shrink: 3 ; */
            flex-basis: 160px;
            /* when flex-direction is set to row flex-basis: will control width */
            /* when flex-direction is set to column flex-basis: will control height */
        }
        #item-3{
            /* flex: 2 2 230px; */
            align-self: flex-start;
            align-self: flex-end;
            align-self: center;

            }

    </style>
</head>
<body>
    <h1>This is Flexbox Tutorial</h1>
    <div class="container">
        <div class="item" id="item-1">First Box</div>
        <div class="item" id="item-2">Second Box</div>
        <div class="item" id="item-3">Third Box</div>
        <!-- <div class="item" id="item-4">Fourth Box</div>
        <div class="item" id="item-5">Fifth Box</div>
        <div class="item" id="item-6">Sixth Box</div> -->
    </div>
</body>
</html>

