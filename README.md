<!DOCTYPE html>
<html>
<head>
    <title>Student Registration Form</title>

    <style>
        body{
            background:#ffe5e5;
            margin:0;
            padding:25px 0;
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
            display:grid;
            grid-template-columns:270px 1fr;
            align-items:center;
            margin-bottom:28px;
        }

        label{
            font-family:Georgia;
            font-size:28px;
        }

        input[type="text"],
        input[type="email"],
        input[type="password"]{
            width:565px;
            height:43px;
            box-sizing:border-box;
            font-size:18px;
        }

        .name{
            width:270px !important;
        }

        .date{
            width:85px !important;
        }

        .year{
            width:140px !important;
        }

        .mobilecode{
            width:65px !important;
        }

        .mobile{
            width:480px !important;
        }

        .dash{
            margin:0 10px;
            font-size:22px;
        }

        .dob{
            display:flex;
            align-items:center;
        }

        .dob i{
            font-family:Georgia;
            font-size:24px;
            margin-left:10px;
        }

        .gender{
            font-family:Georgia;
            font-size:25px;
            white-space:nowrap;
        }

        .gender input{
            width:25px;
            height:25px;
            vertical-align:middle;
            margin-right:8px;
        }

        .department{
            display:flex;
            align-items:center;
            gap:8px;
            font-family:Georgia;
            font-size:25px;
            white-space:nowrap;
        }

        .department input{
            width:25px;
            height:25px;
            margin:0;
        }

        select{
            width:630px;
            height:45px;
            font-size:18px;
        }

        input[type="file"]{
            font-size:18px;
        }

        textarea{
            width:550px;
            height:125px;
            font-size:18px;
            resize:none;
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
        <label>Roll no. :</label>
        <input type="text">
    </div>

    <div class="row">
        <label>Student name :</label>

        <div>
            <input type="text" placeholder="First Name" class="name">
            <span class="dash">-</span>
            <input type="text" placeholder="Last Name" class="name">
        </div>
    </div>

    <div class="row">
        <label>Father's name :</label>
        <input type="text">
    </div>

    <div class="row">
        <label>Date of birth :</label>

        <div class="dob">
            <input type="text" placeholder="Day" class="date">
            <span class="dash">-</span>
            <input type="text" placeholder="Month" class="date">
            <span class="dash">-</span>
            <input type="text" placeholder="Year" class="year">
            <i>(DD-MM-YYYY)</i>
        </div>
    </div>

    <div class="row">
        <label>Mobile no. :</label>

        <div>
            <input type="text" value="+91" class="mobilecode">
            <span class="dash">-</span>
            <input type="text" class="mobile">
        </div>
    </div>

    <div class="row">
        <label>Email id :</label>
        <input type="email">
    </div>

    <div class="row">
        <label>Password :</label>
        <input type="password">
    </div>

    <div class="row">
        <label>Gender :</label>

        <div class="gender">
            <input type="radio" name="gender"> Male
            <input type="radio" name="gender"> Female
        </div>
    </div>

    <div class="row">
        <label>Department :</label>

        <div class="department">
            <input type="checkbox"> CSE
            <input type="checkbox"> IT
            <input type="checkbox"> ECE
            <input type="checkbox"> Civil
            <input type="checkbox"> Mech
        </div>
    </div>

    <div class="row">
        <label>Course :</label>

        <select>
            <option>---------------- Select Current Course's ----------------</option>
            <option>B.Tech</option>
            <option>M.Tech</option>
            <option>BCA</option>
        </select>
    </div>

    <div class="row">
        <label>Student photo :</label>
        <input type="file">
    </div>

    <div class="row">
        <label>City :</label>
        <input type="text">
    </div>

    <div class="row">
        <label>Address :</label>
        <textarea></textarea>
    </div>

    <button type="submit">Register</button>

</form>

</body>
</html>
