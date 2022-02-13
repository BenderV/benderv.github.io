<template>
<div class="pure-g">
  <div class="pure-u-0 pure-u-md-1-5"></div>
  <div class="pure-u-1 pure-u-md-3-5 l-box">
    <h3>About me</h3>
    <br/>
    <p>Engineer. Expertise in Tech, Data Science, Deep Learning.<br/></p>
    <p>I'm interested in Mobility, Biology & AI.</p>

    <h3>Experiences</h3>
    <ul>
      <li>(Current) Tech Lead @ <a href="https://www.norauto.com">Norauto</a>, help with the digital transformation.</li>
      <li>Data Scientist @ <a href="https://www.vroomly.fr">Vroomly</a>, built the most extensive & precise online pricer of automotive market.</li>
      <li>Co-Founder @ <a href="https://www.fluximmo.com">Fluximmo</a>, built the fastest scraping engine in the real estate.</li>
      <li>Deep Learning Expert @ <a href="https://www.doctrine.fr">Doctrine</a>, built state-of-the-art NLP projects.</li>
      <li>Intern @ <a href="https://www.wiredcraft.com">Wiredcraft</a>, built a website for the <a href="https://wiredcraft.com/work/the-myanmar-elections/">first democratic election in Myanmar</a>.</li>
    </ul>

    <h3>Blog</h3>
    <ul>
      <li><a href="https://wiredcraft.com/blog/how-to-get-a-job-the-bot-way/">How to get a Job (the bot way)</a></li>
    </ul>

    
    <!-- <h3><span style="color: red;">Interesting Projects (to remove ?)</span></h3>
    <ul>
      <li><a href="https://www.appartenir.com">appartenir.com</a>, real estate search assistant (in paris)</li>
      <li><a href="https://github.com/BenderV/self_driving_car">Self-driving car</a>, a mini self-driving car. <a href="https://olympe.quip.com/oDncAFFJdbRC"><i style="color:#e91e63;">[Report]</i></a></li>
      <li><span style="color:black">Outliers</span>, a sport prediction algorithm to bet online <i style="color:#e91e63;">(unpublished)</i></li>
      <li><a href="https://github.com/BenderV/PrisonerDilemma">Prisoner's dilemma</a>, Finding Game Theory equilibrium with machine learning agents using the prisoner's dilemma</li>
      <li><a href="http://travel.benderv.com/">UTTravel</a>, website to help students to find a school abroad</li>
      <li><a href="https://github.com/BenderV/pyorg">Pyorg</a>, small library to organize files with scripts.</li>
      <li><a href="/gps">GPS</a>, jupyter notebook with analysis of GPS data <a href="https://github.com/BenderV/GPS">(arduino code)</a> </li>
    </ul> -->


    <h3>Contact</h3>
    <ul>
      <li>Mail : <a href="mailto:benderville@gmail.com">benderville@gmail.com</a></li>
      <li>Github : <a href="https://github.com/BenderV">github.com/BenderV</a></li>
      <li>CV : <a href="files/cv-benjaminderville.pdf"> curriculum vitae (pdf)</a></li>
      <!-- <li>Twitter : <a href="https://twitter.com/ben_derv">twitter.com/ben_derv</a></li> -->
    </ul>

    <h3>Quotes</h3>
    <blockquote>
      <p>I very much recommend you get Benjamin on your team; he interned at Wiredcraft and was a pleasure to work with. He was in charge of a small part of our software platform for the election of Myanmar (https://wiredcraft.com/blog/myanmar-election-open-api/).
      <br/>
      He's wicked smart, "full-stack", nerdy and most importantly self driven. I'd get him back on my team any time.</p>
      <footer>
       - <cite>Ronan Berder, CEO of Wiredcraft</cite>
      </footer>
    </blockquote>    
    <blockquote>
      <p>I'm a very good friend of Benjamin and he knows how to handle complicated tasks and is very passionate about his (many) projects. He did a lot of online classes and tried a many different technologies. And as a side note, he is also a very cool guy, have fun working with him.</p>
      <footer>
       - <cite>Dorian Marié, Nomad Programmer</cite>
      </footer>
    </blockquote>

  </div>
  <div class="pure-u-0 pure-u-md-1-5"></div>
</div>
</template>

<style>
    /* BLOCKQUOTE */ 
    blockquote {
      border-left: 10px solid;
      margin: 1.5em 10px;
      padding: 0.5em 10px;
      quotes: "\201C""\201D""\2018""\2019";
    }
    blockquote:before {
      content: open-quote;
      font-size: 3em;
      line-height: 0.1em;
      margin-right: 0.25em;
      vertical-align: -0.4em;
    }
    blockquote:after {
      content: close-quote;
      font-size: 0;
    }
    blockquote p {
      display: inline;
    }
    /* END BLOCKQUOTE */

    .pure-g > div {
        -webkit-box-sizing: border-box;
        -moz-box-sizing: border-box;
        box-sizing: border-box;
    }
    .l-box {
      padding: 1em;
    }
</style>
