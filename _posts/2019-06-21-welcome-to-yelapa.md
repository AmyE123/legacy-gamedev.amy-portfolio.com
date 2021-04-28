---
layout: post
title:  "Welcome To Yelapa"
type: "Game Development"
color: "background-color: seagreen"
summary: "Welcome To Yelapa is a Legend of Zelda inspired puzzle game, and it was made for the first gamejam I participated in! <small>(Portsmouth Uni Game Jam 2019)</small>"
author: amyelliott
date: '2019-06-21'
category: ['game-jam', 'csharp', 'design', 'level-design', 'ui-ux', 'unity']
thumbnail: /assets/img/posts/WelcomeToYelapa/welcometoyelapa.PNG
keywords: csharp, game design, design, level design, ui, ux, game jam
permalink: /blog/welcome-to-yelapa/
usemathjax: true
---

<!---Part of the collapsible group items // Ref: https://codepen.io/nhembram/pen/XKEJJp -->
<script>
     $('.panel-collapse').on('show.bs.collapse', function () {
        $(this).siblings('.panel-heading').addClass('active');
      });

      $('.panel-collapse').on('hide.bs.collapse', function () {
        $(this).siblings('.panel-heading').removeClass('active');
      });
</script>

<hr>

<!--- -------------------------------------------------------------- -->
<!--- This is for the status of the game, every game should have one -->
<!--- -------------------------------------------------------------- -->
<div class="status-card">
    <h6 style="text-align: center;">Status <a style="text-align: center;">Done</a> </h6> 

    <h6 style="text-align: center;">Project Type <a style="text-align: center;">Game Jam</a> </h6>   

    <h6 style="text-align: center;">Game Jam Duration <a style="text-align: center;">5 Days</a> </h6>    

    <h6 style="text-align: center;">Software Used <a style="text-align: center;">Unity, Photoshop, Tiled</a> </h6>    

    <h6 style="text-align: center;">Primary Roles <a style="text-align: center;">Design, Level Design, UI</a> </h6> 
</div>

<hr>

<!--- -------------------------------------------------------------------- -->
<!--- This is for the main description of the game, this is very important -->
<!--- -------------------------------------------------------------------- -->
<div class = "card">
    <h2 style="text-align: center;">About Welcome To Yelapa</h2>
    <p style="text-align: center;">Welcome To Yelapa is a Legend of Zelda inspired puzzle game, and it was made for the first gamejam I participated in! <br /> For this gamejam, I met Team Horsehead members like Joe, Oliver and Scott, and meeting them started me on my amazing game development journey! <br /> I learnt so much, and met so many amazing friends during this gamejam, it was truly a life changing experience for me.</p>
</div>

<!--- --------------------------------------------------------------------------------------------------------- -->
<!--- This is the Youtube footage of the game, followed by a collapsible with the gallery, which starts as open -->
<!--- --------------------------------------------------------------------------------------------------------- -->
<div style="text-align: center;"><iframe frameborder="0" src="https://itch.io/embed-upload/1501772?color=333333" allowfullscreen="" width="1044" height="664"><a href="https://horsehead.itch.io/gamejam-2019">Play Welcome to Yelapa on itch.io</a></iframe> </div>
<div class="control-card">  
    <h4 style="text-align: center;">Controls</h4>
    <li style="text-align: center;"> <strong>Move:</strong> Arrow Keys / W A S D</li>
    <li style="text-align: center;"> <strong>Pick up:</strong> Space</li>
    <li style="text-align: center;"> <strong>Throw:</strong> Space</li> 
    <p style="text-align: center;">The controls were designed to be as simple as possible, other than moving there is just one button.</p>
</div>

<div class="wrapper center-block">
  <div class="panel-group" id="accordion" role="tablist" aria-multiselectable="true">
  <div class="panel panel-default">
    <div class="panel-heading active" role="tab" id="headingOne">
      <h4 class="panel-title">
        <a role="button" data-toggle="collapse" data-parent="#accordion" href="#collapseGallery" aria-expanded="true" aria-controls="collapseGallery">
          Gallery
        </a>
      </h4>
    </div>
    <div id="collapseGallery" class="panel-collapse collapse in collapse show" role="tabpanel" aria-labelledby="headingOne">
      <div class="panel-body">
        <p>Here is a gallery of pictures which I have taken through the Game Jam, from this gallery you can see how we have approached making the levels, along with how the characters were concepted. <br /> </p>
        <div class="row">
          <div class="column">
            <img src="/assets/img/posts/WelcomeToYelapa/4.png">
            <img src="/assets/img/posts/WelcomeToYelapa/5.png">
          </div>

          <div class="column">
            <img src="/assets/img/posts/WelcomeToYelapa/6.png">
            <img src="/assets/img/posts/WelcomeToYelapa/7.png">
          </div>

          <div class="column">
            <img src="/assets/img/posts/WelcomeToYelapa/8.png">
            <img src="/assets/img/posts/WelcomeToYelapa/9-small.png">
          </div>

          <div class="column">
            <img src="/assets/img/posts/WelcomeToYelapa/10.PNG">
          </div>
        </div>      
      </div>
    </div>
  </div>
</div>

<hr>

<!--- --------------------------------------------- -->
<!--- This is the collapsible which I will be using -->
<!--- --------------------------------------------- -->
<div class="wrapper center-block">
  <div class="panel-group" id="accordion" role="tablist" aria-multiselectable="true">
  <div class="panel panel-default">
    <div class="panel-heading active" role="tab" id="headingOne">
      <h4 class="panel-title">
        <a role="button" data-toggle="collapse" data-parent="#accordion" href="#collapseOverview" aria-expanded="true" aria-controls="collapseOverview">
          Welcome To Yelapa: Development Overview
        </a>
      </h4>
    </div>
    <div id="collapseOverview" class="panel-collapse collapse in" role="tabpanel" aria-labelledby="headingOne">
      <div class="panel-body">
        <p>This Gamejam meant a lot to me, because it was the first one I participated in, and it was the Gamejam which connected me with Team Horsehead, the game development team which I am now proudly a part of. <br /> </p>
        <p>This Gamejam was hosted at the University of Portsmouth and it was a week long jam (34 hours in total) The themes were picked at random from Wikipedia, the themes were a lawyer who coached a basketball team, an African-American author and finally a small beach town called Yelapa. <br /> </p>
        <p>Our team decided to go for all three themes and combine them together, using the town as our setting, the author as the protagonist and the lawyer as the final boss.</p>
      </div>
    </div>
  </div>
  <div class="panel panel-default">
    <div class="panel-heading" role="tab" id="headingTwo">
      <h4 class="panel-title">
        <a class="collapsed" role="button" data-toggle="collapse" data-parent="#accordion" href="#collapsePlanning" aria-expanded="false" aria-controls="collapsePlanning">
          Planning & Concepting The Game
        </a>
      </h4>
    </div>
    <div id="collapsePlanning" class="panel-collapse collapse" role="tabpanel" aria-labelledby="headingTwo">
      <div class="panel-body">
        <p> When planning out the game, we decided to take inspiration from the newly announced Links Awakening (Switch) for the art style since it has such a nice bright and cheerful style, but we also wanted to combine that with the earlier Zelda games where you were locked to one screen at a time. I really like this approach to the art style as it allowed us to work on a game which interests us all. <i>(Everyone is a fan of Zelda right?!)</i> <br /> </p>
            <div class="row">
              <div class="column">
                <img src="/assets/img/posts/WelcomeToYelapa/3.png">
              </div>
              <div class="column">
                <img src="/assets/img/posts/WelcomeToYelapa/11.png">
              </div>
              <div class="column">
                <img src="/assets/img/posts/WelcomeToYelapa/1.jpg">
              </div>
              <div class="column">
                <img src="/assets/img/posts/WelcomeToYelapa/2.png">
              </div>
            </div> 
        <p> <br /> I made artwork for the characters inspired by Links Awakening art style, but I was also inspired by Animal Crossing, these sketches then got turned into amazing looking 3D models which were made and rigged and animated by our 3D modeller, Joe. <br /> </p>
            <div class="row">
              <div class="column-two">
                <img src="/assets/img/posts/WelcomeToYelapa/4.png">
              </div>
              <div class="column-two">
                <img src="/assets/img/posts/WelcomeToYelapa/5.png">
              </div>
            </div>
        <p> <br /> It was fun to talk to the team about how to approach this game, as we were firing lots of different ideas at each other, until we had one we were all happy with! Most of our planning was done through talking though, as this was a Game Jam so we didn't have the time to be making game design documents <br /> </p>
      </div>
    </div>
  </div>
  <div class="panel panel-default">
    <div class="panel-heading" role="tab" id="headingFour">
      <h4 class="panel-title">
        <a class="collapsed" role="button" data-toggle="collapse" data-parent="#accordion" href="#collapseTiled" aria-expanded="false" aria-controls="collapseTiled">
          Using Tiled To Make Levels
        </a>
      </h4>
    </div>
    <div id="collapseTiled" class="panel-collapse collapse" role="tabpanel" aria-labelledby="headingThree">
      <div class="panel-body">
        <p>Joe, one of our programmers, made a tool where we could make each level in text format and have it dynamically spawned at runtime, this would mean that we could put together levels very quickly just by changing a few lines in a text file. <br />
        We designed the maps in the map editing tool Tiled and used a Python script to convert it. <br />
        I used the editing tool Tiled for the first time, and using this and learning about how this Python script converted the map to text and worked with Unity helped me understand how some tools work, it was a very useful and interesting thing to learn.</p> <br />
        <div class="row">
            <div class="column-three">
            <img src="/assets/img/posts/WelcomeToYelapa/6.png">
            </div>
            <div class="column-three">
            <img src="/assets/img/posts/WelcomeToYelapa/7.png">
            </div>
            <div class="column-three">
            <img src="/assets/img/posts/WelcomeToYelapa/8.png">
            </div>
        </div>
        <p><br /> Doing this meant that we could make maps quickly and apply assets which was useful on the last day of the Game Jam where we had to crunch to get everything done (we left levels to last minute, we knew we shouldn't have). Oliver, one of our teams 3D Modellers, done a great job on making the 3D asset props which made our game come together and look nice! </p> <br />
        <div class="row">
            <div class="column-one">
            <img src="/assets/img/posts/WelcomeToYelapa/9.png"> <br />
            </div>
        </div>
    </div>
  </div>
    <div class="panel panel-default">
    <div class="panel-heading" role="tab" id="headingFive">
      <h4 class="panel-title">
        <a class="collapsed" role="button" data-toggle="collapse" data-parent="#accordion" href="#collapseBlog" aria-expanded="false" aria-controls="collapseBlog">
          Personal Blog
        </a>
      </h4>
    </div>
    <div id="collapseBlog" class="panel-collapse collapse" role="tabpanel" aria-labelledby="headingThree">
      <div class="panel-body">
         <p> During the Gamejams, on my way back home during the week, I wrote my own personal journal entries on how each day went for me, and what I’ve learnt. <br /> </p>
         <h5>Day 1</h5> 
         <img src="/assets/img/posts/WelcomeToYelapa/12.jpg" class="TextWrap-R"/> <p> The first day was pretty daunting, I was joining a group of people which I didn’t know and making a 3D game, in which I had no experience whatsoever in, since I had only made 2D games by myself up until that point. <br /> One of the things which I had learnt in my first day was how to use a Photoshop filter called offset, this helps me tile the textures seamlessly. This first day was also the day I drew concepts of the main character. <br /> Another thing which I had learnt was about source control, which I had no idea about until this point, my team taught me about how to use Tortoise Git, and GitLab with projects so I could branch off trying out something, or I could merge files together, all of this was new to me and hard to get my head around at first, but learning this was very useful for many future projects to come! <br /> </p>
         <h5>Day 2</h5> 
         <img src="/assets/img/posts/WelcomeToYelapa/13.jpg" class="TextWrap-L"/> <p>On the second day, I finished all of the texturing and began sketching the other characters like the final boss, the crab concept art and a few props. I also planned the logo for the game using Illustrator and Photoshop. <br /> I also began creating the UI for the game, designing the hearts which would represent the players health. I felt like these were good at the time but now looking back at them, I feel like they were a little too much for a game in this art style. I also learnt how to use Tiled, I began painting the terrain, the height of the terrain and making small levels. <br /> Another thing I did on this day was made textures for the leafs on a tree model. We all also planned out as a group how we are going to have the final boss battle. <br /></p>
         <h5>Day 3, 4 and 5</h5>
         <i>This day is the last day which I wrote about, since the rest of the week was crunch-mode</i> <br />
         <p>On day 3, I worked on the health system for the game, it felt like a very big task for me to do since I wasn’t really confident with programming at that point, along with the players health, I worked on the health for the final boss, all the maps have been added at this point. <br /> For Days 4 and 5, we were mostly working on finishing the game and adding the levels to the game, I was learning a lot along the way, mostly about how source control works, and bits of programming.</p>
      </div>
    </div>
  </div>
</div>
</div>

<hr>

<div class = "card">
    <h3>Game Jam Participants</h3>
    <p>I've talked about Team Horsehead a lot in this blog, and you can read more information about the team here:</p>
    <a href="/blog/authors/teamhorsehead" target="_blank" class="btn btn-dark btn-lg">Team Horsehead</a>
</div>

<hr>
<!--- -------------------------------------------------------- -->
<!--- This is another style of a collapsible which I could use -->
<!--- -------------------------------------------------------- -->
<!---
<details> 
    <summary>Some Words</summary> 
    some text here
</details>
-->

