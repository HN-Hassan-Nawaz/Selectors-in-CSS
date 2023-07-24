<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CSS Selectors</title>
    <style>
        p{
            border: 2px solid red;
        }
        /* Id Selector */
        #firstpara{
            color: red;
        }

        /* Class Selector */
        .redelement{
            color:purple;
            background-color: yellow;
        }
        /* Grouping Selector */
        footer,span{
            color:rgb(209, 14, 14);
        }
    </style>
</head>
<body>
    <h1>CSS Selectors</h1>
    <p id="firstpara">This is a paragraph for Css Tutorial</p>
    <p id="secondpara" class="redelement bgblue">This is a another paragraph for Css Tutorial</p>

    <div>
        <p>This is a yet another paragraph for Css Tutorial</p>
        <span>This is a span</span>
    </div>
    <footer>This is a footer</footer>
</body>
</html># Selectors-in-CSS
