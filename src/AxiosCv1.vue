<template>
    <div class="app" :key="user.id">
        <nav>
        <h1 class="hp">Layla Robi'atus<br><span id="lyl">Syarifah</span></h1><br>
        <img src="layla.jpg" alt="cek kuota anda,terimakasih"><br><br>
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
                <p>{{ user.languages }}</p>
            <h2 class="hp">Hobbies<hr></h2>
                <p>{{ user.hobbies }}</p>
        </nav>
        <article>
            <h2 class="hp">Summary<hr></h2>
            <p>{{ user.summary }}</p>
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
            <p>{{ user.education }}</p>
            <h2 class="hp">Certifications<hr></h2>
            <p>{{ user.certificate }}</p>
        </article>
    </div>
</template>
<script>
/* eslint-disable */
export default {
    data() {
        return this.$store.state.users;
        }
    }
</script>