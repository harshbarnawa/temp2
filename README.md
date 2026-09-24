<!DOCTYPE html>
<html>
<head>
    <title>Student Registration Form</title>

    <style>
        body{
            background:#ffe5e5;
            font-family:Arial;
        }

        h1{
            text-align:center;
            font-family:Georgia;
            font-size:50px;
        }

        form{
            width:90%;
            margin:auto;
        }

        label{
            display:inline-block;
            width:270px;
            font-family:Georgia;
            font-size:28px;
            margin:15px 0;
        }

        input,select,textarea{
            width:550px;
            height:38px;
            font-size:18px;
            box-sizing:border-box;
        }

        .small{
            width:270px;
        }

        .date{
            width:85px;
        }

        .year{
            width:140px;
        }

        .code{
            width:65px;
        }

        textarea{
            height:120px;
        }

        input[type="radio"],
        input[type="checkbox"]{
            width:20px;
            height:20px;
        }

        button{
            display:block;
            margin:30px auto;
            padding:6px 15px;
            font-size:18px;
        }
    </style>
</head>

<body>

<h1>Student Registration Form</h1>

<form>

<label>Roll no. :</label>
<input type="text">

<label>Student name :</label>
<input type="text" placeholder="First Name" class="small">
-
<input type="text" placeholder="Last Name" class="small">

<label>Father's name :</label>
<input type="text">

<label>Date of birth :</label>
<input type="text" placeholder="Day" class="date">
-
<input type="text" placeholder="Month" class="date">
-
<input type="text" placeholder="Year" class="year">

<label>Mobile no. :</label>
<input type="text" value="+91" class="code">
-
<input type="text">

<label>Email id :</label>
<input type="email">

<label>Password :</label>
<input type="password">

<label>Gender :</label>
<input type="radio" name="gender"> Male
<input type="radio" name="gender"> Female

<label>Department :</label>
<input type="checkbox"> CSE
<input type="checkbox"> IT
<input type="checkbox"> ECE
<input type="checkbox"> Civil
<input type="checkbox"> Mech

<label>Course :</label>
<select>
    <option>Select Current Course</option>
    <option>B.Tech</option>
    <option>M.Tech</option>
    <option>BCA</option>
</select>

<label>Student photo :</label>
<input type="file">

<label>City :</label>
<input type="text">

<label>Address :</label>
<textarea></textarea>

<button type="submit">Register</button>

</form>

</body>
</html>
