# responsive_form
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>International Relations Cell Registration-Portal</title>
</head>
<style>
    body,
    html {
        background-color: #78a7ba;
        height: 100%;
    }

    #section {

        height: auto;
        background: #78a7ba;
        display: flex;
        justify-content: center;
        align-items: center;

    }

    #form {
        height: 80%;
        flex: 1;
        max-width: 600px;
        background-color: #EFF0F1;
        border-radius: 10px;
        border: 1px solid #999;
        margin-top: auto;
        margin-bottom: auto;
    }

    .formhead {
        padding: 15px 0;
        border-bottom: 1px solid #cccccc;
    }

    .formhead h1 {
        font-size: 28px;
        text-align: center;
        color: #666;
    }

    .fbody {
        background: white;
        padding: 5px 10px;
    }

    .row {
        display: flex;
        flex-direction: row;
    }

    .rowelement {
        flex: 1;
        display: flex;
        flex-direction: column;
        margin: 10px 5px;
    }

    label {
        color: #181919;
        font-size: 14px;
        font-weight: 500;
    }

    input[type="text"],
    input[type="tel"],
    input[type="email"],
    input[type="date"],
    textarea {
        font-size: 16px;

        height: 30px;
        padding-left: 10px;
        padding-right: 10px;
        color: #666;
        border: 1px solid #d6d6d6;
        border-radius: 4px;
        background: white;
        outline: none;
    }

    #Hall,
    #Year,
    #Department,
    #Team,
    #url,
    #file {
        font-size: 16px;

        height: 30px;
        padding-left: 10px;
        padding-right: 10px;
        color: #666;
        border: 1px solid #d6d6d6;
        border-radius: 4px;
        background: white;
        outline: none;

    }

    @media only screen and (max-width: 600px) {
        .row {
            flex-direction: column;
        }

        #form {
            flex: 1;
            max-width: 300px;
            background-color: #EFF0F1;
            border-radius: 10px;
            border: 1px solid #999;
            margin-top: auto;
            margin-bottom: auto;
        }



        .btn {
            flex: 1;
        }

    }

    .ffooter {
        display: flex;
        justify-content: flex-end;
    }

    #footer {
        background-color: #bcf5e7;
        font-size: large;
        display: flex;
        color: #666;
        justify-content: center;
        margin-top: 5px;
        padding: 10px;
    }

    .btn {
        padding: 10px 20px;
        background-color: #1BBA93;
        font-size: 17px;
        border: none;
        border-radius: 5px;
        color: #bcf5e7;
        cursor: pointer;
        margin: 6px;
    }

    .head h1 {
        background-color: #bcf5e7;
        display: flex;
        color: #666;
        justify-content: center;
        margin-top: 10px;
    }

    .head {
        display: flex;
        flex-direction: column;
    }

    .head img {
        width: 100%;
    }
</style>

<body>

    <header class="head">
        <img src="https://scontent-bom1-1.xx.fbcdn.net/v/t31.18172-8/14991460_1953657791528581_937252996895244081_o.jpg?_nc_cat=106&ccb=1-7&_nc_sid=e3f864&_nc_ohc=3AGJidAoguEAX8fe13g&_nc_ht=scontent-bom1-1.xx&oh=00_AfAIOGHuhB7Pu8XWi2pXggYDYZ3iUWcunYR63HyuJMp4AA&oe=647AA429"
            alt="International Realtions Cell">
        <h1>International Relations Cell</h1>
        <link rel="icon" href="https://ircell.iitkgp.ac.in/static/ftp/images/logo.png">
    </header>

    <section id="section">
        <form id="form" class="bdr" action="registered students.html" method="get" enctype="multipart/form-data"
            target="_blank" autocomplete="on">

            <div class="formhead">
                <h1>Join International Relations Cell</h1>
            </div>
            <div class="fbody">
                <div class="row">
                    <div class="rowelement">
                        <label for="firstname">First Name:</label>
                        <input type="text" name="firstname" placeholder="First name" id="firstname" autofocus required>

                    </div>
                    <div class="rowelement">
                        <label for="middlename">Middle Name:</label>
                        <input type="text" name="middlename" placeholder="Middle name" id="middlename">

                    </div>
                    <!-- <div class="rowelement">
                        <label for="lastname">Last Name:</label>
                        <input type="text" name="lastname" placeholder="Last name" id="lastname">
                    </div> -->


                </div>
                <div class="row">
                    <div class="rowelement">
                        <label for="Roll Number">Roll Number:</label>
                        <input type="text" placeholder="Roll Number" id="Roll Number" name="Roll Number" required>
                    </div>

                    <div class="rowelement">
                        <label for="contact number">Contact Number:</label>
                        <input type="tel" name="contact mumber" placeholder="00000-00000" id="contact number"
                            pattern="[0-9]{5}-[0-9]{5}" required>
                    </div>
                </div>

                <div class="row">
                    <div class="rowelement">
                        <label for="Email">E-Mail ID:</label>
                        <input type="email" placeholder="xyz@gmail.com" id="Email" name="Email" required>

                    </div>
                </div>
                <div class="row">
                    <div class="rowelement">
                        <label for="Hall of Residence">Hall of Residence:</label>
                        <select id="Hall" name="Hall of Residence" required>
                            <option value="Choose your Hall of Residence">Choose your Hall of Residence</option>
                            <option value="Sir Ashutosh Mukherjee Hall of Residence">Sir Ashutosh Mukherjee Hall
                                of
                                Residence
                            </option>
                            <option value="Azad Hall of Residence">Azad Hall of Residence</option>
                            <option value="Bidhan Chandra Roy Hall of Residence">Bidhan Chandra Roy Hall of
                                Residence
                            </option>
                            <option value="Bhimrao Ramji Ambedkar Hall of Residence">Bhimrao Ramji Ambedkar Hall
                                of
                                Residence
                            </option>
                            <option value="Gokhale Hall of Residence">Gokhale Hall of Residence</option>
                            <option value="Homi Jehangir Bhabha Hall of Residence">Homi Jehangir Bhabha Hall of
                                Residence
                            </option>
                            <option value="Acharya Jagadish Chandra Bose Hall of Residence">Acharya Jagadish
                                Chandra
                                Bose Hall
                                of Residence</option>
                            <option value="Lala Lajpat Rai Hall of Residence">Lala Lajpat Rai Hall of Residence
                            </option>
                            <option value="Lalbahadur Sastry Hall of Residence">Lalbahadur Sastry Hall of
                                Residence
                            </option>
                            <option value="Pandit Madan Mohan Malviya Hall of Residence">Pandit Madan Mohan
                                Malviya
                                Hall
                                of
                                Residence</option>
                            <option value="Megnad Saha Hall of Residence">Megnad Saha Hall of Residence</option>
                            <option value="Mother Teresa Hall of Residence">Mother Teresa Hall of Residence
                            </option>
                            <option value="Nehru Hall of Residence">Nehru Hall of Residence</option>
                            <option value="Patel Hall of Residence">Patel Hall of Residence</option>
                            <option value="Radha Krishnan Hall of Residence">Radha Krishnan Hall of Residence
                            </option>
                            <option value="Rajendra Prasad Hall of Residence">Rajendra Prasad Hall of Residence
                            </option>
                            <option value="Rani Laxmibai Hall of Residence">Rani Laxmibai Hall of Residence
                            </option>
                            <option value="Sister Nivedita Hall of Residence">Sister Nivedita Hall of Residence
                            </option>
                            <option value="Sarojini Naidu / Indira Gandhi Hall of Residence">Sarojini Naidu /
                                Indira
                                Gandhi Hall
                                of Residence</option>
                            <option value="Vidyasagar Hall of Residence">Vidyasagar Hall of Residence</option>
                            <option value="Zakir Hussain Hall of Residence">Zakir Hussain Hall of Residence
                            </option>
                        </select>

                    </div>
                </div>
                <div class="row">
                    <div class="rowelement">
                        <label for="DOB">Date of Birth:</label>
                        <input type="date" placeholder="dd-mm-yyyy" id="DOB" name="DOB" required>

                    </div>
                    <div class="rowelement">
                        <label for="Year of study">Year of study</label>
                        <select name="Year of study" id="Year" required>
                            <option value="1st Year">1st Year</option>
                            <option value="2nd Year">2nd Year</option>
                        </select>

                    </div>
                </div>
                <div class="row">
                    <div class="rowelement">
                        <label for="dept">Department</label>
                        <select name="Department" id="Department" required>
                            <option value="Choose your Department">Choose your Department</option>
                            <option value="Department of Aerospace Engineering">Department of Aerospace
                                Engineering
                            </option>
                            <option value="Department of Agricultural and Food Engineering ">Department of
                                Agricultural
                                and Food
                                Engineering</option>
                            <option value="Department of Architecture and Regional Planning">Department of
                                Architecture
                                and
                                Regional Planning</option>
                            <option value="Department of Biotechnology">Department of Biotechnology</option>
                            <option value="Department of Chemical Engineering">Department of Chemical
                                Engineering
                            </option>
                            <option value="Department of Chemistry">Department of Chemistry</option>
                            <option value="Department of Civil Engineering">Department of Civil Engineering
                            </option>
                            <option value="Department of Computer Science Engineering">Department of Computer
                                Science
                                Engineering</option>
                            <option value="Department of Electrical Engineering">Department of Electrical
                                Engineering
                            </option>
                            <option value="Department of Electronics and Electrical Communication">Department of
                                Electronics and
                                Communication</option>
                            <option value="Department of Geology & Geophysics">Department of Geology &
                                Geophysics
                            </option>
                            <option value="Department of Humanities & Social Sciences">Department of Humanities
                                &
                                Social
                                Sciences</option>
                            <option value="Department of Industrial & Systems Engineering">Department of
                                Industrial
                                &
                                Systems
                                Engineering</option>
                            <option value="Department of Mathematics">Department of Mathematics</option>
                            <option value="Department of Mechanical Engineering">Department of Mechanical
                                Engineering
                            </option>
                            <option value="Department of Metallurgical & Materials Engineering">Department of
                                Metallurgical &
                                Materials Engineering</option>
                            <option value="Department of Mining Engineering">Department of Mining Engineering
                            </option>
                            <option value="Department of Ocean Engineering & Naval Architecture">Department of
                                Ocean
                                Engineering
                                & Naval Architecture</option>
                            <option value="Department of Physics">Department of Physics</option>
                        </select>
                    </div>

                </div>
                <div class="row">
                    <div class="rowelement">
                        <label for="Team you want to join">Team you want to join</label>
                        <select name="Team you want to join" id="Team" required>
                            <option value="Web Team">Web Team</option>
                            <option value="Core Team">Core Team</option>
                            <option value="Design Team">Design Team</option>
                            <option value="Videography Team">Videography Team</option>
                        </select>
                    </div>
                </div>
                <div class="row">
                    <div class="rowelement">
                        <label for="file">Certificates/Achievements in the field:</label>
                        <input type="file" name="file" id="file" class="round2" multiple>
                    </div>
                    <div class="rowelement">
                        <lable for="url" class="round2">Link of your previous work/s:</lable>
                        <input type="url" name="url" id="url" multiple>

                    </div>
                </div>
                <div class="row">
                    <div class="rowelement">
                        <label for="feedback">Feedback</label>
                        <textarea name="feedback" rows="10" cols="30" id="feedback"
                            placeholder="please give your feedback"></textarea>
                    </div>
                </div>
                <div class="ffooter">
                    <button class="btn">Submit</button>
                    <button class="btn">Reset</button>
                </div>


        </form>

    </section>
    <footer id="footer" class="bdr">Made by Parineeta Copyright 2023</footer>

</body>

</html>
