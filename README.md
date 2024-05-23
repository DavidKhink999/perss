<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    <title>Personal Page</title>
</head>
<body>
    <div class="nav">
        <div class="nav-left">David Khinkiladze</div>
        <div class="nav-right">
            <ul>
                <li class="one ooo" onclick="scrollAbout()">About</li>
                <li class="two ooo" onclick="scrollSkills()">Skills</li>
                <li class="three ooo" onclick="scrollExperience()">Experience</li>
                <li class="four ooo" onclick="scrollLink()">Links</li>
            </ul>
        </div>
    </div>

    <div class="main">
        <div class="main-left">
            <img src="/github projects/416952543_1168230047483117_3251827525852816424_n.jpg" alt="">
        </div>

        <div class="main-right">
            <div id="about" class="about">
                <h1>About Me</h1>
                <p>Hello! I'm David Khinkiladze, a passionate and dedicated web developer with a knack for creating visually appealing and highly
                functional websites. With a strong background in front-end technologies and a growing proficiency in back-end development,
                I specialize in crafting seamless user experiences and bringing digital concepts to life.</p>
                <p>
                I'm from Georgia, 17 Years of age, high school graduate in 2024 may, studied at IT ACADEMY STEP and got certificate of them on Front-End Web Development online
                course. Use Languages : English (B2+), Georgian(native), little bit Russian(A1).Responsible person, who can work as Remote.
                </p>
            </div>
            <div class="skills" id="skills">
                <h1>Skills</h1>
                <ul>
                    <li>HTML <p>/// Able to make everything possible.</p></li>
                    <li>CSS <p>/// Good at styling div, at using flex and est.</p></li>
                    <li>JavaScript <p>/// Know functions better, also can use loops.</p></li>
                    <li>Angular <p>/// Know how it works, can retype code from casual file.</p></li>
                    <li>TypeScript <p>/// Know typing sistem.</p></li>
                </ul>
            </div>
            <div class="experience" id="experience">
                <h1>Experience</h1>
                <p>I am an emerging front-end developer with foundational skills in Angular and TypeScript,
                     striving to advance my proficiency in these frameworks. My current level of expertise is moderate;
                      I possess a working knowledge that enables me to contribute to projects but leaves ample room for 
                      growth and deeper mastery. Despite being relatively new to the field, I have cultivated strong 
                      competencies in JavaScript and HTML/CSS, which are fundamental to front-end development.
                    </p>  <p>
                    Throughout my learning journey, I have engaged in various projects
                     that have honed my skills in creating responsive, user-friendly interfaces.
                      My understanding of JavaScript is particularly robust, allowing me to implement
                       dynamic and interactive features effectively. Similarly, my command of HTML and 
                       CSS is solid, enabling me to craft well-structured, aesthetically pleasing web pages 
                       that adhere to contemporary web standards.
                    </p><p>
                    I am committed to continuous learning and am actively seeking opportunities to expand
                     my technical repertoire and practical experience. My goal is to refine my Angular and
                      TypeScript abilities to an advanced level, thereby enhancing my capability to deliver 
                      high-quality, scalable web applications. I am eager to contribute to a forward-thinking
                       team where I can leverage my current skills
                     while embracing new challenges that drive my professional growth.</p>
            </div>
        </div>
    </div>
        <div class="last" id="last">
            <h1>Links</h1>
            <div class="links">
            <a href="https://www.facebook.com/profile.php?id=100028883989736" class="o">Facebook <i class="icon fa-brands fa-facebook"></i></a>
            <a href="https://www.instagram.com/datoxinkiladze822/" class="oo">Instagram <i class="icon fa-brands fa-instagram"></i></a>
            <a href="https://github.com/DavidKhink999" class="ooo">GitHub <i class="icon fa-brands fa-github"></i></a>
            <a href="https://www.linkedin.com/in/datuna-khinkiladze-b53a722a5/" class="oooo">LinkedIN <i class="icon fa-brands fa-telegram"></i></a>
            <a href="https://discord.com/channels/@me" class="ooooo">Discord <i class="icon fa-brands fa-discord"></i></a>
        </div>
        </div>

<script>
    
    function scrollAbout(){
        document.getElementById('about').scrollIntoView({ behavior: 'smooth' })
    }
    function scrollSkills(){
        document.getElementById('skills').scrollIntoView({ behavior: 'smooth' })
    }
    function scrollExperience(){
        document.getElementById('experience').scrollIntoView({ behavior: 'smooth' })
    }
    function scrollLink(){
        document.getElementById('last').scrollIntoView({ behavior: 'smooth' })
    }
</script>
</body>
<style>

* {
    margin: 0;
    padding: 0;
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    background-color: #a9afcb;
}
.one, .two, .three, .four {
    cursor: pointer;
}
.nav {
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 20px;
    background-color: #8c92ac;
}

.nav-left {
    font-size: 30px;
    color: white;
    background-color: #8c92ac;
}

.nav-right li {
    list-style-type: none;
    background-color: #8c92ac;
}

.nav-right ul {
    display: flex;
    gap: 50px;
    font-size: 22px;
    color: white;
    background-color: #8c92ac;
}

.main {
    height: 80vh;
    display: flex;
    position: relative; /* Added */
}

.main-left {
    width: 45%;
    height: 600px;
    position: absolute; /* Changed from fixed to absolute */
}

.main-right {
    margin-left: 750px;
    margin-top: 100px;
    color: white;
    display: flex;
    flex-direction: column;
    gap: 150px;
    width: 50%;
}

img {
    width: 50%;
    display: flex;
    justify-self: center;
    align-items: center;
    margin-left: 25%;
    margin-top: 180px;
    border-radius: 50%;
}

.about {
    display: flex;
    flex-direction: column;
    gap: 30px;
    border: 3px solid grey;
    padding: 10px;
    border-radius: 10px;
    margin-top: 100px;
    background-color: #464855;
}

.about h1 {
    text-align: center;
    background-color: #464855;
}

.about p {
    font-size: 18px;
    background-color: #464855;
}

.skills {
    display: flex;
    flex-direction: column;
    gap: 30px;
    border: 3px solid grey;
    padding: 10px;
    border-radius: 10px;
    width: 150%;
    margin-left:-600px;
    margin-top: 100px;
    background-color: #464855;
}
.skills li p{
    background-color: #464855;
}

.skills h1 {
    text-align: center;
    background-color: #464855;
}
.skills ul {
    background-color: #464855;
}
.skills li {
    list-style-type: none;
    font-size: 22px;
    display: flex;
    gap: 40px;
    margin-left: 20px;
    background-color: #464855;
    height: 40px;
}

.experience {
    display: flex;
    flex-direction: column;
    gap: 20px;
    border: 3px solid grey;
    padding: 10px;
    border-radius: 10px;
    width: 150%;
    margin-left:-600px;
    background-color: #464855;
}

.experience h1 {
    text-align: center;
    background-color: #464855;
}

.experience p {
    font-size: 22px;
    background-color: #464855;
}

.last {
    height: 200px;
    width: 100%;
    background-color: #464855;
    margin-top: 1100px;
    align-items: center;
    display: flex;
    flex-direction: column;
    gap: 50px;
}
.last h1{
    color: white;
    background-color: #464855;
}
.links{
    display: flex;
    flex-direction: row;
    font-size: 28px;
    gap: 60px;
    background-color: #464855;
}
.links a{
    background-color: #464855;
    text-decoration: none;
    color: white;
}
.o:hover{
    color: rgb(18, 18, 156);
}
.oo:hover{
    color: rgb(185, 46, 145);
}
.ooo:hover{
    color: black;
}
.oooo:hover{
    color: rgb(18, 18, 156);
}
.ooooo:hover{
    color: rgb(141, 27, 141);
}
.icon{
    background-color: #464855;
}
</style>
</html>
