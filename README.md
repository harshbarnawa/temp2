<!DOCTYPE html>
<html>
<head>
    <title>Student Registration Form</title>

    <style>
        body{
            background:#ffe5e5;
            margin:0;
            padding:30px 0;
        }

        h1{
            text-align:center;
            font-family:Georgia;
            font-size:50px;
            margin-bottom:70px;
        }

        form{
            width:900px;
            margin:auto;
        }

        .row{
            display:flex;
            align-items:center;
            margin-bottom:28px;
        }

        .label{
            width:270px;
            font-family:Georgia;
            font-size:28px;
            flex-shrink:0;
        }

        input[type="text"],
        input[type="email"],
        input[type="password"],
        select{
            width:565px;
            height:43px;
            box-sizing:border-box;
            font-size:18px;
        }

        .name{
            width:270px !important;
        }

        .date{
            width:86px !important;
        }

        .year{
            width:140px !important;
        }

        .code{
            width:65px !important;
        }

        .mobile{
            width:480px !important;
        }

        .dash{
            font-size:25px;
            margin:0 10px;
        }

        .dob-note{
            font-family:Georgia;
            font-size:25px;
            font-style:italic;
            margin-left:10px;
        }

        .gender,
        .department{
            font-family:Georgia;
            font-size:25px;
        }

        input[type="radio"],
        input[type="checkbox"]{
            width:20px;
            height:20px;
            margin:0 8px 0 0;
        }

        .department input{
            margin-left:5px;
        }

        select{
            width:630px;
        }

        textarea{
            width:550px;
            height:125px;
            font-size:18px;
            resize:none;
        }

        input[type="file"]{
            font-size:18px;
        }

        button{
            display:block;
            margin:45px auto 0;
            padding:5px 12px;
            font-size:18px;
        }
    </style>
</head>

<body>

<h1>Student Registration Form</h1>

<form>

    <div class="row">
        <div class="label">Roll no. :</div>
        <input type="text">
    </div>

    <div class="row">
        <div class="label">Student name :</div>
        <input type="text" placeholder="First Name" class="name">
        <span class="dash">-</span>
        <input type="text" placeholder="Last Name" class="name">
    </div>

    <div class="row">
        <div class="label">Father's name :</div>
        <input type="text">
    </div>

    <div class="row">
        <div class="label">Date of birth :</div>
        <input type="text" placeholder="Day" class="date">
        <span class="dash">-</span>
        <input type="text" placeholder="Month" class="date">
        <span class="dash">-</span>
        <input type="text" placeholder="Year" class="year">
        <span class="dob-note">(DD-MM-YYYY)</span>
    </div>

    <div class="row">
        <div class="label">Mobile no. :</div>
        <input type="text" value="+91" class="code">
        <span class="dash">-</span>
        <input type="text" class="mobile">
    </div>

    <div class="row">
        <div class="label">Email id :</div>
        <input type="email">
    </div>

    <div class="row">
        <div class="label">Password :</div>
        <input type="password">
    </div>

    <div class="row">
        <div class="label">Gender :</div>

        <div class="gender">
            <input type="radio" name="gender"> Male
            <input type="radio" name="gender"> Female
        </div>
    </div>

    <div class="row">
        <div class="label">Department :</div>

        <div class="department">
            <input type="checkbox"> CSE
            <input type="checkbox"> IT
            <input type="checkbox"> ECE
            <input type="checkbox"> Civil
            <input type="checkbox"> Mech
        </div>
    </div>

    <div class="row">
        <div class="label">Course :</div>

        <select>
            <option>---------------- Select Current Course's ----------------</option>
            <option>B.Tech</option>
            <option>M.Tech</option>
            <option>BCA</option>
        </select>
    </div>

    <div class="row">
        <div class="label">Student photo :</div>
        <input type="file">
    </div>

    <div class="row">
        <div class="label">City :</div>
        <input type="text">
    </div>

    <div class="row">
        <div class="label">Address :</div>
        <textarea></textarea>
    </div>

    <button type="submit">Register</button>

</form>

</body>
</html>
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
