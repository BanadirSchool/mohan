
<html>
    <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    </head>
    <style>
        body{
            padding: 0;
            margin: 0;
            font-family: Verdana, Geneva, Tahoma, sans-serif;

        }
        Table{
            position:absolute;
            left: 50%;
            top: 50%;
            transform: translate(-50%,-50%);
            border-collapse: collapse;
            width: 800px;
            height: 200px;
            border: 1px solid white;
            box-shadow: 2px 2px 12px rgba(0, 0, 0, 0.2), -1px -1px 8px rgba(0, 0, 0, 0.2);

        }
        tr{
            transition: all .2s ease-in;
            cursor: pointer;
        }
        th{
            padding: 12px;
            text-align: left;
            border-bottom: 1px solid #ddd;

        }
        #header{
            background-color: rgba(0, 81, 255, 0.705);
            color: #ffffff;
        }
        h1{
            font-weight: 600;
            text-align: center;
            background-color: aqua;
            color: #ddd;
            padding: 10px 0px;
        }
        tr:hover{
            background-color: #ffffff;
            transform: scal(1.02);
            box-shadow: 2px 2px 12px rgba(0, 0, 0, 0.2), -1px -1px 8px rgba(0, 0, 0, 0.2);
        }
        /*media query*/
        @media only screen and (max-width: 768px) {
            table{
                width: 90%;
            }
            
        }
    </style>
    <body>
        <h1> hoverable Table</h1>
        <hr>
        <table>
            <tr id="BANADIR SCHOOL"> 
                <th> MAGACA</th>
                <th> MAADADA</th>
                <th> MARKS</th>
                <th> CELCELIS</th>
                

            </tr>
            <td> MOHAMED ABDULKADIR MOHAMED</td>
            <td> sOFTWARE ENG</td>
            <td> 100</td>
            <td> 99%</td>
            <tr>

            </tr>
        </tr>
        <td> johan</td>
        <td> johan</td>
        <td> johan</td>
        <td> johan</td>
        <tr>

       
    </tr>
    <td> johan</td>
    <td> johan</td>
    <td> johan</td>
    <td> johan</td>
    <tr>

   
</tr>
<td> johan</td>
<td> johan</td>
<td> johan</td>
<td> johan</td>
<tr>



        </table>
    </body>
</html>
    
