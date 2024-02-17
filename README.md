<!DOCTYPE html>
<html>
<head>
	<title>Sai geetha Gummadapu</title>
	<link rel="stylesheet" type="text/css" href="resume.css">
</title> <script src="https://kit.fontawesome.com/3ef3559250.js" crossorigin="anonymous"></script>
</head>
<body>

<section class="resume">
	<div class="resume_left">
	    <div class="r_profile_pic">
	      <img src="srmlogo.jpeg" alt="profile_pic">
	    </div>
	    <div class="r_left_sub">
	      <div class="r_aboutme">
	        <h2>About me</h2>
	        <p>I am student at SRM University AP in the Department of Computer Science and Engineering.</p>
	      </div>
	      <div class="r_skills">
	        <h2>Skills</h2>
	        <ul>
	          <li>
	            <p><i class="fa-solid fa-code"></i></p>
	            <p>C language</p>
	          </li>
	          <li>
	            <p><i class="fa-solid fa-pen-nib"></i></p>
	            <p>C++ language</p>
	          </li>
	          <li>
	            <p><i class="fa-solid fa-video"></i></p>
	            <p>Data structers</p>
	          </li>
	          <li>
	            <p><i class="fa-solid fa-headphones"></i></p>
	            <p>Python</p>
	          </li>
	          <li>
	            <p><i class="fa-solid fa-image"></i></p>
	            <p>Web technology</p>
	          </li>
	        </ul>
	      </div>
	      <div class="r_hobbies">
	        <h2>Hobbies</h2>
	        <ul>
	          <li>
	            <p><i class="fa-solid fa-book"></i></p>
	          </li>
	          <li>
	            <p><i class="fa-solid fa-plant-wilt"></i></p>
	          </li>
	          <li>
	            <p><i class="fa-solid fa-bicycle"></i></p>
	          </li>
	          <li>
	            <p><i class="fa-solid fa-chess"></i></p>
	          </li>
	        </ul>
	      </div>
	    </div>
	</div>
	<div class="resume_right">
	    <div class="r_namerole">
	      <p>Gummadapu</p>
	      <p>Sai geetha</p>
	      <p class="role">Student</p>
	    </div>
	    <div class="r_info">
	      <ul>
	        <li>
	          <p>Sai geetha Gummadapu </p>
	        </li>
	        <li>
	          <p>9849493602</p>
	        </li>
	      </ul>
	    </div>
	    <div class="r_right_sub">
	      <div class="r_education">
	        <h2>Education</h2>
	        <ul>
	          <li>
	            <div class="r_ed_left">
	              <p>2020</p>
	            </div>
	            <div class="r_ed_right">
	              <p>10th standard</p>
	            </div>
	          </li>
	          <li>
	            <div class="r_ed_left">
	              <p>2020-2022</p>
	            </div>
	            <div class="r_ed_right">
	              <p>college</p>
	            </div>
	          </li>
	          <li>
	            <div class="r_ed_left">
	              <p>2022-2026</p>
	            </div>
	            <div class="r_ed_right">
	              <p>B.Tech</p>
	              <p>Computer science engineering</p>
	            </div>
	          </li>
	        </ul>
            <h2>CERTIFICATIONS</h2>
            <p>JOY OF COMPUTING USING PYTHON-NPTEL</p>
            <p>Psychology of learning</p>
	</div>
</section>

</body>
</html>
@import url("https://fonts.googleapis.com/css2?family=Calligraffitti&family=Open+Sans:wght@400;700&display=swap");

:root {
  --bg-clr: #6b7fba;
  --white: #fff;
  --rleft-bg: #9ab3eb;
  --rright-bg: #8096d0;
  --primary-text-clr: #525252;
}

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  list-style: none;
  font-family: "Open Sans", sans-serif;
}

body {
  background: var(--bg-clr);
  font-size: 12px;
  line-height: 20px;
  color: var(--primary-text-clr);
  padding: 0 20px;
}

h2 {
  font-family: "Calligraffitti", cursive;
  text-transform: uppercase;
  text-align: center;
  margin-bottom: 20px;
}

.resume {
  width: 800px;
  max-width: 100%;
  height: auto;
  display: flex;
  margin: 50px auto;
  background: var(--white);
}

.resume .resume_left {
  width: 270px;
}

.resume .resume_right {
  background: var(--rright-bg);
  width: calc(800px - 270px);
}

.resume_left .r_profile_pic,
.resume_right .r_namerole {
  width: 100%;
  height: 260px;
  padding: 35px;
}

.resume_left .r_profile_pic {
  background: var(--rleft-bg);
}

.resume_left .r_profile_pic img {
  width: 100%;
}

.resume_left .r_left_sub {
  padding: 35px;
}

.resume_left .r_left_sub > div:not(:last-child),
.resume_right .r_right_sub > div:not(:last-child) {
  margin-bottom: 35px;
}

.resume_left .r_aboutme p {
  text-align: center;
}

.resume_left .r_skills ul li,
.resume_left .r_skills ul li p:first-child,
.resume_left .r_hobbies ul li p:first-child {
  display: flex;
  align-items: center;
}

.resume_left .r_skills ul li:not(:last-child) {
  margin-bottom: 10px;
}

.resume_left .r_skills ul li p:first-child,
.resume_left .r_hobbies ul li p:first-child {
  width: 45px;
  height: 45px;
  background: var(--rleft-bg);
  margin-right: 15px;
  border-radius: 50%;
  justify-content: center;
  font-size: 14px;
  color: var(--white);
}

.resume_left .r_hobbies ul {
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
}

.resume_left .r_hobbies ul li {
  margin-bottom: 10px;
}

.resume_left .r_hobbies ul li p:hover {
  background: var(--rright-bg);
}

.resume_right .r_namerole p {
  font-family: "Calligraffitti", cursive;
  font-size: 60px;
  line-height: 80px;
  text-align: center;
}

.resume_right .r_namerole p:last-child {
  font-size: 18px;
  line-height: 24px;
  color: var(--white);
}

.resume_right .r_info {
  padding: 35px;
  background: var(--white);
}

.resume_right .r_info ul {
  display: flex;
  justify-content: space-between;
}

.resume_right .r_info p {
  font-weight: 700;
  font-size: 18px;
}

.resume_right .r_right_sub {
  padding: 35px;
  padding-bottom: 0;
}

.resume_right .r_right_sub p {
  color: var(--white);
}

.resume_right .r_right_sub ul li {
  display: flex;
  margin-bottom: 20px;
}

.resume_right .r_right_sub ul li div:first-child {
  width: 25%;
  margin-right: 15px;
}

.resume_right .r_right_sub ul li div:last-child {
  width: 75%;
}

.resume_right .r_right_sub p:first-child {
  font-size: 18px;
  margin-bottom: 5px;
}

