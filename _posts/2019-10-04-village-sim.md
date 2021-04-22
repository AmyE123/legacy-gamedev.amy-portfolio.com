---
layout: post
title:  "Village Simulator"
type: "Game Jam"
color: "background-color: seagreen"
summary: "Village Simulator is a.. well you guessed it, it's a village simulator! This was designed around the theme 'Start with nothing' <small>(Ludum Dare 45)</small>"
author: amyelliott
date: '2019-10-04'
category: ['game-jam', 'csharp', 'design', 'ui-ux', 'unity']
thumbnail: /assets/img/posts/VillageSim/villagesimulator.png
keywords: villagesim, village, sim, indie
permalink: /blog/village-simulator/
usemathjax: true
---
<!---Keep this here-->
<!---Part of the collapsible group items // Ref: https://codepen.io/nhembram/pen/XKEJJp -->
<script>
     $('.panel-collapse').on('show.bs.collapse', function () {
        $(this).siblings('.panel-heading').addClass('active');
      });

      $('.panel-collapse').on('hide.bs.collapse', function () {
        $(this).siblings('.panel-heading').removeClass('active');
      });
</script>

<!--- This HR is nice to have here, to seperate the status of the game -->
<hr>


<!--- -------------------------------------------------------------- -->
<!--- This is for the status of the game, every game should have one -->
<!--- -------------------------------------------------------------- -->
<div class="status-card">
    <h6 style="text-align: center;">Status <a style="text-align: center;">Done</a> </h6> 

    <h6 style="text-align: center;">Project Type <a style="text-align: center;">Game Jam</a> </h6>   

    <h6 style="text-align: center;">GJ Rank <a style="text-align: center;">431st of 2611 entries</a> </h6>  

    <h6 style="text-align: center;">Game Jam Duration <a style="text-align: center;">72 hours</a> </h6>    

    <h6 style="text-align: center;">Software Used <a style="text-align: center;">Unity, Photoshop</a> </h6>    

    <h6 style="text-align: center;">Primary Roles <a style="text-align: center;">Programming, UI, Design</a> </h6> 
</div>

<!--- This HR is nice to have here, to seperate the status of the game -->
<hr>

<!--- -------------------------------------------------------------------- -->
<!--- This is for the main description of the game, this is very important -->
<!--- -------------------------------------------------------------------- -->
<div class = "card">
    <h2 style="text-align: center;">About Village Simulator</h2>
    <p style="text-align: center;">Village Simulator is a.. well you guessed it, it's a village simulator! This was designed around the theme 'Start with nothing' and was made for Ludum Dare 45. This game was made with a team of 2, including me, and my friend Joe. <br /> As our team was small, both me and Joe worked on a bit of everything so we could get the game done in time. <br /> This game helped me understand more about scriptable objects in Unity.</p>
</div>

<!--- --------------------------------------------------------------------------------------------------------- -->
<!--- This is the Embed of the game, followed by a collapsible with the gallery, which starts as open -->
<!--- --------------------------------------------------------------------------------------------------------- -->
<div style="text-align: center;"> <iframe frameborder="0" src="https://itch.io/embed-upload/3491873?color=333333" allowfullscreen="" width="980" height="650"><a href="https://horsehead.itch.io/village-simulation-game";  width="100%">Play Village Simulation Game on itch.io</a></iframe> </div>
<div class="control-card">  
    <h4 style="text-align: center;">Controls</h4>
    <p style="text-align: center;">This game is played with the mouse. Click on objects in the world to instruct your villager to interact with them. By collecting enough resources you can start to build things, and attract more villagers.</p>
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
        <p>Here is a gallery of pictures which I have taken through the Game Jam, from this gallery you can see concepts which I have drawn out which have been made into models, as well as some gameplay mechanics. <br /> </p>  
        <div class="row">
            <div class="column-two">
                <img src="/assets/img/posts/VillageSim/1.png">
            </div>
            <div class="column-two">
                <img src="/assets/img/posts/VillageSim/0.png">
            </div>
        </div>



        <div class="row">
              <div class="column">
                <img src="/assets/img/posts/VillageSim/2.png">
              </div>
              <div class="column">
                <img src="/assets/img/posts/VillageSim/6.png">
              </div>
              <div class="column">
                <img src="/assets/img/posts/VillageSim/3.png">
              </div>
              <div class="column">
                <img src="/assets/img/posts/VillageSim/9.png">
              </div>
        </div>


        <div class="row">
              <div class="column-two">
                <img src="/assets/img/posts/VillageSim/4.png">
              </div>
              <div class="column-two">
                <img src="/assets/img/posts/VillageSim/5.png">
              </div>
        </div>

      </div>
    </div>
  </div>
</div>

<!--- This HR is nice to have here, to seperate the status of the game -->
<hr>

<!--- -------------------------------------------------------- -->
<!--- This is the collapsible which I will be using.           -->
<!--- I will use these to write about what I done for the game -->
<!--- -------------------------------------------------------- -->
<div class="wrapper center-block">
  <div class="panel-group" id="accordion" role="tablist" aria-multiselectable="true">
  <div class="panel panel-default">
    <div class="panel-heading active" role="tab" id="headingOne">
      <h4 class="panel-title">
        <a role="button" data-toggle="collapse" data-parent="#accordion" href="#collapseOverview" aria-expanded="true" aria-controls="collapseOverview">
          Village Simulator: Development Overview
        </a>
      </h4>
    </div>
    <div id="collapseOverview" class="panel-collapse collapse in" role="tabpanel" aria-labelledby="headingOne">
      <div class="panel-body">
        This was the first Ludum Dare Gamejam which me and Joe entered in October of 2019, it was a 72-hour Gamejam, and we decided to get a good amount of sleep each night which meant we were working for about 48-hours of work time for our team of two. <br /> We wanted to try something different for this Gamejam, so we decided to try out a simulation game. <br /> Since it was just me and Joe developing the game for this Gamejam, this was something that none of us have done before so it really pushed our knowledge and abilities.  <br /> We were both really proud of our outcome since we learnt how to make a simulation game and people actually enjoyed playing it! <br /> The way the game works is we split the simulation from the presentation, all of the simulation would happen separately and independently from the game objects in the scenes, and then those 3D models would just have to replicate the underlying state, this allowed for very easy speed control implementation.
      </div>
    </div>
  </div>
  <div class="panel panel-default">
    <div class="panel-heading" role="tab" id="headingTwo">
      <h4 class="panel-title">
        <a class="collapsed" role="button" data-toggle="collapse" data-parent="#accordion" href="#collapseInspiration" aria-expanded="false" aria-controls="collapseInspiration">
          Inspiration and UI for the game
        </a>
      </h4>
    </div>
    <div id="collapseInspiration" class="panel-collapse collapse" role="tabpanel" aria-labelledby="headingTwo">
      <div class="panel-body">
        <p> We were both inspired by The Sims with their radical menus for actions, so we made it so when you click on something which can be interacted with, a list of possible interactions would pop up, which made adding new interactions simple, since all we would need to do is add new items to that list. <br /> </p>
        <div class="row">
              <div class="column-three">
                <img src="/assets/img/posts/VillageSim/2.png">
              </div>
              <div class="column-three">
                <img src="/assets/img/posts/VillageSim/6.png">
              </div>
              <div class="column-three">
                <img src="/assets/img/posts/VillageSim/8.png">
              </div>
        </div>  
        <p> <br />Near the end of the first day, the UI began to get worked on, we were looking at different types of UI to use but we were very inspired from the complex-but-sleek UI in the 2013 SimCity game, the UI was made so we could add new buildings and shelves without needing to lay out any additional UI, but in the end we never had the time to fill up the shelves so they didn’t have too much in them anyway, but it still looked really nice anyway! <br /> </p>
        <div class="row">
              <div class="column-two">
                <img src="/assets/img/posts/VillageSim/3.png">
              </div>
              <div class="column-two">
                <img src="/assets/img/posts/VillageSim/7.png">
              </div>
        </div> 
        <p> <br /> We used ScriptableObjects a lot to define the properties of our elements on the prefabs. <br /> Each SimulationEvent had a slot for a SimulationProperties (Which was the Scriptable Object), this would show up on the screen whenever the player selected “More Info” on the radical UI. All of these properties would be changed from inside the editor. <br /> </p>
      </div>
    </div>
  </div>
  <div class="panel panel-default">
    <div class="panel-heading" role="tab" id="headingThree">
      <h4 class="panel-title">
        <a class="collapsed" role="button" data-toggle="collapse" data-parent="#accordion" href="#collapseRabbit" aria-expanded="false" aria-controls="collapseRabbit">
          Rabbit-Hole System
        </a>
      </h4>
    </div>
    <div id="collapseRabbit" class="panel-collapse collapse" role="tabpanel" aria-labelledby="headingThree">
      <div class="panel-body">
        <p>Most of our second day was spent getting a lot of the content in, like the 3D models and animations, we then also decided to implement a “rabbit hole” system, this too was borrowed from The Sims, where you would send your sims off to a location and they would disappear to do that, like when you send them to school or work, and when they come back, there would be some UI pop-up with text which explained what they done in their day, this allowed us to add world-building without needing all the content, I personally had a lot of fun writing out these little scenarios!<br /></p>
        <div class="row">
              <div class="column-three">
                <img src="/assets/img/posts/VillageSim/9.png">
              </div>
              <div class="column-three">
                <img src="/assets/img/posts/VillageSim/5.png">
              </div>
              <div class="column-three">
                <img src="/assets/img/posts/VillageSim/4.png">
              </div>
        </div>       
      </div>
    </div>
  </div>
  <div class="panel panel-default">
    <div class="panel-heading" role="tab" id="headingThree">
      <h4 class="panel-title">
        <a class="collapsed" role="button" data-toggle="collapse" data-parent="#accordion" href="#collapseFinal" aria-expanded="false" aria-controls="collapseFinal">
          Final Day
        </a>
      </h4>
    </div>
    <div id="collapseFinal" class="panel-collapse collapse" role="tabpanel" aria-labelledby="headingThree">
      <div class="panel-body">
        <p>Unfortunately by Monday, we were down to Joe working on the game for most of the day by himself, as I had to go to work, but I worked on the game for the evening of the final day, and we both realised that there was far too much work to do and get completed, so we decided to cut out planned content so we can make the game playable first. <br /> We decided that the most important thing to get in first was progression, so that the player would have a reason to carry on playing, so we decided to check what buildings the player has crafted and progress from there, unlocking more buildings and villagers for the player to handle. <br />When the deadline was growing closer, we still had far too much we had to do, for example if a villager was hungry or tired or upset, there would be no effect on the game, so we quickly made a system for making the villagers pass out when their lacks are low. <br />Overall we were both very happy with how this game turned out, I personally really love how the game looks, it looks really sleek and clean, and it’s a very simple and easy game to pick up and play, we definitely planned way more than what we got done, but this is all part of leaning!<br /></p>  
      </div>
    </div>
  </div>
</div>
</div>

<hr>
        
<div class = "card">
    <h3>Game Jam Participants</h3>
    <p>This game was made by me and Joe Shanahan, we submitted it as a Team Horsehead game</p>
    <p>You can read more information about the team here:</p>
    <a href="/blog/authors/teamhorsehead" target="_blank" class="btn btn-dark btn-lg">Team Horsehead</a>
</div>


