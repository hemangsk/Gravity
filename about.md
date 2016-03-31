---
layout: page
title : About
permalink: /about/
---

<h2>Gravity</h2>
<p>Minimal, text based, liberal Jekyll theme<br>for sharing your awesome ideas.</p>
<br>
<center><p ><strong><span class="manual">Get up and running with</span> Gravity</strong></p></center>
<br>
<div class="manual-post">
  <div class="manual manual-title">
  <strong>Posting</strong>
  </div>
<p>  <div class="manual-content">

      - Create a .markdown file inside <code class="highlighter-rouge">_posts</code> folder.<br>
      - Name the file according to the format YY-MM-DD-[short name for your post].<br>  <code>2016-03-30-i-love-design.markdown</code><br>
      - Write the <a href="jekyll">Front Matter</a> and content in the file.<br>
      <div class="example">
        <span class='manual'>FORMAT</span><BR>
        <code>---<br>
        layout: post | default | page<br>
        title:  String<span class="hint"> Post Title</span><br>
        date:   Time Stamp<br>
        categories: String | Array of Strings<span class="hint"> Category / Categories </span><br>
        ---
      </code><br>
      </div>
      <div class="example">

        <code>---<br>
        layout: post<br>
        title:  "The One with the Blackout"<br>
        date:   2016-03-30 19:45:31 +0530<br>
        categories: ["life", "friends"]<br>
        ---
      </code>
      </div>


  </div>
</p>
</div>
<br>
<div class="manual-post">
  <div class="manual manual-title">
  <strong>Create Pages</strong>
  </div>
<p>  <div class="manual-content">

      - Create a .md file in the root directory.<br>
      - Name the file with the desired page link name.<br>  <code>about.md</code><br><code>design.md</code><br>
      - Write the <a href="jekyll">Front Matter</a> and content in the file.
      <div class="example">
        <span class='manual'>FORMAT</span><BR>
        <code>---<br>

          layout: page<br>
          title: String <span class="hint">Title of the webpage</span><br>
          permalink: / String / <span class="hint">Permalink for the webpage</span><br>
          tagline: String <span class="hint">Optional Gravity Feature : Tagline for the page</span><br>
          ---
      </code><br>
      </div>
      <div class="example">

        <code>---<br>
        layout: page<br>
        title:  "Science"<br>
        permalink:   /science/ <br>
        tagline : "Humanity is overrated." <br>
        ---
      </code>
      </div>


  </div>
</p>
</div>
<br>
<div class="manual-post">
  <div class="manual manual-title">
  <strong>Create Archives/ Category Pages</strong><br>
</div><br>
<div class="archiveIntro">
  <p>
    Introducing <strong>Archive Pages</strong>.<br></p>
  <span class="archive-intro">  You can display a list of all the post corresponding to a particular category on a standalone Page using the <code>'archive'</code> layout.
</span>
</div>
<br>

<p>  <div class="manual-content">

      - Create a .md file in the root directory.<br>
      - Name the file. Preferred name will be the name of the category<br>  <code>life.md</code><br>
      - Write the <a href="jekyll">Front Matter</a> and content in the file.
      <div class="example">
        <span class='manual'>FORMAT</span><BR>
        <code>---<br>

          layout: archive<span class="hint"> Archive Page Layout</span> <br>
          title: String <span class="hint">Title of the webpage</span><br>
          permalink: / String / <span class="hint">Permalink for the webpage</span><br>
          tagline: String <span class="hint"> Tagline for the page</span><br>
          category : String <span class="hint"> Name of the category of which the page will show posts.</span><br>
          ---
      </code><br>
      </div>
      <div class="example">

        <code>---<br>
        layout: archive<br>
        title:  "Design"<br>
        permalink : "Design"<br>
        category: "design"<br>
        tagline: "It's all about perception."<br>
        ---
      </code>
    </div><br>
  </div>
</p>
</div>
