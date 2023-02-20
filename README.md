    <!DOCTYPE html>
    <html lang="en">

    <head>
        <meta charset="UTF-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Document</title>
        <style>
            body{
                background-color:plum;
            }
            #a {
                height: 500px;
                width: 500px;
                border: 1px solid;
                background-color: pink;
                /* text-align: center; */
                margin: 0 auto;
                padding-left: 100px;
            }
            #b{
                text-align: center;
            }
            #z{
                margin-left: 10px;
            }
            #pp{
                background-color: yellow;
            margin-left: 170px;
            width: 70px;
            }
        </style>
    </head>

    <body>
        <h1 id="b">Survey Form</h1>
        <div id="a">
            <form action="">
                <br>
                <label for="">Let know we can improve freecodecamp</label>
                <br>
                <br>
                
            <label for="">Name:</label>
            <input type="text" required>
                <br>
                <br>
                <label for="">Email:</label>
                <input type="email" name="" id="" required>
                <br>
                <br>
                <label for="" id="z">Age:</label>
                <input type="text">
                <br>
                <br>
        
                <label for="">Which option best describes your current role?</label>
                <select name="" id="">
                    <option value="">Student</option>
                    <option value="">Freshers</option>
                    <option value="">Expericence</option>
                </select>
                <br>
                    <br>
                <label for="">How likely is that you would recommend  freecodecamp to a friend?</label>
                <br>
                <input type="radio" name="sona" id="">
                <label for="">Definitely</label>
                <br>
                <input type="radio" name="sona" id="">
                <label for="">Maybe</label>
                <br>
                <input type="radio" name="sona" id="">
                <label for="">Not sure</label>
                
                
                <br>
                <br>
                <label for="">Things should be improved in the future (Check all that apply):</label>
                <br>
                <input type="radio" name="p" id="">
                <label for="">Front-end project</label>
                <br>
                <input type="radio" name="p" id="">
                <label for="">Back-end project</label>
                <br>
                <input type="radio" name="p" id="">
                <label for="">Data Visualization</label>
                <br>
                <br>
                <br>
                <input type="submit" value="SUMIT" id="pp">
            </form>
        </div>
    </body>

    </html>
