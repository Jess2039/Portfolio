

<main>
    <div class="home-presentation">
        <h1>Jessica JAMAIN</h1>
            <h2>Développeur web - Intégrateur</h2>
    </div>
    <section class="contact_section">
        <section class="rsp_section">
            <div class="border_white"></div>
            <div class="rsp">
                <a href="https://www.linkedin.com/in/jessica-jamain/" target="blank"><img src="/images/linkedin.png" class="linkedin_logo" alt="linkedin"></a>
                <a href="https://github.com/Jess2039" target="blank"><img src="/images/github.png" class="github_logo" alt="github"></a>
            </div>
            <div class="border_white"></div>
        </section>
        <div class="contact_div">
            <a href="mailto:jessicajamain20@gmail.com" target="blank"><button class="contact_me"><span>Me contacter</span></button></a>
        </div>
    </section>
</main>  
<style>
     .rsp {
        margin-left: 50px;
    }
    .contact_section {
        display: flex;
    }
    .contact_div {
        margin-top: 480px;
    }
    .contact_me {
        height:50px;
        width:150px;
        border:none;
        border-radius:50px;
        transition:0.3s;
        background-color:var(--bluemoon);
        animation: glow 1s infinite ;
        transition:0.5s;
        text-align: center;
    }
    .contact_me:hover {
        transform:translateX(-20px);
        border-radius:50px;
        background-color:var(--white);
        transition:0.5s;
       /*  width: 200px;
        height: 60px;
        rotate: 360deg; */
    }
    span{
    display: block;
    width: 100%;
    height: 100%;
    font-family: Arial, Helvetica, sans-serif;
    font-weight: 700;
    padding-top: 10%;
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
    .rsp_section {
        margin-left: 260px;
        width: 800px;
    }
    .contact_section {
        width: 450px;
    }
    .contact_div {
        margin-left: 80%;
    }
    .rsp {
        margin-left: 0px;
    }
    .border_white {
        margin-left: 60px;
    }
    .contact_me {
        width: 200px;
        height: 75px;
        padding-top: 8px;
    }
    span {
        font-size: 24px;
    }
  
}

</style>