<template>
    <section class="container-md d-flex" id="about-me">
      <div class="row">
      <div class="col-10 mx-auto">
        <div class="row">
          <div className="title col-6 mx-auto">
            <h2>About Me</h2>
            <p class="links">
              <a href='https://www.linkedin.com/in/kevinkelbach/' target="_blank">LinkedIn</a>
              <a href='https://github.com/Kelbach' target="_blank">Github</a>
            </p>
          </div>
        </div>
        <img class="my-2 mx-auto d-block" id="bio-image" src='../../dist/assets/CJH_5439crop.jpg' alt="K. Kelbach " />
      
        <article class="row">
          <ul class="mx-auto">
            <li>Hi, I'm Kevin </li>
            <li>Graduated the Full-Stack Coding Bootcamp from CWRU in Feb. 2022</li>
            <li>Reliable and flexible problem solver </li>
            <li>I have a background in physics, mathematics, music and audio engineering </li>
          </ul>
          <p class="col-8 mx-auto my-3">  
            Full-stack web developer leveraging a physics background to efficiently problem solve and build a more intuitive user experience on the web. 
            Completed a certificate in full stack development from the Case Western Reserve University Coding Bootcamp (Feb. 2022) and acquiring newly developed skills in JavaScript, CSS, SQL, MERN and responsive web design. 
            Utilizing innovative problem solving and passion to develop apps, with a focus on mobile-first design and development. 
            With each project, my aim is to best engage my audience for an impactful user experience. 
            Over the course of bootcamp, I applied aspects of MVC and OOP in a recent group project designed for community interaction and worked on a team of four to develop a MERN application that connects users through a passion for video games. 
            Excited to leverage my skills as part of a fast-paced, quality-driven team to build better user experiences on the web. <br/>
            I look forward to learning more and using my creativity and problem solving to build what I imagine.
          </p>
        </article>
      </div></div>
      </section>
</template>

<style scoped>
.links a {
  margin: 0.6rem;
}

img {
  width: 17rem;
  height: 17rem;
  border-radius: 100%;
}

article ul li {
  font-size:1.0rem;
}

article p {
  font-size: 1.2rem;
  margin-top: 2rem;
}

</style>