# bcrec_webpage
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        * {
            margin: 0;
            /* padding: 0; */
        }

        nav {
            background-color: rgb(6, 6, 128);
            color: white;
            height: 35px;

            display: flex;
            justify-content: space-around;
            align-items: center;
        }

        .logo ul {
            display: flex;
            gap: 20px;

        }

        .logo ul li {
            list-style: none;

        }

        .right ul {
            display: flex;
            gap: 10px;
        }

        .right ul li {
            list-style: none;
        }

        span {
            color: rgb(6, 6, 128);
            font-size: 150%;
            display: flex;
            justify-content: space-around;
            align-items: center;
        }

        .top {
            transform: translateY(25%) translateX(6%);

        }

        .topc {
            background-color: gainsboro;
            height: 35px;
            width: 1550px;
            margin: 10px;
            /* padding: 30px; */

            display: flex;
            justify-content: space-around;
            align-items: center;
        }

        .topc ul {
            display: flex;
            gap: 10px;
        }

        .topc ul li {
            list-style: none;
        }

        /* .hedder3{
            background-color: rgb(158, 43, 43);
        
            /* background-color: rgb(6, 6, 128); */
        /* color: white;
            height: 35px;

            display: flex;
            justify-content: space-around;
            align-items: center;
        }
        .hedder4{
            display: flex;
        }
        .hedder4 ul li {
            list-style: none;

        } */
        main {
            background-color: rgb(6, 6, 128);
            color: white;
            /* width: 900px; */
            height: 35px;

            display: flex;
            justify-content: space-around;
            align-items: center;
        }

        .hedder3 ul {
            display: flex;
            gap: 20px;


        }

        .hedder3 ul li {
            list-style: none;

        }

        .hedder4 ul {
            display: flex;
            gap: 10px;
        }

        .hedder4 ul li {
            list-style: none;
        }

        .me {
            height: 700px;
            width: 1550px;
            object-fit: cover;
        }

        .meee {
            position: absolute;

            animation-name: slide-in;

            animation-duration: 10s;
            animation-iteration-count: infinite;
            animation-direction: alternate;
            animation-timing-function: ease-out;
        }

        @keyframes slide-in {
            0% {
                transform: translate(-1560px);
            }

            100% {
                transform: translate(-1px);
            }
        }

        .aiml {
            height: 700px;
            width: 1550px;
            object-fit: cover;

        }

        .aimlll {
            /* position: relative; */
            animation-name: slide-out;

            animation-duration: 10s;
            animation-iteration-count: infinite;
            animation-direction: alternate;

            animation-timing-function: ease-out;
        }

        @keyframes slide-out {
            0% {

                transform: translate(1px);

            }

            100% {

                transform: translate(1560px);
            }

        }

        .container {
            display: flex;
            justify-content: space-around;
            align-items: center;
        }

        navr {
            display: flex;
            justify-content: space-around;
            align-items: center;
        }

        .navr ul {
            display: flex;

        }

        .navr ul li {
            list-style: none;
        }

        .myphoto {
            /* margin: 3px; */
            height: 190px;
            width: 180px;
            filter: contrast(1.6);
            transition: 1s;

        }

        .myphoto:hover {
            height: 200px;
            width: 190px;
            box-shadow: 5px 15px 15px rgb(228, 196, 196);


        }

        .card {
            margin: 40px;
            padding: 20px;
            background-color: rgb(6, 6, 128);
            width: 644px;
            height: 250px;
            border-radius: 7px;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;


        }

        .read {
            border: 2px solid black;
            width: 80px;
            padding: 8px;
            border-radius: 9px;
            background-color: rgb(6, 6, 128);
            color: white;
        }

        latter {
            display: flex;
            align-items: center;
            justify-content: center;
            /* min-height: 100vh; */
            /* background: #343F4F; */
            background: white;
        }

        .wrapper {
            /* display: inline-flex; */

        }

        .wrapper .static-txt {
            /* color: #fff; */
            font-size: 36px;
            /* font-weight: 400; */
        }

        .wrapper .dynamic-txts {
            margin-left: 0px;
            height: 58px;
            line-height: 58px;
            /* background: red; */
            overflow: hidden;

        }

        .dynamic-txts li {
            list-style: none;
            font-size: 16px;
            font-weight: 400;
            color: orangered;
            position: relative;
            /* top: 1110; */

            animation: slide 0s steps(1) infinite;
        }

        @keyframes slide {
            100% {
                top: -360px;
            }

        }

        .dynamic-txts li span {
            position: relative;
        }

        .dynamic-txts li span::after {
            content: "";
            left: 0;
            position: absolute;
            background: white;
            height: 40%;
            width: 100%;
            border-left: 2px solid orangered;
            animation: typing 6s steps(40) infinite;
        }

        @keyframes typing {
            100% {
                left: 100%;
                margin: 0 -35px 0 35px;

            }

        }

        .readmore {
            border: 2px solid black;
            /* margin: 10%; */
            width: 80px;
            padding: 8px;
            border-radius: 9px;
            background-color: red;
            color: white;
        }

        .d {
            margin: 3ex;
            color: white;
            transition: 1s;
        }

        .d:hover {
            color: yellow;
            box-shadow: 5px 15px 15px rgb(0, 0, 0);

        }

        .lineb {
            margin: 10px;
            height: 2px;
            width: 630px;
            background-color: white;
        }

        .corner {
            color: white;
        }

        .welcome {
            height: 4px;
            width: 50px;
            background-color: rgb(6, 6, 128);
            /* margin: 10%; */
        }

        .bcrec {
            margin: 60px;
        }

        navp ul {
            /* margin: 10%; */
            display: flex;
            justify-content: center;
            align-items: center;
            padding: 80px;
            background-color: rgb(239, 239, 245);
            /* border: 2px solid black; */
            gap: 25px;

        }

        /* ul li{ */
        /* padding: 90px; */
        /* display: inline; */
        /* border: 2px solid rgb(227, 216, 216); */
        /* border-radius: 10px; */

        /* height: 100px; */
        /* width: 320px; */
        /* display: flex; */
        /* justify-content: center; */
        /* align-items: center; */

        /* margin: 2px; */
        /* height: 150px; */
        /* width: 360px; */
        /* padding: 60px; */

        /* } */
        navp ul li {
            list-style: none;
            height: 110px;
            /* width: 2000px; */
            border: 2px solid rgb(236, 224, 224);
            padding: 80px;
            border-radius: 10px;
            display: flexbox;
            justify-content: center;
            align-items: center;
        }

        .Programmes {
            display: flex;
            justify-content: center;
            align-items: center;
            position: relative;
            top: 100px;
            transition: 1s;


        }

        .Programmes:hover {
            transform: scale(1.1);
        }

        .linee {
            height: 4px;
            width: 250px;
            background-color: black;
            margin: 100px;

        }

        Programmeee {
            background-color: rgb(242, 207, 207);

            /* padding: px; */
            /* padding: px; */
            /* position: relative; */
            position: absolute;
            /* margin: 50px; */
            display: flex;
        }


        .cardf {
            background-color: white;
            height: 650px;
            border-radius: 7px;
            padding: 9px;
            margin: 4px;
            box-shadow: 5px 15px 15px gold;
            transition: 0.8s;
        }

        .cardf:hover {
            box-shadow: 5px 15px 15px rgb(7, 107, 141);
            padding: 25px;
        }

        .carddf {
            background-color: white;
            height: 650px;
            border-radius: 7px;
            padding: 9px;
            margin: 4px;
            /* position: ab; */
            box-shadow: 5px 15px 15px gold;
            transition: 0.8s;
        }

        .carddf:hover {
            box-shadow: 5px 15px 15px rgb(7, 107, 141);
            padding: 25px;
        }



        .name {
            height: 40px;
            background-color: rgb(6, 6, 128);
            color: white;
            border-radius: 7px;
            text-align: center;
            /* margin: ; */
            display: flex;
            justify-content: center;
            align-items: center;
        }

        .imageee {
            padding: 25px;
        }

        .imageee img:hover {
            border-radius: 50%;
        }

        .imageee img {
            border-radius: 9px;
            transition: 1s;
        }

        .contenttt {
            padding: 7px 14px;
            /* font-family: 'Poppins', sans-serif; */
        }

        .contenttt p {
            font-size: 15px;
            color: gray;
            transition: 1s;
        }

        p:hover {
            color: blue;
        }

        .capsulesss {
            padding: 0 28px 0 44px;
            /* border: 1px solid gray; */

        }

        .capsulesss span {
            border: 1px solid gray;
            padding: 0px 6px;
            border-radius: 7px;
            font-size: 8px;
            font-family: 'Baloo Bhai 2', sans-serif;

        }

        .buttonnn {
            text-align: center;
        }

        .buttonnn button {
            padding: 7px 15px;
            border-radius: 15px;
            background-color: rgb(192, 219, 244);
            color: rgb(14, 150, 234);
            font-size: 10px;
            /* margin-top: 7px; */
            border: none;
            font-weight: bold;
            cursor: pointer;
            transition: 1s;
        }

        .buttonnn button:hover {
            background-color: rgb(0, 5, 8);
            color: rgb(10, 136, 214);
        }

        mainnn {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 95vh;
            /* margin: 50px; */
            gap: 70px;
            position: absolute;
            right: 35px;
            top: 800px;

            /* box-shadow: 5px 15px 15px gold; */
        }

        .o {
            /* display: flex; */
            height: 100px;
            width: 100px;
            position: relative;
            bottom: 50px;
            left: 100px;
            object-fit: cover;
            border-radius: 50px;
            /* box-shadow: 5px 15px 15px gold; */
            transition: 1s;
        }

        .o:hover {
            height: 110px;
            width: 110px;
            box-shadow: 5px 15px 15px black;

        }

        .newlogo {
            position: relative;
            height: 500px;
            top: 50px;
            width: 300px;
            border-radius: 10px;
            border: 2px solid black;
            box-shadow: 5px 15px 15px gold;
        }

        .sa {
            position: relative;
            height: 500px;
            top: 50px;
            width: 300px;
            border-radius: 10px;
            box-shadow: 5px 15px 15px gold;
            border: 2px solid black;

        }

        .vi {
            position: relative;
            height: 500px;
            top: 50px;
            width: 300px;
            border-radius: 10px;
            box-shadow: 5px 15px 15px gold;
            border: 2px solid black;
        }

        .de {
            position: relative;
            height: 500px;
            top: 50px;
            width: 300px;
            border-radius: 10px;
            box-shadow: 5px 15px 15px gold;
            border: 2px solid black;

        }

        .sinha {
            text-align: center;
            position: relative;
            bottom: 40px;
        }

        .texttt {
            margin: 15px;
            transition: 1s;
        }

        .texttt:hover {
            color: red;

        }

        .videoo {
            height: 760px;
            width: 1500px;
            background-color: rgb(11, 11, 99);
            display: flex;
            /* padding: 0vh; */
            /* justify-content: center; */
            align-items: center;
            /* position: relative; */
            position: absolute;
            top: 1700px;
            /* right: px; */
            left: 20px;

        }

        .vid {
            height: 600px;
            width: 700px;
            margin: 80px;
            /* object-fit: cover; */
            transition: 1s;

        }

        .vid:hover {
            height: 700px;
            width: 900px;

        }

        .Apply {
            color: white;
            margin: 40px;
        }

        .ApplyNow {
            /* height: 25px; */
            /* width: 100px; */
            /* border: 2px solid beige; */
            /* align-items: center; */
            /* margin: 9px; */
            border: 2px solid black;
            width: 80px;
            padding: 8px;
            border-radius: 9px;
            background-color: white;
            color: blue;
            transition: 1s;
        }

        .ApplyNow:hover {
            background-color: red;
            color: white;
        }

        .ccc {
            margin: 5%;
        }

        .lineeee {
            width: 20%;
            height: 5px;
            background-color: rgb(34, 34, 150);
        }

        .UPCOMING {
            height: 40px;
            width: 700px;
            background-color: black;
            color: white;
            border-radius: 10px;
            margin: 10px;
        }

        aa {
            display: flex;
            margin: 10px;
            height: 160px;
            width: 700px;

            border-radius: 10px;
            border: 2px solid rgb(190, 170, 170);

        }

        .ii {
            margin: 20px;
            width: 30%;
            border: 2px solid rgb(190, 170, 170);
            border-radius: 10px;
            /* margin: 10px; */

        }

        .THU {
            background-color: black;
            color: white;
            /* justify-content: center; */
            margin: 2px;
            border-radius: 10px;

        }

        .gg {
            color: rgb(41, 41, 160);
        }

        .pp {
            margin: 20px;
            font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
        }

        .tt {
            font-size: 15px;
            margin: 10px;
        }

        nn {
            /* margin: 20%; */
            /* border: 2px solid black; */
            display: flex;
        }

        .ss {
            display: flex;
            /* align-items: center; */
            /* justify-content: space-around; */
            /* flex-direction: column; */
            border: 2px solid;
            /* padding: 10px; */
            height: 40px;
            width: 700px;
            background-color: black;
            color: white;
            border-radius: 10px;
            margin: 10px;

        }

        .zz {
            font-size: 15px;
            margin: 10px;

        }

        /* mmm {
             margin: 10; 
        } */
        .rrr {
            display: flex;
            justify-content: center;
            align-items: center;
        }

        events {
            position: absolute;
            top: 380%;
            right: 1%;
        }

        .imageeeeee {
            position: absolute;
            top: 3200px;
            left: 20px;

        }


        .oooa {
            display: flex;
            justify-content: space-around;
            align-items: center;

        }

        .ooa {
            height: 5px;
            width: 100px;
            background-color: black;
            /* margin: 10px; */
            /* position: absolute; */


        }

        foot {
            position: absolute;
            top: 3700px;
            left: 45%;
        }



        imggg {
            display: flex;
            justify-content: center;
            align-items: center;
            /* height: 30px;width: 607px; */
            /* gap: 50px; */
            position: absolute;
            top: 3800px;
            left: 7%;
        }

        .opp {
            height: 100px;
            margin: 20px;
            border: 2px solid rgb(180, 171, 171);
            border-radius: 10px;
        }

        imgggg {
            display: flex;
            justify-content: center;
            align-items: center;
            /* height: 30px;width: 607px; */
            /* gap: 50px; */
            position: absolute;
            top: 3950px;
            left: 47%;
        }

        .op {
            height: 10px;
            width: 10px;
            margin: 20px;
            background-color: rgb(137, 130, 130);
            /* border: 2px solid rgb(43, 40, 40); */
            border-radius: 10px;
            transition: 1s;
        }

        .op:hover {
            background-color: black;
            height: 15px;
            width: 15px;
        }

        footer {
            position: absolute;
            top: 4200px;
            left: 0%;
            /* width: 10%; */
        }

        .last {
            width: 100%;
        }
    </style>
</head>

<body>
    <header>
        <nav>
            <div class="logo">
                <ul>
                    <li><img src="/img/f.png" alt=""></li>
                    <li><img src="/img/t.png" alt=""></li>
                    <li><img src="/img/y.png" alt=""></li>
                    <li><img src="/img/i.png" alt=""></li>
                </ul>
            </div>
            <div class="right">
                <ul>
                    <li>News</li>
                    <li>|</li>
                    <li>Events</li>
                    <li>|</li>
                    <li>Notice Board</li>
                    <li>|</li>
                    <li>Alumni</li>
                    <li>|</li>
                    <li>Approval/Accreditation</li>
                    <li>|</li>
                    <li>IQAC</li>
                    <li>|</li>
                    <li>Feedback </li>
                    <li>|</li>
                    <li>Gallery </li>
                    <li>|</li>
                    <li>Disclosure </li>
                    <li>|</li>
                    <li>Collaboration </li>
                    <li>|</li>
                    <li>Download </li>
                    <li>|</li>
                    <li>Sign Up</li>

                    <!-- <img src="/img/logo.png" alt=""> -->


                </ul>
            </div>
        </nav>
        <div class="header1">
            <span>
                <div class="top">
                    <img height="75px" src="/img/logo.png" alt="">

                </div>
                <div class="tpoB">
                    <img height="40px" src="/img/call-icon.gif" alt="">
                    <b>CALL US
                        <br>(0343)-2501353,2504106
                        <br>Mob: +91-6297128554 | Email: info@bcrec.ac.in
                    </b>
                </div>
        </div>
        <div class="topc">
            <ul>
                <li>HOME</li>
                <li>
                    ABOUT </li>
                <li> DEPARTMENTS
                </li>
                <li> ACADEMICS
                </li>
                <li>INFRA STRUCTURE
                </li>
                <li>ADMISSIONS
                </li>
                <li>EXAMINATION
                </li>
                <li> TRAINING & PLACEMENT
                </li>
                <li>LIBRARY
                </li>
                <li>CAREERS
                </li>
                <li>CONTACT US</li>
            </ul>
        </div>
        </span>
        <main>
            <div class="hedder3">
                <ul>
                    <li>
                        Highlights
                    </li>
                </ul>
            </div>
            <div class="hedder4">
                <ul>
                    <li>ons are invited for the post of Professor/Associate Professor </li>
                    <li>|</li>
                    <li> Form fill-up for Regular and
                        Backlog Students </li>
                    <li>|</li>
                    <li>Applications are invited for the post of Professor/Associate Professor</li>
                </ul>
            </div>
            </div>
        </main>
        <mainphoto>
            <div class="meee">
                <img class="me" src="/img/photo_2023-12-11_16-38-05.jpg" alt="">
            </div>
            <div class="aimlll">
                <img class="aiml" src="/img/AIML.jpg" alt="">
            </div>
        </mainphoto>
        </div>

    </header>
    <nava>
        <div class="navr">
            <ul>
                <li class="berec"><br>
                    <br>
                    <br>
                    <h1>Welcome to BCREC</h1>
                    <div class="welcome"></div>
                    <latter>
                        <div class="wrapper">
                            <div class="static-txt"></div>
                            <ul class="dynamic-txts">
                                <li><span>Website desiner : Subhadip Sinha</span></li>
                                <!-- <li><span>SUBHADIP</span></li>
                                <li><span>KHOKON</span></li>
                                <li><span>SINHA</span></li> -->
                            </ul>
                        </div>
                    </latter>
                    <br>
                    When you go on that mission to upgrade yourself, to become the 2.0 version of yourself, to become
                    the next highest version of the man that you're meant to be, that is threatening, that is scary to
                    the people around you. For two reasons, one, they don't know this version of you anymore.They can't
                    relate to you.Number two, they see their shortcomings, because they know that they ought to be
                    levelingup, they ought to be trying harder, they ought to be doing more, but they're not.
                    <br>
                    <br>
                    <div class="read">
                        read More
                    </div>

                </li>
                <li>
                    <div class="card">
                        <div class="cardA">
                            <h2 class="corner">Principal's Corner </h2>
                            <div class="lineb"></div>
                        </div>

                        <div class="cardB">
                            <ul>
                                <li>
                                    <img class="myphoto" src="/img/me.jpg" alt="">
                                </li>
                                <li class="d">
                                    <b> Lorem ipsum dolor, sit amet consectetur adipisicing elit. Dolor, qui soluta?
                                        Atque dolores officiis dolorum dignissimos eveniet amet eligendi fugit,
                                        laboriosam vero. Veniam recusandae officia at non fuga quod autem. </b>.



                                    <br>
                                    <br>
                                    <br>
                                    <div class="readmore">
                                        read More
                                    </div>
                                </li>

                        </div>
            </ul>
        </div>
        </li>
        </ul>
        </div>

    </nava>
    <navp>
        <ul>
            <li><img src="/img/Placement.png" alt=""><br> Ouar Vision </li>
            <li><img src="/img/Departments.png" alt=""><br>Online Application</li>
            <li><img src="/img/Facilities.png" alt=""> <br>Faculties</li>
            <li><img src="/img/Courses.png" alt=""><br>Placement</li>
        </ul>
    </navp>
    <div class="Programmes">
        <h1>BOARD OF DIERECTORS</h1>

    </div>
    <center>
        <div class="linee"></div>
    </center>
    <Programmeee>
        <div class="cardf">
            <div class="name">SUBHADIP SINHA</div>
            <div class="imageee">
                <img width="300" src="/img/photo_2023-12-11_17-03-22.jpg" alt="">
            </div>

            <div class="capsulesss">
                <spa>Insta id:-</spa>

            </div>
            <div class="contenttt">
                <h2>@subhadip___sinha__</h2><br>
                <p>
                <h5>
                    <li>FULL STACK DEVELOPER</li>
                    <li>Lorem, ipsum dolor.</li>
                </h5>
                </p>
            </div>
            <div class="buttonnn">
                <button>Read More</button>
            </div>

        </div>

        <div class="cardf">
            <div class="name">KUMAR SAURAV</div>
            <div class="imageee">
                <img width="300" src="/img/saurav.jpg" alt="">
            </div>

            <div class="capsulesss">
                <spa>Insta id:-</spa>

            </div>
            <div class="contenttt">
                <h2>@suaraav__288</h2><br>
                <p>
                <h5>
                    <li>GYM LOVER</li>

                    <li>Lorem, ipsum dolor.</li>

                </h5>
                </p>
            </div>
            <div class="buttonnn">
                <button>Read More</button>
            </div>

        </div>

        <div class="cardf">
            <div class="name"> VISHWAJIT KUMAR </div>
            <div class="imageee">
                <img width="300" src="/img/vishajit.jpg" alt="">
            </div>

            <div class="capsulesss">
                <spa>Insta id:-</spa>

            </div>
            <div class="contenttt">
                <h2>@vishwajitkanth</h2><br>
                <p>
                <h5>
                    <li>BEGINNER DEVELOPER</li>
                    <li>Lorem, ipsum dolor.</li>

                </h5>
                </p>
            </div>
            <div class="buttonnn">
                <button>Read More</button>
            </div>

        </div>
        <div class="carddf">
            <div class="name">DEVESH JHA</div>
            <div class="imageee">
                <img width="300" src="/img/devish.jpg" alt="">
            </div>

            <div class="capsulesss">
                <spa>Insta id:-</spa>

            </div>
            <div class="contenttt">
                <h2>@devesh_._jha</h2><br>
                <p></p>
                <h5>
                    <li>HOOPER, ATHLETE</li>
                    <li>Lorem, ipsum dolor.</li>

                </h5>
            </div>
            <div class="buttonnn">
                <button>Read More</button>
            </div>
    </Programmeee>

    <mainnn>
        <div class="newlogo">
            <img class="o" src="/img/subha.jpg" alt="">
            <div class="sinha">
                <h2>SUBHADIP</h2>
            </div>
            <div class="texttt">
                <ul>
                    <li>
                        <h3>Khubsurat ladkiyon ka khwab lekar engineering college mein jaate Hain per 4 sal ke bad sapne
                            mein code aur error najar aate Hain ..</h3>
                    </li>
                </ul>
            </div>
        </div>

        <div class="sa">
            <img class="o" src="/img/sa.jpg" alt="">
            <div class="sinha">
                <h2>SAURAV</h2>
            </div>
            <div class="texttt">
                <ul>
                    <li>
                        <h3>Engineers marte nahi..
                            zinda dafnaaye jaate hain..
                            har 6 mahino mein tadpaaye jaate hain..
                            kafan khol ke dekho..
                            to woh kabr mein bhi assignment likhte paaye jaate hain..</h4>
                        </h3>
                    </li>
                </ul>
            </div>
        </div>
        <div class="vi">
            <img class="o" src="/img/vi.jpg" alt="">
            <div class="sinha">
                <h2>VISWHAJIT</h2>
            </div>
            <div class="texttt">
                <ul>
                    <li>
                        <h3>
                            Centuries ago people who sacrificed their
                            sleep, food, laughter & other joys of life
                            were called “SAINTS”
                            Now they are called ENGINEERS.</h3>
                    </li>
                </ul>
            </div>
        </div>
        <div class="de">
            <img class="o" src="/img/de.jpg" alt="">
            <div class="sinha">
                <h2>DEVESH</h2>
            </div>
            <div class="texttt">
                <ul>
                    <li>
                        <h3>
                            Engineering studies are like a public toilet.
                            People standing outside are very anxious as to when they will get a chance to go inside.
                            On the other hand, the people sitting inside are dying to go out.
                        </h3>
                    </li>
                </ul>
            </div>
        </div>
    </mainnn>

    <div class="videoo">
        <div class="video"><video class="vid" src="/video/video.mp4" controls></video></div>
        <div class="Apply">
            <h1>Apply for Admission</h1>
            <br><br>

            Lorem ipsum dolor sit amet consectetur adipisicing elit. Assumenda, labore.
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Assumenda, labore.
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Assumenda, labore.
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Assumenda, labore.
            <br>
            <br>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Assumenda, labore.
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Assumenda, labore.

            <br><br>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Optio, alias!
            <br><br>

            <br>
            <div class="ApplyNow">Apply Now</div>
        </div>
    </div>

    <events>
        <center class="ccc">
            <div class="eventsss">
                <h1>Our Latest Events & News</h1>

                <div class="lineeee"></div>
            </div>
        </center>
        <cen class="rrr">
            <mmm>
                <nn class="mmmm">
                    <hello>
                        <div class=" UPCOMING">UPCOMING EVENTS </div>
                        <aa>
                            <div class="ii">
                                <center>
                                    <div class="THU"> THU</div><br>NOVEMBER <br> 2023
                            </div>
                            </center>
                            <div class="pp">
                                <div class="gg">
                                    Quiz Contest
                                </div>
                                <h1>
                                    Quiz Contest Organized by First year Students
                                </h1>
                            </div>
                        </aa>
                        <div class="tt">
                            <b>
                                Upcoming Events | View Calendar
                            </b>
                        </div>
                    </hello>
                    <div class="ff">
                        <div class="ss">RECENT NEWS</div>

                        <div class="zz"><b>
                                Recent News | View News
                            </b>

                        </div>
                    </div>

                </nn>

            </mmm>

        </cen>

    </events>

    </div>
    <div class="imageeeeee">
        <img width="100%" src="/img/Scree.png" alt="">

    </div>


    <foot>

        <div class="oooa">
            <h1>Our Recruiters</h1>
        </div>
        <center>
            <div class="ooa">
                </h1>
            </div>

        </center>
    </foot>
    <fooot>
        <imggg>
            <div>
                <img class="opp" src="/img/a.png" alt="">
            </div>
            <div> <img class="opp" src="/img/b.png" alt=""></div>
            <div> <img class="opp" src="/img/c.png" alt=""></div>
            <div> <img class="opp" src="/img/d.png" alt=""></div>
            <div> <img class="opp" src="/img/e.png" alt=""></div>
            <div><img class="opp" src="/img/ff.png" alt=""></div>

        </imggg>

    </fooot>
    <fooot>
        <imgggg>
            <div class="op">

            </div>

            <div class="op"> </div>
            <div class="op"></div>


        </imgggg>

    </fooot>
    <footer>
        <img class="last" src="/img/Screenshot 2023-12-13 180850.png" alt="">
    </footer>
</body>

</html>
