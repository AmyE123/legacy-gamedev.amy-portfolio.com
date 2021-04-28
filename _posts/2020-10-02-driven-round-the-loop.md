---
layout: post
title:  "Driven Round The Loop"
type: "Game Development"
color: "background-color: seagreen"
summary: "Driven Round the Loop is a puzzle game designed around the theme 'Stuck in a loop'. <small>(Ludum Dare 47)</small>"
author: amyelliott
date: '2020-10-02'
category: ['game-jam', 'csharp', 'level-design', 'unity']
thumbnail: /assets/img/posts/DrivenRoundTheLoop/cover.png
keywords: funny, gamejam, cars
permalink: /blog/driven-round-the-loop/
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

    <h6 style="text-align: center;">GJ Rank <a style="text-align: center;">173rd of 3,206 entries</a> </h6> 

    <h6 style="text-align: center;">Game Jam Duration <a style="text-align: center;">72 hours</a> </h6>    

    <h6 style="text-align: center;">Software Used <a style="text-align: center;">Unity, Photoshop</a> </h6>    

    <h6 style="text-align: center;">Primary Roles <a style="text-align: center;">Programming, UI, Level Design</a> </h6> 
</div>

<!--- This HR is nice to have here, to seperate the status of the game -->
<hr>

<!--- -------------------------------------------------------------------- -->
<!--- This is for the main description of the game, this is very important -->
<!--- -------------------------------------------------------------------- -->
<div class = "card">
    <h2 style="text-align: center;">About Driven Round The Loop</h2>
    <p style="text-align: center;">Driven Round the Loop is a puzzle game designed around the theme 'Stuck in a loop'  made for Ludum Dare 47, as our group was so large I worked on a bit of programming, UI and Level Design. <br /> The game was made with a team of 7, which was a good experience as I don't usually work with groups this size!</p>
</div>

<!--- ------------------------------------------------------------------------------------------------------------------------------- -->
<!--- This is the Embed or Youtube Footage of the game, followed by controls and a collapsible with the gallery, which starts as open -->
<!--- ------------------------------------------------------------------------------------------------------------------------------- -->
<div style="text-align: center;"><iframe frameborder="0" src="https://itch.io/embed-upload/2803554?color=333333" allowfullscreen="" width="1000" height="700"><a href="https://horsehead.itch.io/driven-round-the-loop">Play Driven Round the Loop on itch.io</a></iframe></div>

<div class="control-card">  
    <h4 style="text-align: center;">Controls</h4>
    <li style="text-align: center;"> <strong>Action:</strong> Mouse Controls</li>
    <li style="text-align: center;"> <strong>Pause, Play, 1x speed and 2x speed:</strong> 1, 2, 3</li>
    <li style="text-align: center;"> <strong>Pause/Play:</strong> Space</li> 
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
        <p>Here is a gallery of screenshots taken from the game. <br /> </p>
        
        <div class = "row">
          <div class="column-three">
            <img src="/assets/img/posts/DrivenRoundTheLoop/1.png">
          </div>
          <div class="column-three">
            <img src="/assets/img/posts/DrivenRoundTheLoop/2.png">
          </div>
          <div class="column-three">
            <img src="/assets/img/posts/DrivenRoundTheLoop/3.png">
          </div>
        </div>        
        <br />
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
          Why complain normally, when you can make a petition?
        </a>
      </h4>
    </div>
    <div id="collapseOverview" class="panel-collapse collapse in" role="tabpanel" aria-labelledby="headingOne">
      <div class="panel-body">
        <p>The residents of Loopton are not a happy bunch. The most popular activity for them is to file complaints about the awful road infrastructure. But who can blame them? All of the roads are closed loops, and without proper guidance, they’re stuck going round and round forever! <br />This is where you come in! By placing directional arrows on roads, you can get cars, bikes, pedestrians, or even busses to swap from one loop to another. Use your power wisely, to solve the many petitions submitted to the Loopton Council website. <br />Be careful not to cause any crashes! (unless crashes are what’s being requested, of course...)<br /> </p>
      </div>
    </div>
  </div>
</div>
</div>

<hr>

<div class = "card">
    <h3>Game Jam Participants</h3>
    <p>I've talked about Team Horsehead in this blog, and you can read more information about the team here:</p>
    <a href="/blog/authors/teamhorsehead" target="_blank" class="btn btn-dark btn-lg">Team Horsehead</a>
</div>


<hr>
