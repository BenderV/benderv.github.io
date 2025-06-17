<template>
<div class="pure-g">
  <div class="pure-u-0 pure-u-md-1-5"></div>
  <div class="pure-u-1 pure-u-md-3-5 l-box">
    <h3>About me</h3>
    <br/>
    <p>Engineer. Expertise in Tech, Data, Deep Learning.<br/></p>

    <h3>Experiences</h3>
    <ul>
      <li>Founder @ <a href="https://www.myriade.ai">Myriade</a>, building the most advanced AI business analyst.</li>
      <li>Product Manager @ <a href="https://www.norauto.com">Norauto</a>, not sure I did help, but it was great experience.</li>
      <li>Tech Lead @ <a href="https://www.norauto.com">Norauto</a>, help with the digital transformation.</li>
      <li>Data Scientist @ <a href="https://www.vroomly.fr">Vroomly</a>, built the most extensive & precise online pricer of automotive market.</li>
      <li>Co-Founder @ <a href="https://www.fluximmo.com">Fluximmo</a>, built the fastest scraping engine in the real estate.</li>
      <li>Deep Learning Expert @ <a href="https://www.doctrine.fr">Doctrine</a>, built state-of-the-art NLP projects.</li>
      <li>Intern @ <a href="https://www.wiredcraft.com">Wiredcraft</a>, built a website for the <a href="https://wiredcraft.com/work/the-myanmar-elections/">first democratic election in Myanmar</a>.</li>
    </ul>

    <h3>Blog</h3>
    <ul>
      <li><a href="https://wiredcraft.com/blog/how-to-get-a-job-the-bot-way/">How to get a Job (the bot way)</a></li>
      <li><a href="/voting_scheme">Paper Review : “Manipulation of Voting Schemes: A General Result (2975, 1973)” by Allan Gibbard</a></li>
    </ul>

    <h3>Contact</h3>
    <ul>
      <li>Mail : <a href="mailto:ben.derville@gmail.com">ben.derville@gmail.com</a></li>
      <li>Github : <a href="https://github.com/BenderV">github.com/BenderV</a></li>
      <!-- <li>Twitter : <a href="https://twitter.com/benderville">twitter.com/benderville</a></li> -->
    </ul>
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
