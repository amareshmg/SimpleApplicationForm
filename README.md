# SimpleApplicationForm
ASimpleApplicationFormByAMG
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <!-- <link rel="stylesheet" href="./ApplicationCSS.css"> -->
    <style>
        label{
    background-color: aqua;
}
div{
    border: 2px solid black;
    padding: 20px;
    background-color: antiquewhite;
    text-align: center;
}
h1{
    text-align: center;
    color: blue;
    border: 2px solid black;
    background-color: springgreen;
    
}
button{
    text-align: center;
    
    
}

    </style>
</head>
<body>
    <div>
    <form action="">
        <main>A_M_G</main>
        <marquee behavior="Ranganath" direction="right">AMG Group Of Companies</marquee>
        <marquee behavior="Ranganath" direction=" button">AMG Group Of Companies</marquee>
        <h1 > <u> :Application Form:</u></h1>
        <label for="">Name:</label>
        <input type="text" placeholder="enter ur name">
        <br><br>
        <label for="">USN :</label>
        <input type="text">
        <br><br>
        <label for="">DOB:</label>
        <input type="date">
        <br><br>
        <label for="">Ph num:</label>
        <input type="number">
        <br><br>
        <label for="">Email id:</label>
        <input type="email">
        <br><br>
        <label for="">Gender:</label>
        <input type="radio" name="a">Male
        <input type="radio" name="a">Female
        <input type="radio" name="a">others
        <br><br>
        <label for="">Qalification:</label>
        <select name="" id=""> 
            <option value="">Click here</option>
            <optgroup label="Technical">
            
            <option value="">BE</option>
            <option value="">BCOM</option>
        </optgroup>
        <optgroup label="Software">
            <option value="">MCOM</option>
            <option value="">MBA</option>
        </optgroup>
        </select>
        
        <br><br>
        <label for="">Year of passout:</label>
        <input type="number" min="2020" max="2023">
        
        <br><br>
        <label for="">Hobbies:</label>
        <input type="checkbox"> Programming
        <input type="checkbox"> Dancing
        <input type="checkbox"> Sleeping
        <input type="checkbox"> Cooking
        <br><br>
        <label for="">Tell me About Your Self:</label>
        <textarea placeholder="Write here..." name="name" id="" cols="30" rows="5" ></textarea>
        <br><br>
        <label for="">Upload your Resume here:</label>
        <input type="file">
        <br><br>
        <button>Submit</button>

        

    </form>
</div>


</body>

</html>
