name: The Technical Writing Monkey
author: Carlos
markdown: kramdown
safe: true
lsi: true
baseurl: ""


kramdown:
 auto_ids: false
 footnote_nr: 1
 entity_output: as_char
 toc_levels: 1..6
 smart_quotes: lsquo,rsquo,ldquo,rdquo
 use_coderay: true
 parse_span_html: true
 parse_block_html: true

---
layout: base
title: "Welcome"
---

<article data-hd-class="concept">
<h1>{{ page.title }}</h1>
<p>Welcome to {{ site.name }}. Please use the navigation bar to browse the site.
	
</p>

</article>


---
layout: base
title: "Nutritional recommendations for monkeys"
---
<article data-hd-class="task"> 
<h1>{{ page.title }}</h1> 
<p>Recommended food items for monkeys.</p> 
<div class="table-responsive">
<table class="table table-striped">
  <tr>
    <th>Food item</th>
    <th>Recommendation</th>
  </tr>
  <tr>
    <td>Apple</td>
    <td>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</td>
  </tr>
  <tr>
    <td>Banana</td>
    <td>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</td>
  </tr>
  <tr>
    <td>Egg</td>
    <td>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</td>
  </tr>
 
  </table>
</div>
</article>

HDITA template for Technical Writing at Virginia Tech (Summer 2014)
=================

##Template for Technical Writing HDITA experiment at Virginia Tech

1. Create your github.io repository following the instructions on the [Github Pages site](https://pages.github.com)
2. Download or clone this template (links on the right sidebar of this text)
3. Save the template to your local `username.github.io` repository
2. Update the site's title and information in the `_config.yml` file
3. Open and modify my sample files for tasks, concepts, and references
    * See that I have named the concepts as `c-something.html`, the tasks as `t-something.html`, and the references as `r-something.html`. That makes it easier to tell what information type they follow.
4. Copy the task samples for as many tasks as you need for your project, writing your own content
5. Pay attention to the YAML metadata on every topic, giving it a unique name
6. Save your images, as needed, in the images folder. Give them simple names
7. Update the `topics.yml` file inside the `_data` folder to create your map. Copy for as many topics as needed. Avoid tab spaces
8. Commit your changes to your `username.github.io` repository
9. Enjoy your lovely site in big-screen and mobile devices.




---
layout: base
title: "How to put a monkey inside a box"
---
<article data-hd-class="task"> 
<h1>{{ page.title }}</h1> 
<p>Hide your monkey in a box if your friends are coming for lunch.</p> 
<section data-hd-class="task/context"> 
	<h2>Context</h2>
<p>Hide the monkey only if he approves it. </p>
</section> 
<section data-hd-class="task/prereq"> 
<h2>Pre-requisites</h2>  
<ul> 
<li>1 monkey</li> 
<li>1 box</li>
</ul> 
</section> 
<section data-hd-class="task/steps-informal"> 
<h2>Steps</h2>
<ol> 
<li>Grab the monkey</li> 
<li>Get him inside the box
<p><strong>Be sure to find a box bigger than the monkey</strong></p>
</li>
<li>Run away</li> 
</ol> 
</section>
<section data-hd-class="task/example">
<h2>Example</h2>
<p>Your monkey should be happy in the box <em>(Figure 4)</em></p>
<figure>
  <img src="images/boxmonkey.jpg" />
  <figcaption>Figure 4: Happy monkey inside a box</figcaption>
</figure>
</section>
</article>


---
layout: base
title: "How to feed a monkey"
---
<article data-hd-class="task"> 
<h1>{{ page.title }}</h1> 
<p>Feeding monkeys can be difficult. They like bananas but we will give them apples.</p> 
<section data-hd-class="task/context"> 
<h2>Context</h2>
<p>Be sure to do this only when monkey is hungry.</p> 
</section> 
<section data-hd-class="task/prereq"> 
<h2>Ingredients</h2>  
<ul> 
<li>1 hungry monkey</p> 
<li>1 apple</p>
</ul> 
</section> 
<section data-hd-class="task/steps-informal"> 
<h2>Steps</h2>
<ol> 
<li>Hold the monkey
<p><strong>Be careful! Monkeys can be aggressive when hungry</strong></p>
</li> 
<li>Let the monkey smell the apple <em>(Figure 2)</em></li>
<figure>
  <img src="images/applemonkey.jpg" />
  <figcaption>Figure 2: Monkey smelling an apple</figcaption>
</figure>
<li>Let the monkey eat the apple</li>
</ol> 
</section>
<section data-hd-class="task/postreq"> 
<h2>Post-requisites</h2>
<ul>
	<li>Clean the kitchen.</li> 
</ul>
</section> 
</article>

---
layout: base
title: "How to give iced tea to a monkey"
---
<article data-hd-class="task"> 
<h1>{{ page.title }}</h1> 
<p>Give iced tea to your monkey to keep him fresh during the summer.</p> 

<section data-hd-class="task/prereq"> 
<h2>Pre-requisites</h2>  
<ul> 
<li>1 monkey</li> 
<li>1 bottle of iced tea</li>
</ul> 
</section> 
<section data-hd-class="task/steps-informal"> 
<h2>Steps</h2>
<ol> 
<li>Hold the monkey</li> 
<li>Give him the bottle</li>
<li>Enjoy the moment</li>
</ol> 
</section>
<section data-hd-class="task/example">
<h2>Example</h2>
<p>Your monkey should look like this <em>(Figure 3)</em></p>
<figure>
  <img src="images/teamonkey.jpg" />
  <figcaption>Figure 3: Fresh monkey with iced tea</figcaption>
</figure>
</section>
</article>

