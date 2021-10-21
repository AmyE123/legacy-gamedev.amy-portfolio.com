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
<table>
    <tr>
        <th style="border: 0px !important">Status:</th>
        <th style="text-align:right; border: 0px !important"><small class="btn btn-col" style="font-size: small; padding: .1rem .5rem; display:inline; background-color: darkslategrey; margin: 10px">Done</small></th>
    </tr>
    <tr>
        <th style="border: 0px !important">Project Type:</th> 
        <th style="text-align:right; border: 0px !important"><small class="btn btn-col" style="font-size: small; padding: .1rem .5rem; display:inline; background-color: darkslategrey; margin: 10px">Game Jam</small></th>
    </tr>
    <tr>
        <th style="border: 0px !important">Development Duration:</th>
        <th style="text-align:right; border: 0px !important"><small class="btn btn-col" style="font-size: small; padding: .1rem .5rem; display:inline; background-color: darkslategrey; margin: 10px">72 Hours</small></th>
    </tr>
    <tr>
        <th style="border: 0px !important">Software Used:</th>
        <th style="text-align:right; border: 0px !important"><small class="btn btn-col" style="font-size: small; padding: .1rem .5rem; display:inline; background-color: darkslategrey; margin: 10px">Unity</small><small class="btn btn-col" style="font-size: small; padding: .1rem .5rem; display:inline; background-color: darkslategrey; margin: 10px">Photoshop</small><small class="btn btn-col" style="font-size: small; padding: .1rem .5rem; display:inline; background-color: darkslategrey; margin: 10px">Maya</small></th>
    </tr>
    <tr>
        <th style="border: 0px !important">Primary Roles:</th>
        <th style="text-align:right; border: 0px !important"><small class="btn btn-col" style="font-size: small; padding: .1rem .5rem; display:inline; background-color: darkslategrey; margin: 10px">Programming</small><small class="btn btn-col" style="font-size: small; padding: .1rem .5rem; display:inline; background-color: darkslategrey; margin: 10px">UI</small><small class="btn btn-col" style="font-size: small; padding: .1rem .5rem; display:inline; background-color: darkslategrey; margin: 10px">Design</small><small class="btn btn-col" style="font-size: small; padding: .1rem .5rem; display:inline; background-color: darkslategrey; margin: 10px">3D</small></th>
    </tr>
</table>


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
<hr>
<h3 style="text-align:center; margin-top: 20px; margin-bottom: 20px">Gallery & Screenshots</h3>
<div class="panel-heading active" role="tab" id="headingOne">
    <h2 class="panel-title" style="word-wrap: normal; padding: 15px; background-color: #1b1b1b">
    <a role="button" data-toggle="collapse" data-parent="#accordion" href="#collapseConceptArt" aria-expanded="true" aria-controls="collapseConceptArt" style="font-size: 18px; padding: 0px !important">
        Concept Art
    </a>
    </h2>                                
</div>
<div id="collapseConceptArt" class="panel-collapse collapse" role="tabpanel" aria-labelledby="headingOne">
    <div class="panel-body">
        <div class = "widcard" style="background-color: #1c1c1e; margin-bottom: 0px !important">
            <img src="/assets/img/posts/TheDragonsitter/2.png" style="max-width: -webkit-fill-available; box-shadow: 0px 0px 20px #202022;">
        </div>
        <p style="text-align: center">I worked on the 2D Concept Art for this game, and with this concept art, I gave it a very cartoony style, inspired by lots of different images I found on Google as that was the vibe we were going for when planning out the game.</p>
    </div>
</div>
<div class="panel-heading active" role="tab" id="headingTwo">
    <h2 class="panel-title" style="word-wrap: normal; padding: 15px; background-color: #1b1b1b">
    <a role="button" data-toggle="collapse" data-parent="#accordion" href="#collapseWeather" aria-expanded="true" aria-controls="collapseWeather" style="font-size: 18px; padding: 0px !important">
        Weather System Clips
    </a>
    </h2>                                
</div>
<div id="collapseWeather" class="panel-collapse collapse" role="tabpanel" aria-labelledby="headingTwo">
    <div class="panel-body">
        <div class = "widcard" style="background-color: #1c1c1e; margin-bottom: 0px !important">
            <img src="/assets/img/posts/TheDragonsitter/g1.gif" style="max-width: -webkit-fill-available; box-shadow: 0px 0px 20px #202022;">
        </div>
        <div class = "widcard" style="background-color: #1c1c1e; margin-bottom: 0px !important">
            <img src="/assets/img/posts/TheDragonsitter/g2.gif" style="max-width: -webkit-fill-available; box-shadow: 0px 0px 20px #202022;">
        </div>
        <div class = "widcard" style="background-color: #1c1c1e; margin-bottom: 0px !important">
            <img src="/assets/img/posts/TheDragonsitter/g3.gif" style="max-width: -webkit-fill-available; box-shadow: 0px 0px 20px #202022;">
        </div>
        <div class = "widcard" style="background-color: #1c1c1e; margin-bottom: 0px !important">
            <img src="/assets/img/posts/TheDragonsitter/g4.gif" style="max-width: -webkit-fill-available; box-shadow: 0px 0px 20px #202022;">
        </div>
    </div>
</div>
<hr>
<h3 style="text-align:center; margin-top: 20px; margin-bottom: 20px">Development Overview</h3>
<img src="/assets/img/posts/TheDragonsitter/tamagotchi.png" style="object-fit: cover; height: 400px; width: 100%; object-position: 0 50%">
<p>Our team of 4 entered this Gamejam in April of 2020, this Gamejam was a 72 -hour Gamejam, and much like our other Ludum Dare gamejam entry (Village Simulator) – We decided to each get a good amount of sleep each night, resulting on us working on the game each day for 12 or so hours, 48 hours in total.<br />
For this Gamejam, the theme was ‘Keep it alive’ – and that reminded most of our team of Tamagotchis! So that is where planning for this game began.</p>
<h3 style="text-align:center; margin-top: 20px; margin-bottom: 20px">Planning and Concepting</h3>
<img src="/assets/img/posts/TheDragonsitter/2.png" style="object-fit: cover; height: 400px; width: 100%; object-position: 0 50%">
<p>Our planning was mostly done on a document we all had access to over a Skype call, writing down random words, and pictures, and a list of words, and once we done that, we had our idea. <br />
The idea of our game is similar to Tamagotchi and Sims, since you have to take care and keep alive both your Tamagotchi and Sim, and we already had an idea how to do some of the mechanics which would be required since we had made the Village Simulator game previously.<br />
For the main ‘thing’ we had to keep alive, we all began making suggestions on animals and creatures which we all really liked from other games, we had the Chocobo from Final Fantasy suggested, along with some Pokemon (most notably Snorlax!) and Valoo from Wind Waker.<br />
Taking these ideas, I began to sketch up some quick concept sketches of an animal which shared elements with all three of these characters, we decided that we were going to have the dragon grow over the course of the game, to show the player how well they’re taking care of their pet, and I really love the final outcome of the dragon!</p>
<h3 style="text-align:center; margin-top: 20px; margin-bottom: 20px">User Interface</h3>
<p>For the UI in the game, we referenced code which was used for our Village Simulation game to have a radical crafting menu, since we felt like this looks the best, our crafting menu was certainly lacking though, due to the restrictions on time, we could only manage to get the fire and the 2 straw beds for the dragon into the menu, and the fire was the only thing with functionality. <br />
Our other UI interfaces involved the inventory at the bottom middle, the dragon’s needs at the bottom right and the date along with notifications on the top left, the notifications have similar functionality to the notifications in the Village Simulator game too. These UI elements were made with Scriptable Objects so it’s not hard to modify properties of the UI.</p>
<h3 style="text-align:center; margin-top: 20px; margin-bottom: 20px">Weather System</h3>
<img src="/assets/img/posts/TheDragonsitter/g4.gif" style="object-fit: cover; height: 400px; width: 100%; object-position: 0 50%">
<p>Particles were used a bit more in this game, for example, the dragon’s reaction particles and the weather particles, these were all pretty important to have in the game because the dragon’s reaction particles let the player know if their input has been put in or not, and the weather particles are there mostly for aesthetics, but they do serve a purpose, as if it’s snowing, the dragon gets colder faster, and if it’s raining the fire gets put out faster. – I personally wish we had more time to put in more particles, for example, a happy reaction particle for the dragon if their needs are high.<br /></p>  
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

