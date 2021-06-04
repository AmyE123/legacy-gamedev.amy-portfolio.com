---
layout: post
title:  "The Dragonsitter"
type: "Game Development Blog"
color: "background-color: seagreen"
summary: "The Dragonsitter is a Tamagotchi inspired game, made for the 'Keep it alive' theme. <small>(Ludum Dare 46)</small>"
author: amyelliott
date: '2020-04-18'
category: ['game-development', 'game-jam', 'unity']
thumbnail: /assets/img/posts/TheDragonsitter/1.png
keywords: dragonsitter, gamejam, here
permalink: /blog/the-dragonsitter/
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

    <h6 style="text-align: center;">GJ Rank <a style="text-align: center;">614th of 4959 entries</a> </h6> 

    <h6 style="text-align: center;">Game Jam Duration <a style="text-align: center;">72 hours</a> </h6>    

    <h6 style="text-align: center;">Software Used <a style="text-align: center;">Unity, Photoshop, Maya</a> </h6>    

    <h6 style="text-align: center;">Primary Roles <a style="text-align: center;">Programming, Design, 3D, UI</a> </h6> 
</div>

<!--- This HR is nice to have here, to seperate the status of the game -->
<hr>

<!--- -------------------------------------------------------------------- -->
<!--- This is for the main description of the game, this is very important -->
<!--- -------------------------------------------------------------------- -->
<div class = "card">
    <h2 style="text-align: center;">About The Dragonsitter</h2>
    <p style="text-align: center;">The Dragonsitter is a Tamagotchi inspired game, made for the 'Keep it alive' theme. I ended up working on all sorts of things for this game, including programming, 3D and art. <br />This game was made with a team of 4, including me. <br />This game was great fun to plan out and produce, I felt like we worked very well as a team to make this!</p>
</div>

<!--- ------------------------------------------------------------------------------------------------------------------------------- -->
<!--- This is the Embed or Youtube Footage of the game, followed by controls and a collapsible with the gallery, which starts as open -->
<!--- ------------------------------------------------------------------------------------------------------------------------------- -->
<div style="text-align: center;"><iframe frameborder="0" src="https://itch.io/embed-upload/2159156?color=333333" allowfullscreen="" width="980" height="688"><a href="https://horsehead.itch.io/keep-it-alive">Play The Dragonsitter on itch.io</a></iframe></div>

<div class="control-card">  
    <h4 style="text-align: center;">Controls</h4>
    <li style="text-align: center;"> <strong>Move:</strong> Arrow Keys / W A S D</li>
    <li style="text-align: center;"> <strong>Throw/Action:</strong> Space</li>
    <li style="text-align: center;"> <strong>C:</strong> Crafting Menu</li> 
    <li style="text-align: center;"> <strong>Shift:</strong> Sprint</li> 
    <li style="text-align: center;"> <strong>M:</strong> Mute Audio</li> 
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
        <p>Here is a gallery of pictures displaying the different types of weather and interactions in the game along with some concept art. <br /> </p>
        
        <div class = "row">
          <div class="column-one">
            <img src="/assets/img/posts/TheDragonsitter/2.png">
          </div>
        </div>        
        <br />
        <div class="row">
          <div class="column">
            <img src="/assets/img/posts/TheDragonsitter/g1.gif">
          </div>
          <div class="column">
            <img src="/assets/img/posts/TheDragonsitter/g2.gif">
          </div>
          <div class="column">
            <img src="/assets/img/posts/TheDragonsitter/g3.gif">
          </div>
          <div class="column">
            <img src="/assets/img/posts/TheDragonsitter/g4.gif">
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
          The Dragonsitter: Development Overview
        </a>
      </h4>
    </div>
    <div id="collapseOverview" class="panel-collapse collapse in" role="tabpanel" aria-labelledby="headingOne">
      <div class="panel-body">
        <p>Our team of 4 entered this Gamejam in April of 2020, this Gamejam was a 72 -hour Gamejam, and much like our other Ludum Dare gamejam entry (Village Simulator) – We decided to each get a good amount of sleep each night, resulting on us working on the game each day for 12 or so hours, 48 hours in total. <br /> For this Gamejam, the theme was ‘Keep it alive’ – and that reminded most of our team of Tamagotchis! So that is where planning for this game began.<br /> </p>
      </div>
    </div>
  </div>
  <div class="panel panel-default">
    <div class="panel-heading" role="tab" id="headingTwo">
      <h4 class="panel-title">
        <a class="collapsed" role="button" data-toggle="collapse" data-parent="#accordion" href="#collapsePlan" aria-expanded="false" aria-controls="collapsePlan">
          Planning & Concepting
        </a>
      </h4>
    </div>
    <div id="collapsePlan" class="panel-collapse collapse" role="tabpanel" aria-labelledby="headingTwo">
      <div class="panel-body">
        <p>Our planning was mostly done on a document we all had access to over a Skype call, writing down random words, and pictures, and a list of words, and once we done that, we had our idea. <br /> The idea of our game is similar to Tamagotchi and Sims, since you have to take care and keep alive both your Tamagotchi and Sim, and we already had an idea how to do some of the mechanics which would be required since we had made the Village Simulator game previously. <br /> For the main ‘thing’ we had to keep alive, we all began making suggestions on animals and creatures which we all really liked from other games, we had the Chocobo from Final Fantasy suggested, along with some Pokemon (most notably Snorlax!) and Valoo from Wind Waker. <br /></p>        
        <div class = "row">
          <div class="column-three">
            <img src="/assets/img/posts/TheDragonsitter/fatchocobo.png">
          </div>
          <div class="column-three">
            <img src="/assets/img/posts/TheDragonsitter/snorlax.png">
          </div>
          <div class="column-three">
            <img src="/assets/img/posts/TheDragonsitter/valoo.png">
          </div>
        </div> 
        <p><br />Taking these ideas, I began to sketch up some quick concept sketches of an animal which shared elements with all three of these characters, we decided that we were going to have the dragon grow over the course of the game, to show the player how well they’re taking care of their pet, and I really love the final outcome of the dragon! <br /></p>
        <div class = "row">
          <div class="column-one">
            <img src="/assets/img/posts/TheDragonsitter/2.png">
          </div>
        </div>
        <br />
        <div class = "row">
          <div class="column-two">
            <img src="/assets/img/posts/TheDragonsitter/4.png">
          </div>      
          <div class="column-two">
            <img src="/assets/img/posts/TheDragonsitter/3.png">
          </div>
        </div>  
      </div>
    </div>
  </div>
  <div class="panel panel-default">
    <div class="panel-heading" role="tab" id="headingThree">
      <h4 class="panel-title">
        <a class="collapsed" role="button" data-toggle="collapse" data-parent="#accordion" href="#collapseUi" aria-expanded="false" aria-controls="collapseUi">
          User Interface
        </a>
      </h4>
    </div>
    <div id="collapseUi" class="panel-collapse collapse" role="tabpanel" aria-labelledby="headingThree">
      <div class="panel-body">
        <p>For the UI in the game, we referenced code which was used for our Village Simulation game to have a radical crafting menu, since we felt like this looks the best, our crafting menu was certainly lacking though, due to the restrictions on time, we could only manage to get the fire and the 2 straw beds for the dragon into the menu, and the fire was the only thing with functionality. <br /> Our other UI interfaces involved the inventory at the bottom middle, the dragon’s needs at the bottom right and the date along with notifications on the top left, the notifications have similar functionality to the notifications in the Village Simulator game too. These UI elements were made with Scriptable Objects so it’s not hard to modify properties of the UI.<br /></p>
        <div class="row">
          <div class="column-one">
            <img src="/assets/img/posts/TheDragonsitter/5.png">
          </div>
        </div>
        <br />
        <div class="row">
          <div class="column-two">
            <img src="/assets/img/posts/TheDragonsitter/6.png">
          </div>
          <div class="column-two">
            <img src="/assets/img/posts/TheDragonsitter/7.png">
          </div>
        </div>       
      </div>
    </div>
  </div>
  <div class="panel panel-default">
    <div class="panel-heading" role="tab" id="headingFour">
      <h4 class="panel-title">
        <a class="collapsed" role="button" data-toggle="collapse" data-parent="#accordion" href="#collapseWeather" aria-expanded="false" aria-controls="collapseWeather">
          Weather System With Particles
        </a>
      </h4>
    </div>
    <div id="collapseWeather" class="panel-collapse collapse" role="tabpanel" aria-labelledby="headingFour">
      <div class="panel-body">
        <p>Particles were used a bit more in this game, for example, the dragon’s reaction particles and the weather particles, these were all pretty important to have in the game because the dragon’s reaction particles let the player know if their input has been put in or not, and the weather particles are there mostly for aesthetics, but they do serve a purpose, as if it’s snowing, the dragon gets colder faster, and if it’s raining the fire gets put out faster. – I personally wish we had more time to put in more particles, for example, a happy reaction particle for the dragon if their needs are high.<br /></p>  
        <div class="row">
            <div class="column">
                <img src="/assets/img/posts/TheDragonsitter/g1.gif">
            </div>
            <div class="column">
                <img src="/assets/img/posts/TheDragonsitter/g2.gif">
            </div>
            <div class="column">
                <img src="/assets/img/posts/TheDragonsitter/g3.gif">
            </div>
            <div class="column">
                <img src="/assets/img/posts/TheDragonsitter/g4.gif">
            </div>
        </div>
        </div>
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


<!--- ------------------------------------------------- -->
<!--- Styleguide on how to use code to document my work -->
<!--- ------------------------------------------------- -->
<!---
{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

or

```javascript
var a = 1;
var b = 2;
function sum (num1,num2){
  return num1+num2;
}
var result = sum(a,b);
```

```c
cout >> "fun" >> endl;
```
-->

