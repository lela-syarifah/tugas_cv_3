<template>
  <div id="upp">
    <div class="all" v-for="user in users" :key="user">
        <div id="app">
          <nav>
          <h1 class="hp">Layla Robi'atus<br><span id="lyl">Syarifah</span></h1><br>
            <img src="bunga.jpg" alt="" id="cv1"><br><br>
              <h2 class="hp">Contact<hr></h2>
                  <p><b>Address:</b></p>
                      <p>{{ user.address }}</p>
                  <p><b>Phone:</b></p>
                      <p>{{ user.phone }}</p>
                  <p><b>Email:</b></p>
                      <a href="mailto:syareefa4@gmail.com">{{ user.email }}</a><br><br>
                  <p><b>Linkedin:</b></p>
                      <p>{{ user.linkedin }}</p>
              <h2 class="hp">Languages<hr></h2>
                  <p>Javanese<br>Indonesian<br>English</p>
              <h2 class="hp">Hobbies<hr></h2>
                <ul>
                  <li>Writing</li>
                  <li>Reading</li>
                </ul>
          </nav>
          <article>
              <h2 class="hp">Summary<hr></h2>
                <p>Senior Web Developer specializing in front development.<br> Experienced with all stages of the development cycle for dynamic web projects. Well-versed in numerousm programming<br> languages including HTML5, PHP OOP, JavaScript, CSS, MySQL.<br> Strong background in project management and customer<br> relation<br></p>
              <h2 class="hp">Skill Hightlights<hr></h2>
                <ul id="ul">
                    <li>Project management</li>
                    <li>Strong decision maker</li>
                    <li>Complex problem<br> solver</li>
                    <li>Creative design</li>
                    <li>Innovative</li>
                    <li>Service-focused</li>
                </ul><br>
              <h2 class="hp">Experience<hr></h2>
                <p><b>Web Developer</b>-09/2015 to 05/2019<br> <b>Luna Web Design</b>, New York</p>
                <ul>
                    <li>Cooperate with designers to create clean interfaces and<br> simple, intuitive interaction and experiences.</li>
                    <li>Develop project concepts and maintain optimal<br> workflow.</li>
                    <li>Work with senior developer to manage large, complex<br> design project for corporatie clients.</li>
                    <li>Complete detailed programming and development tasks<br> challenging back-end server code.</li>
                    <li>Carry out quality assurance tests to discover errors and<br> optimize usability.<br></li>
                </ul><br>
              <h2 class="hp">Education<hr></h2>
                <p>Bachelor of Science: <b>Computer Information Systems</b> - 2014<br> <b>Columbia University</b>, NY<br></p>
              <h2 class="hp">Certifications<hr></h2>
                <p>PHP Framework (certificate): <b>Zend, Codeigniter, Symfony.</b><br>Programming Languages: <b>JavaScript, HTML5, PHP OOP, CSS,<br> SQL, MySQL</b></p>          </article>
        </div>
        <br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>
        <br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>
        <div id="ass">
          <header>
            <br><div id="rsm"><h5 id="res">RESUME</h5></div>
              <h2 class="nm"><br><br><span id="span">Layla Robi'atus Syarifah</span></h2>
              <img src="bunga.jpg" alt="" id="cv2">
          </header><br>
          <div id="bio">
              <h4>PROFILE<hr class="hr"></h4>
                  <h5>NAME</h5>
                      <p>{{ user.name }}</p>
                  <h5>DATE OF BIRTH</h5>
                      <p>{{ user.born }}</p>
                  <h5>ADDRESS</h5>
                      <p>{{ user.address }}</p>
                  <h5>WEBSITE</h5>
                      <p>{{ user.linkedin }}</p>
              <h4>AWARDS<hr class="hr"></h4>
                  <h5>CREATIVE AWARDS 2012</h5>
                      <p>Openminded.org</p>
                  <h5>INTERFACE DESIGN 2013</h5>
                      <p>Coolideas.com</p>
              <h4>CONTACT<hr class="hr"></h4>
                  <h5>HOME NUMBER</h5>
                      <p>{{ user.linkedin }}</p>
                  <h5>PHONE NUMBER</h5>
                      <p>{{ user.phone }}</p>
                  <h5>EMAIL</h5>
                      <p>{{ user.email }}</p>
              <h4>SOCIAL<hr class="hr"></h4>
                  <h5>TWITTER</h5>
                      <p>{{ user.linkedin }}</p>
                  <h5>FACEBOOK</h5>
                      <p>{{ user.linkedin }}</p>
          </div>
          <div class="knn">
              <h4>GRAPHIC ARTIST</h4><hr id="garis">
                  <div id="articel">
                  <h4>WORK EXPERIENCE<hr class="hr"></h4>
                      <h5>CREATIVE ROOMS</h5>
                      <p>Feb 2013 - Jun 2014</p><br>
                      <h5>CREATIVE ROOMS</h5>
                      <p>Feb 2013 - Jun 2014</p><br>
                      <h5>CREATIVE ROOMS</h5>
                      <p>Feb 2013 - Jun 2014</p><br><br><br><br><br><br><br><br><br><br><br><br>
                      <h5>SENIOR ART DIRECTOR</h5>
                      <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Fugiat id neque amet in ducimus facere facilis consequatur, officiis temporibus cumque itaque, aut rerum, est asperiores.</p>
                      <h5>SENIOR ART DIRECTOR</h5>
                      <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Fugiat id neque amet in ducimus facere facilis consequatur, officiis temporibus cumque itaque, aut rerum, est asperiores.</p>
                      <h5>SENIOR ART DIRECTOR</h5>
                      <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Fugiat id neque amet in ducimus facere facilis consequatur, officiis temporibus cumque itaque, aut rerum, est asperiores.</p>                
                  </div><br> 
                  <div id="tikel">
                  <h4>EDUCATION<hr class="hr"></h4>
                      <h5>MASTER DEGREE</h5>
                      <p>Feb 2011 - Jun 2014</p>
                      <h5>MASTER DEGREE</h5>
                      <p>Feb 2011 - Jun 2014</p>
                      <h5>MASTER DEGREE</h5>
                      <p>Feb 2011 - Jun 2014</p><br><br><br><br><br>
                      <h5>UNIVERSITY OF CREATIVE MINDS</h5>
                      <p>Jakarta, Indonesia</p>
                      <h5>UNIVERSITY OF CREATIVE MINDS</h5>
                      <p>Jakarta, Indonesia</p>
                      <h5>UNIVERSITY OF CREATIVE MINDS</h5>
                      <p>Jakarta, Indonesia</p>
                  </div><br>
                  <div id="skil">
                    <h4>SKILLS<hr class="hr"></h4>
                      <h5>PROFESSIONAL SKILLS</h5>
                      <p>Microsoft Windows <span class="bullets"></span> <span class="bullets"></span> <span class="bullets"></span> <span class="bullets"></span> <span class="bullets"></span> <span class="titik"></span> <span class="titik"></span></p>
                      <p>Windows <span class="bullets"></span> <span class="bullets"></span> <span class="bullets"></span> <span class="bullets"></span> <span class="bullets"></span> <span class="titik"></span> <span class="titik"></span></p>
                      <p>Mac OSX <span class="bullets"></span> <span class="bullets"></span> <span class="bullets"></span> <span class="bullets"></span> <span class="bullets"></span> <span class="titik"></span> <span class="titik"></span></p>
                      <p>Data Handling <span class="bullets"></span> <span class="bullets"></span> <span class="bullets"></span> <span class="bullets"></span> <span class="bullets"></span> <span class="titik"></span> <span class="titik"></span></p>
                      <p>Record Keeping <span class="bullets"></span> <span class="bullets"></span> <span class="bullets"></span> <span class="bullets"></span> <span class="bullets"></span> <span class="titik"></span> <span class="titik"></span></p>
                      <p>Web Skills <span class="bullets"></span> <span class="bullets"></span> <span class="bullets"></span> <span class="bullets"></span> <span class="bullets"></span> <span class="titik"></span> <span class="titik"></span></p><br><br><br><br><br><br>
                      <h5>PERSONAL SKILLS</h5>
                      <p>Organisation <span class="bullets"></span> <span class="bullets"></span> <span class="bullets"></span> <span class="bullets"></span> <span class="bullets"></span> <span class="titik"></span> <span class="titik"></span></p>
                      <p>Communication <span class="bullets"></span> <span class="bullets"></span> <span class="bullets"></span> <span class="bullets"></span> <span class="bullets"></span> <span class="titik"></span> <span class="titik"></span></p>
                      <p>Time Keeping <span class="bullets"></span> <span class="bullets"></span> <span class="bullets"></span> <span class="bullets"></span> <span class="bullets"></span> <span class="titik"></span> <span class="titik"></span></p>
                      <p>Team Player <span class="bullets"></span> <span class="bullets"></span> <span class="bullets"></span> <span class="bullets"></span> <span class="bullets"></span> <span class="titik"></span> <span class="titik"></span></p>
                      <p>Commitment <span class="bullets"></span> <span class="bullets"></span> <span class="bullets"></span> <span class="bullets"></span> <span class="bullets"></span> <span class="titik"></span> <span class="titik"></span></p>
                      <p>Multitasking <span class="bullets"></span> <span class="bullets"></span> <span class="bullets"></span> <span class="bullets"></span> <span class="bullets"></span> <span class="titik"></span> <span class="titik"></span></p>
                  </div>
          </div>
        </div>
    </div>
 </div>
</template>

<script>
/* eslint-disable */
import axios from 'axios'
export default {
  data () {
    return{
      users: '',
    }
  },
  mounted() {
    this.load()
  },
  methods: {
    load(){
      axios.get('http://localhost:3000/users').then(res => {
        this.users = res.data 
      }).catch ((err) => {
        console.log(err);
      })
    }
  },
}
</script>

<style>
* {
  box-sizing: border-box;
}
#res {
  color: rgb(2, 2, 46);
  text-align: center;
  height: 1px;
  margin-left: 50px;
  width: 150px;
  padding-left: 150px;
}
#rsm {
  background-color: white;
  height: 15px;
}
.bullets {
  height: 10px;
  width: 10px;
  background-color: rgb(2, 2, 46);
  border-radius: 50%;
  display: inline-block;
}
.titik {
  height: 10px;
  width: 10px;
  background-color: rgba(2, 2, 46, 0.377);
  border-radius: 50%;
  display: inline-block;
}
#span {
  padding-left: 380px;
}
#cv2 {
  border-radius: 50%;
  width: 180px;
  height: 180px;
  padding-left: 11%;
  padding-top: 10px;
}
#cv1 {
  width: 300px;
  height: 200px;
  padding-left: 0px;
  padding-bottom: 10px;
}
#garis {
  border: 1px solid rgb(2, 2, 46);
  margin-top: -20px;
  margin-bottom: 27px;
  margin-left: 1px;
  width: 84.7%;
}
#skil {
  height: 410px;
  background: rgb(188, 188, 189);
  width: 85%;
  padding: 28px;
  -webkit-column-count: 3;
  -moz-column-count: 3;
  column-count: 2;
  font-size: 15px;
}
#tikel {
  height: 430px;
  background: rgb(188, 188, 189);
  width: 85%;
  padding: 28px;
  -webkit-column-count: 3;
  -moz-column-count: 3;
  column-count: 2;
  font-size: 15px;
}
#articel {
  height: 670px;
  background: rgb(188, 188, 189);
  width: 85%;
  padding: 28px;
  -webkit-column-count: 3;
  -moz-column-count: 3;
  column-count: 2;
  font-family: Arial, Helvetica, sans-serif;
}
.knn {
  float: right;
  width: 78%;
  color: rgb(2, 2, 46);
  padding-top: 0px;
  padding-left: 30px;
}
p {
  font-family: Arial;
}
h5 {
  font-family: Arial, Helvetica, sans-serif;
  font-size: 15px;
}
h4 {
  font-family: 'Courier New', Courier, monospace;
  font-size: 30px;
}
.hr {
  border: 2px dotted rgb(8, 8, 8);
  margin-top: 0px;
}
hr {
  border-color: grey;
}
header{
  background-color: rgb(2, 2, 46);
  width: 88.7%;
  height: 240px;
  color: white;
}
#bio {
  text-align: right;
  float: left;
  color: rgb(2, 2, 46);
  padding-top: 100px;
  padding-left: 100px;
}
h1 {
  font-size: 37px;
}
.hp {
  font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
}
.nm {
  font-family: 'Courier New', Courier, monospace;
}
#app {
  font-family: sans-serif;
  background-color: grey;
}
nav {
  float: left;
  width: 30%;
  height: 1104px;
  background: rgb(188, 188, 189);
  padding: 50px;
}
article {
  float: left;
  padding: 50px;
  width: 59%;
  background-color: white;
  height: 1104px;
}
section::after {
  content: "";
  display: table;
  clear: both;
}
#lyl {
  color: rgb(255, 115, 0);
}
#ul {
  -webkit-column-count: 2;
  -moz-column-count: 2;
  column-count: 2;
}
</style>