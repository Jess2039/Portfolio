<main>
    <div class="home-presentation">
        <h1>Compétences</h1>
    </div>
    <div class="main_skills">
        <section class="skills_section">
            <ul class="skills_list">
                <div class="skill_item">
                <li class="tool"><img src="/images/htmlcss-logo.svg" alt="HTML/CSS" width="52px">HTML/CSS</li>
                <li class="rate"><p class="blue_circle"></p><p class="blue_circle"></p><p class="blue_circle"></p><p class="dark_circle"></p><p class="dark_circle"></p></li>
                </div>
                <div class="skill_item">
                <li class="tool"><img src="/images/JavaScript-logo.png" alt="Javascript" width="53px">Javascript</li>
                <li class="rate"><p class="blue_circle"></p><p class="dark_circle"></p><p class="dark_circle"></p><p class="dark_circle"></p><p class="dark_circle"></p></li>
                </div>
                <div class="skill_item">
                <li class="tool"><img src="/images/svelte-bg.png" alt="Svelte" width="55px">Svelte</li>
                <li class="rate"><p class="blue_circle"></p><p class="blue_circle"></p><p class="dark_circle"></p><p class="dark_circle"></p><p class="dark_circle"></p></li>
                </div>
                <div class="skill_item">
                <li class="tool"><img src="/images/mysql-mariadb.png" alt="MariaDB/MySQL" width="45px">MariaDB/MySQL</li>
                <li class="rate"><p class="blue_circle"></p><p class="blue_circle"></p><p class="dark_circle"></p><p class="dark_circle"></p><p class="dark_circle"></p></li>
                </div>
                <div class="skill_item">
                <li class="tool"><img src="/images/PHP-logo.png" alt="PHP" width="45px">PHP</li>
                <li class="rate"><p class="blue_circle"></p><p class="dark_circle"></p><p class="dark_circle"></p><p class="dark_circle"></p><p class="dark_circle"></p></li>
                </div>
                <div class="skill_item">
                <li class="tool"><img src="/images/Directus_Logo.png" alt="Directus" width="45px">Directus</li>
                <li class="rate"><p class="blue_circle"></p><p class="blue_circle"></p><p class="dark_circle"></p><p class="dark_circle"></p><p class="dark_circle"></p></li>
                </div>
                <div class="skill_item">
                <li class="tool"><img src="/images/github.png" alt="" width="45px">Github</li>
                <li class="rate"><p class="blue_circle"></p><p class="blue_circle"></p><p class="dark_circle"></p><p class="dark_circle"></p><p class="dark_circle"></p></li>
                </div>
                <div class="skill_item">
                <li class="tool"><img src="/images/asana-logo.svg" alt="Asana" width="40px">Asana</li>
                <li class="rate"><p class="blue_circle"></p><p class="blue_circle"></p><p class="blue_circle"></p><p class="dark_circle"></p><p class="dark_circle"></p></li>
                </div>
                <div class="skill_item">
                <li class="tool"><img src="/images/figma-logo.png" alt="Figma" width="50px">Figma</li>
                <li class="rate"><p class="blue_circle"></p><p class="blue_circle"></p><p class="blue_circle"></p><p class="dark_circle"></p><p class="dark_circle"></p></li>
                </div>
                <div class="skill_item">
                <li class="tool"><img src="/images/canva_logo.png" alt="Figma" width="40px">Canva</li>
                <li class="rate"><p class="blue_circle"></p><p class="blue_circle"></p><p class="blue_circle"></p><p class="dark_circle"></p><p class="dark_circle"></p></li>
                </div>
            </ul>
        </section>
        <a href="/CV-Jessica.pdf" target="blank" class="download_cv"><span>Télécharger CV</span></a>
        <section class="rsp_section">
           <hr width="30%" color="white">
            <div class="rsp">
                <a href="https://www.linkedin.com/in/jessica-jamain/" target="blank"><img src="/images/linkedin.png" class="linkedin_logo" alt="linkedin"></a>
                <a href="https://github.com/Jess2039" target="blank"><img src="/images/github.png" class="github_logo" alt="github"></a>
            </div>
            <hr width="30%" color="white">
        </section>
    </div> 
</main>

<style>
    .main_skills {
        display: flex;
        flex-direction: column;
    }
     .line_white {
        border-bottom: solid 2px var(--white);
        border-right: none;
    } 
    .rsp_section {
        display: flex;
        align-items: center;
        margin: 10px 0px;
    }
    .rsp {
        display: flex;
        flex-direction: row;
    }
    .rsp a {
        margin-right: 20px;
    }
    .linkedin_logo {
        width: 30px;
    }
    .github_logo {
        width: 35px;
    }
    li {
        list-style-type:none;  
        margin: 15px 25px;
        font-size: 20px;
        width: 200px;
    }
    li img {
        margin-right: 20px;
    }
    .rate {
        display: flex;
        justify-content: space-between;
    }
    .blue_circle {
        border: var(--white) solid 0.1px;
        background-color: var(--bluemoon);
        width:15px;
        height: 15px;
        border-radius: 25px;
    }
    .dark_circle {
        border: var(--white) solid 0.1px;
        background-color: var(--black_background);
        width:15px;
        height: 15px;
        border-radius: 25px;  
    }
    .download_cv {
     /*    background-color: var(--bluemoon);
        border: solid 2px var(--bluemoon);
        width: 150px;
        margin-left: 30%;
        border-radius: 8%;
        margin-top: 10px;
        text-decoration: none;
        text-align: center; */
        height:20px;
        width:180px;
        border:none;
        border-radius:50px;
        transition:0.3s;
        background-color:var(--bluemoon);
        animation: glow 1s infinite ;
        transition:0.5s;
        text-align: center;
        padding-bottom: 30px;
        text-decoration: none;
        margin-top: 10px;
        margin-left: 30%;
    }
    .download_cv:hover {
        transform:translateX(-20px);
        border-radius:50px;
        background-color:var(--white);
        transition:0.5s;
    }
    span{
    display: block;
    width: 100%;
    height: 100%;
    font-family: Arial, Helvetica, sans-serif;
    font-weight: 700;
    padding-top: 8%;
    padding-right: 2.5%;
    margin-right: 0px;
    font-size: 1.2rem;
    transition: 0.3s;
    }
span:hover{
    transition: 0.3s;
    opacity: 1;
    font-weight: 700;
    }
    @keyframes glow{
  0%{
  box-shadow: 5px 5px 20px var(--white),-5px -5px 20px var(--white);}
  
  50%{
  box-shadow: 5px 5px 20px var(--white),-5px -5px 20px var(--white)
  }
  100%{
  box-shadow: 5px 5px 20px var(--bluemoon),-5px -5px 20px var(--bluemoon)
  }
}

      /* ******* Desktop ******* */
@media screen and (min-width: 1024px) {
    
    .skill_item {
        display: flex;
    }
    .home-presentation {
        margin-top: 180px;
    }
    .home-presentation h1 {
        font-size: 50px;
        margin-left: 25%;
        margin-bottom: 100px;
    }
    li {
        font-size: 35px;
    }
    .tool {
        width: 400px;
        margin-right: 100px;
    }
    li img {
        width:70px;
        margin-right: 60px;
    }
    .blue_circle {
        width:30px;
        height: 30px;
        margin: 10px 5px;
    }
    .dark_circle {
        width:30px;
        height: 30px; 
        margin: 10px 5px;
    }
    .rate {
        width: 450px;
    }
    .skills_list {
        margin-left: 100px;
    }
    .download_cv {
        margin-left: 50%;
        height: 20px;
        padding-top: 5px;
    }
    .linkedin_logo {
        width: 35px;
    }
    .github_logo {
        width: 45px;
    }
}

</style>