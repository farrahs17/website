<template>
  <div class="root">
    <div class="menu">
      <h1>Farrah Shawky</h1>
      <ul class="menu-list">
        <li><a href="#about">About</a></li>
        <li><a href="#resume">Resume</a></li>
        <li><a href="#contact">& Contact</a></li>

      </ul>
    </div>
    <div class="content" id="about">
      <p>Some stuff about me blah blah blah</p>
      <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Ducimus officia beatae, iure provident cumque ad quo dolor repudiandae ratione qui quisquam placeat blanditiis, a facere maxime architecto, magnam accusantium quaerat.</p>
    </div>
    <div class="resume" id="resume">
      <h2>Work Experience</h2>
      <div class="row">
        <h3>Full Stack Web Developer - Spare Payments</h3>
        <h4>2019 - Present</h4>
        <ul>
          <li>Working with an Agile Methodology by collaborating and communicating fast and often with cross-functional teams even through the COVID-19 Pandemic
          </li>
          <li>Discussing the design and implementing a fully responsive website redesign as a part of implementing a new marketing strategy</li>
          <li>Working with the UX designer and implementing front-end views for all company web appsCollaborating in writing and testing RESTful APIs for the core products of Spare.
          </li>
          <li>Designing and developing API documentation using Swagger for company apps that helped in scaling the products and on-boarding new members</li>
          <li>Researching and creating a style guide with team members to ease transitions for newcomers and improve the codebase.</li>
        </ul>
      </div>
      <div class="row">
        <h3>Copywriter - Freelance</h3>
        <h4>2018 - Present</h4>
      </div>
      <h2>Education</h2>
      <div class="row">
        <h3>FireUp BootCamp - AlMakinah</h3>
        <h4>March - August 2019</h4>
        <p>A 5-month intensive full stack course for GearUp top students exploring more deeply into web development technologies and fundamental computer science principles.</p>
      </div>
      <div class="row">
        <h3>GearUp BootCamp - AlMakinah</h3>
        <h4>January - March 2019</h4>
        <p>
          A 2-months introductory bootcamp about the basics of web development and the latest technologies and industry practices.
        </p>
      </div>
      <div class="row">
        <h3>BBA, Marketing</h3>
        <h4>2014 - 2018</h4>
        <p>J. Mack Robinson College of Business, 
            Georgia State University Joint Program
            Cairo University
          </p>
      </div>
      <h2>Skills</h2>
      <div class="row"></div>
    </div>
    <div class="contact" id="contact">
      <ul>
        <li>Email: Farrah.shawky.95@gmail.com</li>
        <li>Linkedin</li>
        <li>Github</li>
      </ul>
    </div>
  </div>
   
   
</template>

<script>
export default {
  name: 'Home',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
  .root {
    margin: 0;
    }

  .menu {
    display: flex;
    flex-direction: column;
    height: 100vh;
    justify-content: center;
    align-items: center;

    &-list {
      list-style: none;
      display: flex;
      justify-content: space-between;
      width: 33%;
      padding: 0 1rem;
      margin: 0;
      a {
        text-decoration: none;
        color: #2c2e32;
      }
      a:hover {
        color:#4f5052;
        text-decoration: underline;
      }
    }

    h1 {
      color: #272727;
      font-size: 60px;
      text-decoration: underline;
      text-decoration-thickness: 2px;
      margin-bottom: 0;
    }
  }

  .content {
    height: 100vh;
  }

  .resume{
    min-height: 100vh;
    display: flex;
    flex-direction: column;
    padding: 3rem;
    
  }

  .contact {
    height: 100vh;
  }
</style>
