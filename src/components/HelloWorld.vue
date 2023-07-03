<template>
  <nav class="navbar">
    <ul>
      <li><a @click="smoothScroll('#education')">Education</a></li>
      <li><a @click="smoothScroll('#what')">Skills</a></li>
      <li><a @click="smoothScroll('#experiences')">Work Experiences</a></li>
      <li><a @click="smoothScroll('#projects')">Projects</a></li>
      <li><a @click="smoothScroll('#blogs')">Blogs</a></li>
      <li><a @click="smoothScroll('#certifications')">Certifications</a></li>
      <li><a @click="smoothScroll('#contact')">Contact Me</a></li>
    </ul>
  </nav>
  <div class="about-me">
    <h1>Hi all,<span id="wave-emoji"> 👋 </span> I'm Ali Ahmad Jan</h1>
    <img id="web-dev" src="../assets/web-dev1.png">
    <p>
      I have proficiency in C++, MERN Stack, MEVN Stack, Flask, AWS and Docker. I am eager to
develop my skills further and work in a collaborative team environment. I am
passionate about technology and stay updated with the latest advancements by
watching tech-related videos and reading articles. I am also a devoted football fan
and enjoy both watching and playing the game
    </p>

    </div>
    <div class="logos">
    

    <a href="https://www.linkedin.com/in/ali-ahmad-jan-14b108206/" target="_blank">
        <img id="linkedin" src="../assets/linkedin.png">
    </a>

   
    <a href="https://github.com/aliahmadjan" target="_blank">
        <img id="github" src="../assets/github.png">       
    </a>

     
    <a href="mailto:aliahmadjan009@gmail.com" target="_blank">
        <img id="github" src="../assets/email.png">       
    </a>

    
    </div>
    <div class="button-container">
  <button id="contact-btn" @click="goToContact">Contact</button>
  <!-- <button id="resume" @click="downloadResume">Download Resume</button> -->
 
</div>

<div id="education">
  <h1>Education <span>🏫</span></h1>
  
  <img src="../assets/fast.png">
  <div class="education-container">
  <p>National University of Computer and Emerging Sciences <br>
  Bachelor in Computer Science <br>
  September 2019 - July 2023 </p>
</div>

<hr>

<img src="../assets/fauji.png">
  <div class="college-container">
  <p>Fauji Foundation College For Boys<br>    
   Pre-Engineering (Chemistry, Physics and Mathematics)<br>
  September 2017 - August 2019 </p>
</div>
<hr>
</div>

<div id="what">

  <h1>Skills <span>✨</span></h1>
  <h2>CRAZY FULL STACK DEVELOPER WHO WANTS TO EXPLORE EVERY TECH STACK</h2>
  
</div>

<div>
  <img id="web" src="../assets/xD.png">
</div>

<div class="tech-logos">
  
        <img id="reactjs" src="../assets/reactjs.png">
        <img id="nodejs" src="../assets/nodejs.png">
        <img id="mongodb" src="../assets/mongodb.png">
         <img id="vuejs" src="../assets/vuejs.png">
        <img id="docker" src="../assets/docker.png">
        <img id="aws" src="../assets/aws.png">
        <img id="python" src="../assets/python.png">
        <img id="c" src="../assets/c++.png">
        <img id="java" src="../assets/java.png">
        <img id="html" src="../assets/html.png">
        <img id="css" src="../assets/css.png">
        <img id="flask" src="../assets/flask.png">
</div>

<div class="skills">
  <ul>
    <li>MERN Stack</li>
    <li>MEVN Stack</li>
    <li>HTML and CSS</li>
    <li>Python</li>
    <li>C and C++</li>
    <li>Java</li>
    <li>Flask</li>
    <li>AWS</li>
    <li>Docker</li>
  </ul>
</div>
<div id="experiences">
  <h1>Experiences <span>🏢</span></h1>
</div>

<div class="test-experience">
<div class="card-experience">
<img id="folio" src="../assets/folio3.png"> 
<div class="container-experience">
<h4>Folio3 Summer Internship Program<br>
  Aug 2022 - Sept 202</h4>
    <p> I participated in Folio3's Summer Internship program where I gained valuable
knowledge in basic concepts of web development and android development.
Through mentorship, I acquired practical skills that will serve as a foundation for
my future career in technology</p>
</div>

</div>


</div>

<div id="projects">
  <h1>Projects <span>🚀</span></h1>
</div>





<div class="test">
<div class="card">
  
 <img id="learnlive" src="../assets/LearnLiveLogo.png"> 
 <div class="container">
    <h4> LearnLive - FYP</h4>
    <p> Developed a web based platform that provides Zoom for online
classes, LMS, chatting feature, collaborative coding, discussion
forums all at one platform using MERN Stack</p>
</div>
</div>



<div class="card">


<img id="vm" src="../assets/vm.png"> 
<div class="container">
<h4>Veteran Meet</h4>
    <p> Built a Facebook-inspired application where veterans could create
profiles, upload content and posts, follow each other, and connect
to different events using MERN and REST API</p>
</div>

</div>
<div class="card">


<img id="gymfit" src="../assets/gymfit.png"> 
<div class="container">
<h4>Gym Fit</h4>
    <p> Developed a web based platform for the gym, along with maintaining
user profiles, workout routine and diet plans using HTML, CSS,
Bootstrap, PHP and MYSQL</p>
</div>

</div>
<div class="card">


<img id="carbo" src="../assets/carbo1.png"> 
<div class="container">
<h4> Carbo</h4>
    <p>Developed an application which assists and enables anyone
with carpooling using JavaFX, JDBC, Hibernate, and MySQL</p>
</div>

</div>
</div> 
 


<div id="blogs">
  <h1>Blogs <span id="blog-emoji">📖</span></h1>
  <h2>WITH LOVE FOR DEVELOPING COOL STUFF, I LOVE TO WRITE AND TEACH OTHERS WHAT I HAVE LEARNT.</h2>
</div>

<div class="test-blogs">
<div class="card-blogs">
 
  <div class="container-blogs">
    <h4>Dockerizing a MERN Stack Application using Docker Compose: A Step-by-Step Guide</h4>
    <p> Docker is a popular containerization technology that allows developers
       to package and deploy their applications with ease. Docker Compose is...</p>


<button id="view-blog1"
role="link"
@click="openInNewTab('https://medium.com/@i190572/dockerizing-a-mern-stack-application-using-docker-compose-a-step-by-step-guide-396250713b20')"
>View</button>
</div>
</div>


<div class="card-blogs">
<div class="container-blogs">
<h4> PlayKube Podman: Building containers without Docker</h4>
    <p> Introduction As software development becomes more complex, containerization has become
       a crucial component of the development process. They provide a lightweight and portable way to package 
      software dependencies and run applications in any environment...</p>
      <button id="view-blog2"
      role="link"
      @click="openInNewTab('https://medium.com/@i190572/playkube-podman-building-containers-without-docker-3f71eece1bcf')"
      >View</button>
</div>

</div>


<div class="card-blogs">
<div class="container-blogs">
<h4>
    How to Create a Virtual Machine on DigitalOcean and Securely Access it using SSH Keys and RDP</h4>
    <p> DigitalOcean is a cloud hosting provider that offers an easy-to-use interface 
      for creating and managing virtual machines (VMs) in the...</p>

<button id="view-blog3"
role="link"
  @click="openInNewTab('https://medium.com/@i190572/how-to-create-a-virtual-machine-on-digitalocean-and-securely-access-it-using-ssh-keys-and-rdp-3f0983065ba0')"
>View</button>
</div>
</div>

</div>

<div id="certifications">
  <h1>Certifications <span id="trophy">🏆</span></h1>
  
</div>

<div class="test">
<div class="card">
 
  <div class="container-certifications">
    <img id="coursera" src="../assets/coursera.png"> 
    <h4> Programming for Everybody
(Getting Started with Python)
(Coursera)</h4>
    
</div>
</div>
<div class="card">
<div class="container-udemy">
  <img id="udemy" src="../assets/udemy.png"> 
  
<h4>The Complete 2023 Web
Development Bootcamp (Udemy)</h4>
</div>

</div>

<div class="card">
<div class="container-certifications">
  <img id="solo" src="../assets/solo.png"> 
<h4>Fundamentals of Istio by Solo.io</h4>
<button id="solo-btn"
role="link"
  @click="openInNewTab('https://www.credly.com/badges/5f12146c-6007-433b-b8fc-3113f8a39da2/public_url')"
>View Badge</button>
</div>

</div>

<div class="card">
<div class="container-certifications">
  <img id="azure" src="../assets/azure.png"> 
<h4>Azure Fundamentals ( AZ-900 )</h4>
<button id="azure-btn"
role="link"
  @click="openInNewTab('https://www.credly.com/badges/8da2c4f2-6e52-468e-81d7-803b20975ac8/public_url')"
>View Badge</button>
</div>

</div>

<div class="card">
<div class="container-certifications">
  <img id="aws-cloud" src="../assets/aws-cloud.png"> 
<h4>AWS Academy Graduate - AWS Academy Cloud Foundations</h4>
<button id="aws-cloud-btn"
role="link"
  @click="openInNewTab('https://www.credly.com/badges/2b3c2717-3a9b-4841-9847-3ba5471c3af1/public_url')"
>View Badge</button>
</div>

</div>

</div>


<div id="contact">
  <h1>Contact Me <span>☎️</span></h1>
  <h2>DISCUSS A PROJECT OR JUST WANT TO SAY HI? MY INBOX IS OPEN FOR ALL.</h2>
  <h3> +923345200264<br>
    aliahmadjan009@gmail.com
  </h3>
</div>
<div>
  <img id="cnt" src="../assets/contact.png"> 
  </div>



<footer>
    <p>Ali Ahmad Jan<br>
        </p>
        
  <a href="https://www.linkedin.com/in/ali-ahmad-jan-14b108206/" target="_blank">
        <img id="linkedin" src="../assets/linkedin.png">
    </a>

   
    <a href="https://github.com/aliahmadjan" target="_blank">
        <img id="github" src="../assets/github.png">       
    </a>

     
    <a href="mailto:aliahmadjan009@gmail.com" target="_blank">
        <img id="github" src="../assets/email.png">       
    </a>
    <div>
      <button class="go-top" @click="scrollTop">
  <img id="top" src="../assets/top.png" alt="Go to top">
</button>

 </div>
      </footer>

     


</template>



<script>
export default {
  methods: {
   
    openInNewTab(url) {
      window.open(url, '_blank', 'noreferrer');
    },

    smoothScroll(target) {
  const element = document.querySelector(target);
  if (element) {
    window.scrollTo({
      top: element.offsetTop,
      behavior: 'smooth'
    });
  }
},


    scrollTop() {
        window.scrollTo({
          top: 0,
          behavior: "smooth"
        });
      },

      goToContact(){
        const contactElement = document.getElementById('contact')  
        contactElement.scrollIntoView({ behavior: 'smooth' })
  },
 
  
  downloadResume(){

      const fileURL = process.env.BASE_URL + 'AliAhmadJan-Resume.pdf';
      
     // require('@/assets/AliAhmadJan-Resume.pdf'); // Provide the relative path to the file here
      // Create a virtual link element
      const link = document.createElement('a');
      link.href = fileURL;
      link.download = 'AliAhmadJan-Resume.pdf'; // Set the desired file name here
      link.target = '_blank'; // Open the file in a new tab
      // Trigger the click event on the link element
      link.click();
      },
  
  },
     
}


</script>

<!-- </script> -->

<style>
  body {
    margin: 0;
    background-color: rgb(23,28,40);
    /* background-image: linear-gradient(to right, rgba(66, 66, 66, 0.423), rgb(86, 82, 82)); */
    /* background-image: linear-gradient(to right, rgba(206, 163, 71, 0.423), rgb(255, 255, 255)); */
  }

 

  #wave-emoji {
    display: inline-block;
    animation-name: wave;
    animation-duration: 1s;
    animation-iteration-count: infinite;
  }

  @keyframes wave {
    0% { transform: rotate(0deg); }
    /* 25% { transform: rotate(20deg); }  */
     50% { transform: rotate(0deg); } 
    75% { transform: rotate(-20deg); }
    /* 100% { transform: rotate(0deg); } */
  }

  .navbar {
  position: fixed;
  top: 0;
  left: 0;
  right: 0;
  display: flex;
  justify-content: flex-end;
  background-color: rgb(23,28,40);
  z-index: 9999;
  
  }
  
  .navbar ul {
    list-style-type: none;
    margin: 0;
    padding: 0;
    display: flex;
    flex-direction: row;
    
  }

  .navbar li {
    margin: 0;
  }

  .navbar li a {
    font-family: 'Montserrat' , sans-serif;
    display: block;
    color: whitesmoke;
    text-align: center;
    padding: 14px 16px;
    text-decoration: none;
  }
  
  .navbar li a:hover {
    background-color: rgb(255, 0, 0);
  }

  .about-me h1 {
    font-family: 'Montserrat' , sans-serif;
    color: rgb(0, 0, 0);
    text-align: left;
    margin-top: 4%;
    margin-left: 5%;
  }

  #web-dev{
    position: absolute;
    margin-left: 150px;
    width: 30%;
    height: 30%;
  }

  .about-me p {
    font-family: 'Montserrat' , sans-serif;
    color: rgb(255, 255, 255);
    font-size: larger;
    text-align: left;
    line-height: 1.53em;
    width: 50%;
    margin-left: 5%;
  }

  .logos {
    margin-left: 5%;
  display: flex;
}

 .logos img {
  border-radius: 50%;
  width: 40px;
  height: 40px;
  margin: 5px;

} 



.button-container {
  display: flex;
  margin-top: 1%;
  margin-left: -66%;
  justify-content: center; /* aligns buttons horizontally */
  align-items: center; /* aligns buttons vertically */
}

#contact-btn {
  background: linear-gradient(to bottom, #ff0000, #590000);
  border: none;
  border-radius: 5px;
  margin-right: 260px; 
  color: white;
  margin-top: 2%;
  font-size: 18px;
  padding: 10px 20px;
  text-align: center;
  position: absolute;
  text-shadow: 1px 1px 1px black;
  transition: all 0.3s ease;
  transform-style: preserve-3d;
}

#resume {
  background: linear-gradient(to bottom, #ff0000, #590000);
  border: none;
  border-radius: 5px;
  margin-left: 150px;  
  color: white;
  font-size: 18px;
  margin-top: 2%;
  position: absolute;
  padding: 10px 20px;
  text-align: center;
  text-shadow: 1px 1px 1px black;
  transition: all 0.3s ease;
  transform-style: preserve-3d;
} 

#contact-btn:hover, #resume:hover {
  
  box-shadow: 0 0 10px rgba(153, 103, 103, 0.8);
}

#education h1 {
    font-family: 'Montserrat' , sans-serif;
    color: rgb(255, 255, 255);
    font-size: 180%;;
    /* font-size: large; */
    text-align: left;
    margin-top: 4%;
    margin-left: 5%;
    scroll-behavior: smooth;
  }

  #education img {
    margin-left: -84%;
    border-radius: 50%;
    margin-top: 25px; 
    width: 120px;
    height: 120px;
  
  }

  .education-container p {
    font-family: 'Montserrat' , sans-serif;
    font-size: larger;
    color: rgb(255, 255, 255);
    margin-left: 13%;
    margin-top: -7%;
    line-height: 1.53em;
    width: 25%;
    /* margin:5px; */
  }

  .college-container p {
    font-family: 'Montserrat' , sans-serif;
    font-size: larger;
    color: rgb(255, 255, 255);
    margin-left: 15%;
    margin-top: -7%;
    line-height: 1.53em;
    width: 18%;
    
    /* margin:5px; */
  }

  .education-container hr {
  /* Other styles... */
  animation-name: slideFromRight;
  animation-duration: 1s;
  animation-timing-function: ease-out;
  animation-delay: 0s;
  animation-fill-mode: forwards;
  opacity: 0;
  transform: translateX(100%);
}

@keyframes slideFromRight {
  0% {
    transform: translateX(100%);
    opacity: 0;
  }
  100% {
    transform: translateX(0);
    opacity: 1;
  }
}



#what{
  font-family: 'Montserrat' , sans-serif;
    color: rgb(255, 255, 255);
    text-align: left;
    line-height: 1.53em;
    width: 50%;
     margin-left: 45%; 
     margin-top: 1%;
     scroll-behavior: smooth;
  
}

#what {
  /* Other styles... */
  animation-name: slideFromRight;
  animation-duration: 1s;
  animation-timing-function: ease-out;
  animation-delay: 0s;
  animation-fill-mode: forwards;
  opacity: 0;
  transform: translateX(100%);
}

@keyframes slideFromRight {
  0% {
    transform: translateX(100%);
    opacity: 0;
  }
  100% {
    transform: translateX(0);
    opacity: 1;
  }
}

#web{
  margin-left: -55%;
  width:30%;
  height:30%;
  margin-top: -5%;
}

#web {
  /* Other styles... */
  animation-name: slideFromRight;
  animation-duration: 1s;
  animation-timing-function: ease-out;
  animation-delay: 0s;
  animation-fill-mode: forwards;
  opacity: 0;
  transform: translateX(100%);
}

@keyframes slideFromRight {
  0% {
    transform: translateX(100%);
    opacity: 0;
  }
  100% {
    transform: translateX(0);
    opacity: 1;
  }
}
.tech-logos {
  position: absolute;
  top: 1040px;
  margin-left: 450px;
}

.tech-logos img {
  width:5%;
  height: 6%;
  animation-name: slideFromRight;
  animation-duration: 1s;
  animation-timing-function: ease-out;
  animation-delay: 0s;
  animation-fill-mode: forwards;
  opacity: 0;
  transform: translateX(100%);
}

@keyframes slideFromRight {
  0% {
    transform: translateX(100%);
    opacity: 0;
  }
  100% {
    transform: translateX(0);
    opacity: 1;
  }
}

.skills{
  font-family: 'Montserrat' , sans-serif;
  font-size: larger;
    color: rgb(255, 255, 255);
    text-align: left;
    line-height: 1.53em;
    width: 50%;
    margin-left: 43%;
    margin-top: -20%;
}
.skills {
  /* Other styles... */
  animation-name: slideFromRight;
  animation-duration: 1s;
  animation-timing-function: ease-out;
  animation-delay: 0s;
  animation-fill-mode: forwards;
  opacity: 0;
  transform: translateX(100%);
}

@keyframes slideFromRight {
  0% {
    transform: translateX(100%);
    opacity: 0;
  }
  100% {
    transform: translateX(0);
    opacity: 1;
  }
}


#experiences h1 {
    font-family: 'Montserrat' , sans-serif;
    color: rgb(255, 255, 255);
    text-align: left;
    margin-top: 10%;
    margin-left: 5%;
    scroll-behavior: smooth;
  }
  .test-experience {
   display: flex;
    flex-direction: row;
    margin:20px;
    
   
}

  .card-experience {
    width: 500px;
    margin-left: 500px;
  /* Add shadows to create the "card" effect */
  box-shadow: 0 4px 8px 0 rgba(208, 0, 0, 0.2);
  transition: 0.3s;

  
}

/* On mouse-over, add a deeper shadow */
.card-experience:hover {
  box-shadow: 8px 8px 16px 16px rgba(185, 0, 0, 0.2);
}

/* Add some padding inside the card container */
.container-experience{
  padding: 2px 16px;
  margin:5px;
}
.container-experience h4 {
  font-family: 'Montserrat' , sans-serif;
    color: rgb(255, 255, 255);
    font-size: large;
}

.container-experience p {
  font-family: 'Montserrat' , sans-serif;
    color: rgb(255, 255, 255);
    font-size: large;
}
#folio {
  width: 20%;
}

#learnlive {
  position: absolute;
  margin-top: 20px;
  margin-left: -70px;
  height: 10%;
  width: 10%;
}

#vm {
  position: absolute;
  margin-top: 20px;
  margin-left: -70px;
  height: 10%;
  width: 10%;
}

#gymfit {
 
  position: absolute;
  margin-top: 20px;
  margin-left: -70px;
  height: 10%;
  width: 10%;

}

#carbo {
  position: absolute;
  margin-top: 20px;
  margin-left: -70px;
  height: 10%;
  width: 10%;
}

.container h4{
  margin-top: 40%;
  font-family: 'Montserrat' , sans-serif;
    color: rgb(255, 255, 255);
    font-size: large;
} 

.container p{
  font-family: 'Montserrat' , sans-serif;
    color: rgb(255, 255, 255);
    font-size: large;

}



 #projects h1 {
  font-family: 'Montserrat' , sans-serif;
    color: rgb(255, 255, 255);
    text-align: left;
    margin-top: 4%;
    margin-left: 5%;

 } 

 #blogs h1 {
    font-family: 'Montserrat' , sans-serif;
    color: rgb(255, 255, 255);
    text-align: left;
    margin-top: 4%;
    margin-left: 5%;
    scroll-behavior: smooth;
  }

  #blogs h2 {
    font-family: 'Montserrat' , sans-serif;
    color: rgb(255, 255, 255);
  }
  
.test-blogs {
    display: flex; 
    flex-direction: row;
    margin: 20px;
   
}

.card-blogs {
    /* Add shadows to create the "card" effect */
    width: 350px;
    height: 300px;
    margin: 10px;
    margin-left: 100px;
  box-shadow: 0 4px 8px 0 rgba(57, 56, 56, 0.2);
  transition: 0.3s;
   
}

.card-blogs:hover {
  box-shadow: 0 8px 16px 0 rgba(255, 0, 0, 0.2);
  /* width: 550px;
  height: 400px; */
}




.container-blogs h4  {
   /* margin-top: 10%; */
  font-family: 'Montserrat' , sans-serif;
    color: rgb(255, 255, 255);
    font-size: large;
}

.container-blogs p {
   font-family: 'Montserrat' , sans-serif;
    color: rgb(255, 255, 255);
    font-size: large;
}
.container-blogs p,
.container-blogs button {
  
  display: none;
  opacity: 0;
}

.card-blogs:hover .container-blogs p,
.card-blogs:hover .container-blogs button {
  display: block;
  opacity: 1;
  transition: opacity 0.3s;

}
  
#view-blog1{
  background: linear-gradient(to bottom, #ff0000, #590000);
  border: none;
  border-radius: 5px;
  margin-left: 130px; /* add some margin to the right */
  margin-top: 15px;
  color: white;
  font-size: 18px;
  padding: 10px 20px;
  text-align: center;
  text-shadow: 1px 1px 1px black;
  transition: all 0.3s ease;
  transform-style: preserve-3d;
}
#view-blog2{
  background: linear-gradient(to bottom, #ff0000, #590000);
  border: none;
  border-radius: 5px;
  margin-left: 135px; /* add some margin to the right */
  margin-top: 15px;
  color: white;
  font-size: 18px;
  padding: 10px 20px;
  text-align: center;
  text-shadow: 1px 1px 1px black;
  transition: all 0.3s ease;
  transform-style: preserve-3d;
}

#view-blog3 {
  background: linear-gradient(to bottom, #ff0000, #590000);
  border: none;
  border-radius: 5px;
   margin-left: 135px; /* add some margin to the right */
  margin-top: 15px;
  color: white;
  font-size: 18px;
  padding: 10px 20px;
  text-align: center;
  text-shadow: 1px 1px 1px black;
  transition: all 0.3s ease;
  transform-style: preserve-3d;
}

  
 #certifications h1 {
    font-family: 'Montserrat' , sans-serif;
    color: whitesmoke;
    text-align: left;
    margin-top: 4%;
    margin-left: 5%;
    scroll-behavior: smooth;
  }
 
.test {
   display: flex;
    flex-direction: row;
    margin:20px;
   
}
.card {
  /* Add shadows to create the "card" effect */
  box-shadow: 0 4px 8px 0 rgba(208, 0, 0, 0.2);
  transition: 0.3s;
  
  
}

/* On mouse-over, add a deeper shadow */
.card:hover {
  box-shadow: 8px 8px 16px 16px rgba(185, 0, 0, 0.2);
}

/* Add some padding inside the card container */
.container{
  padding: 2px 16px;
  margin:5px;
  
}

 img {
  width: 50%;
 }

 /* .container {

} */




#coursera{
  margin-top: 12.6%;
}

 #udemy {
  /* height: 77%;
  width: 77%;  */
  margin-top: 32.6%;
} 

#solo{
  height: 100%;
  width: 100%;
  margin-top: 8.6%;
}

#azure {
  margin-top: 20%;
}
#solo-btn 
{
  background: linear-gradient(to bottom, #ff0000, #590000);
  border: none;
  border-radius: 5px;
  margin-left: -40px; 
  color: white;
  margin-top: -1%;
  font-size: 10px;
  padding: 5px 10px;
  text-align: center;
  position: absolute;
  text-shadow: 1px 1px 1px black;
  transition: all 0.3s ease;
  transform-style: preserve-3d;
}
#aws-cloud-btn
{
  background: linear-gradient(to bottom, #ff0000, #590000);
  border: none;
  border-radius: 5px;
  margin-left: -40px; 
  color: white;
  margin-top: -1.5%;
  font-size: 10px;
  padding: 5px 10px;
  text-align: center;
  position: absolute;
  text-shadow: 1px 1px 1px black;
  transition: all 0.3s ease;
  transform-style: preserve-3d;
}

#azure-btn {
  background: linear-gradient(to bottom, #ff0000, #590000);
  border: none;
  border-radius: 5px;
  margin-left: -40px; 
  color: white;
  margin-top: -1%;
  font-size: 10px;
  padding: 5px 10px;
  text-align: center;
  position: absolute;
  text-shadow: 1px 1px 1px black;
  transition: all 0.3s ease;
  transform-style: preserve-3d;
}

#aws-cloud {
  margin-top: 20%;
}
.container-udemy h4{
  margin-top: 20%;
  font-family: 'Montserrat' , sans-serif;
    color: rgb(255, 255, 255);
    font-size: large;
} 



.container-certifications h4{
  margin-top: 10%;
  font-family: 'Montserrat' , sans-serif;
    color: rgb(255, 255, 255);
    font-size: large;
} 



.card {
  margin-left: 5%;
  width: 30%;

  display: inline-block;

  box-shadow:4px  4px 8px 8px rgba(185, 0, 0, 0.2);
  transition: 0.3s;
  border-radius: 5px; /* 5px rounded corners */
  
}

/* Add rounded corners to the top left and the top right corner of the image */
/* img {
  width:  100%;
} */
#contact {
  margin-left: 0%;
  scroll-behavior: smooth;

}


#contact h1 {
  font-family: 'Montserrat' , sans-serif;
    color: rgb(255, 255, 255);
    text-align: left;
    line-height: 1.53em;
    width: 50%;
    margin-left: 5%;

}

#contact h2 {
    font-family: 'Montserrat' , sans-serif;
    font-size: medium;
    color: rgb(255, 255, 255);
    text-align: left;
    line-height: 1.53em;
    width: 50%;
    margin-left: 5%;
  }

  #contact h3 {
    font-family: 'Montserrat' , sans-serif;
    font-size: large;
    color: rgb(255, 255, 255);
    text-align: left;
    line-height: 2.53em;
    width: 10%;
    margin-left: 5%;
  }

 

   #cnt {
  
  width: 25%;
  height: 25%;
    margin-top: -15%;
  margin-right: -50%; 

}  

hr {
  width: 50%;
  margin-left: 5%;
  margin-top: 2%;
  /* height: 2px; */
  background-color: black;
  /* transition: width 0.3s ease-in-out; */
}
/* 
hr:hover {
  width: 4px;
}  */


  
footer {
  position: relative;
  left: 0;
  bottom: 0;
  width: 100%;
  color: rgb(255, 255, 255);
  text-align: center;
  height:7%;
}

footer img {
  border-radius: 50%;
  width: 40px;
  height: 40px;

  margin-right: 30%; 
 margin: 2px;
} 

.go-top {
  position: fixed;
  bottom: 20px;
  right: 20px;
  background-color: rgb(255, 0, 0);
  color: #fff;
  border: none;
  border-radius: 50%;
  width: 50px;
  height: 50px;
  font-size: 24px;
  cursor: pointer;
  transition: background-color 0.3s ease;
  animation: bounce 2s infinite;
}

@keyframes bounce {
  0% {
    transform: translateY(0);
  }
  50% {
    transform: translateY(-10px);
  }
  100% {
    transform: translateY(0);
  }
}
/* .go-top:hover {
  background-color: #7b0000;
} */

#top {
   width: 55%; 
  height: 55%; 
  margin-top: -25%;
  position: fixed;
  margin-left: -25%;
  filter: 'invert(1)';
}

</style>
