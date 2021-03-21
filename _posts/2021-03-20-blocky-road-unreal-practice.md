---
layout: post
title:  "Blocky Road (Unreal Engine C++ Practice)"
summary: "I decided to tackle Unreal Engine C++ straight on to remake one of my older game jam games <small>(MiniJam 76)</small>"
author: amyelliott
date: '2021-03-20'
category: ['CPlusPlus', 'Game-Jam', 'Unreal-Engine']
thumbnail: /assets/img/wip.png
keywords: cplusplus, gamejam, unrealengine, ue
permalink: /blog/blocky-road-ue-practice/
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
    <h6 style="text-align: center;">Status <a style="text-align: center;">Work in progress</a> </h6> 

    <h6 style="text-align: center;">Project Type <a style="text-align: center;">Game Jam + Practice</a> </h6>   

    <h6 style="text-align: center;">Game Jam Duration <a style="text-align: center;">72 hours</a> </h6>    

    <h6 style="text-align: center;">Software Used <a style="text-align: center;">Unreal Engine</a> </h6>    

    <h6 style="text-align: center;">Primary Roles <a style="text-align: center;">Programming</a> </h6> 
</div>

<!--- This HR is nice to have here, to seperate the status of the game -->
<hr>

<!--- -------------------------------------------------------------------- -->
<!--- This is for the main description of the game, this is very important -->
<!--- -------------------------------------------------------------------- -->
<div class = "card">
    <h2 style="text-align: center;">About Blocky Road (Unreal Engine C++ Practice)</h2>
    <p style="text-align: center;">I knew I had to get more comfortable with using Unreal Engine's C++ at some point, as of now I don't really have too much free time to learn this, besides weekends, so I decided to use my weekend to reproduce Blocky Road, one of my solo game jam games which I made in Unity. Making this game using Unreal's Blueprints would be no problem, which is why I decided to make it using C++ ONLY<br /> My reason for doing this is, I can't get comfortable with one engine and stick with it for the rest of my life, there are many studios which use different engines, and their own in-house engines, and refusing to learn another engine will just mean I lock myself away from those opportunities, at some point, these engines will die out and other engines will replace them, so I need to learn how to adapt and learn new engines on the fly.</p>
</div>

<!--- ------------------------------------------------------------------------------------------------------------------------------- -->
<!--- This is the Embed or Youtube Footage of the game, followed by controls and a collapsible with the gallery, which starts as open -->
<!--- ------------------------------------------------------------------------------------------------------------------------------- -->

<!---<div class="wrapper center-block">
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
        <p>Here is a gallery of gifs, showing gameplay <br /> </p>
        
        <div class = "row">
          <div class="column-two">
            <img src="/assets/img/posts/SomewhereInBerkshire/berkshire.gif">
          </div>
          <div class="column-two">
            <img src="/assets/img/posts/SomewhereInBerkshire/berkshire2.gif">
          </div>
        </div>        
        <br />
        <div class="row">
          <div class="column-two">
            <img src="/assets/img/posts/SomewhereInBerkshire/berkshire3.gif">
          </div>
          <div class="column-two">
            <img src="/assets/img/posts/SomewhereInBerkshire/berkshire4.gif">
          </div>
        </div>  
      </div>
    </div>
  </div>
</div>-->

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
          Blocky Road (Unreal C++ Practice): Development Overview
        </a>
      </h4>
    </div>
    <div id="collapseOverview" class="panel-collapse collapse in" role="tabpanel" aria-labelledby="headingOne">
      <div class="panel-body">
        <p>Like mentioned in the About section, I tackled this project to learn Unreal Engine's C++. <br /> Beforehand, I have made a few small things using blueprints and I have worked on Unreal Engine C++ courses, but all I was doing was following along with the courses, I didn't feel as if I was learning much, so I decided that I should remake Blocky Road, so I can do my own research and implementation of code, and with that technique, I learnt much better then taking the courses which I have.<br /> Of course, as Unreal Engine's C++ and general C++ feel very different, I didn't do this without the help of tutorials, documentation and forums, on the sections of the blog, I mention tutorials and forums which I have used to help me out. <br /> I didn't do the full Game Jam hours either, I wasn't worrying too much if I couldn't submit on time as my studying took prioirity over submitting on time, so I accepted that if I wasn't ready by the end of the game jam, it wasn't an issue. <br /> <br /> In the end, I'm aware that I didn't get much done at all, but I feel like with more practice I will speed up overtime, as I have learnt from any mistakes which I have made on this project.</p>
      </div>
    </div>
  </div>
  <div class="panel panel-default">
    <div class="panel-heading" role="tab" id="headingTwo">
      <h4 class="panel-title">
        <a class="collapsed" role="button" data-toggle="collapse" data-parent="#accordion" href="#collapseGridMovement" aria-expanded="false" aria-controls="collapseGridMovement">
          Grid Movement
        </a>
      </h4>
    </div>
    <div id="collapseGridMovement" class="panel-collapse collapse" role="tabpanel" aria-labelledby="headingTwo">
      <div class="panel-body">
        <p>In the original Blocky Road, the player moves in only one direction, and they can choose how far they move by holding down the mouse button, and they can click the mouse button once to flip the map to get to the other side of the puzzle.</p>        
        <div class = "row">
          <div class="column-one">
            <img src="/assets/img/posts/BlockyRoadUnreal/BR.png">
          </div>
        </div> 
        <p><br />So I began to replicate this in Unreal, the first thing I done, was make a Pawn C++ class, and called it BlockyController. I used part of <a href="https://youtu.be/UFwHj0gwYW4" target="_blank">this tutorial</a> to help me out.<br /> After following this tutorial, I had movement, but it was only forward and backwards on the grid, and not in increments like a grid movement would be.</p>
        <p>In the original Blocky Road, you wouldn't be able to move backwards, just forwards, and currently in the game, your movement direction was determined by what mouse button you were clicking, you would go forward with the left mouse button, and backwards with the right mouse button, and that was unnecessary, but I figured that I could make it work this way and just remove it if I didn't like it in the end. For the detection of the move direction I was using an Axis, instead of an Action, so I was having trouble with checking if the key is pressed once, instead of running the multiple frames which the key is being held down, so after lots of research, I found out about the function WasInputKeyJustPressed, which returns a bool if the key was pressed in the previous frame, I done lots of research into this function and the IsPressed function, and this is where some of my problems started. <br /> Nothing was working how I wanted it to, as if I were going to use this I had to have a reference to the player controller, but this didn't work, so I tried creating an instance of the controller, and that was causing crashes.<br /></p>
        <div class = "row">
          <div class="column">
            <img src="/assets/img/posts/BlockyRoadUnreal/1.png">
          </div>      
          <div class="column">
            <img src="/assets/img/posts/BlockyRoadUnreal/2.png">
          </div>
          <div class="column">
            <img src="/assets/img/posts/BlockyRoadUnreal/3.png">
          </div>      
          <div class="column">
            <img src="/assets/img/posts/BlockyRoadUnreal/4.png">
          </div>
        </div>  
        <div class = "row">
          <div class="column">
            <img src="/assets/img/posts/BlockyRoadUnreal/5.png">
          </div>      
          <div class="column">
            <img src="/assets/img/posts/BlockyRoadUnreal/6.png">
          </div>     
          <div class="column">
            <img src="/assets/img/posts/BlockyRoadUnreal/8.png">
          </div>
        </div>
        <p><br />So I decided to take a different approach and just try and make the cube move forward on a single button press, so instead of making a axis, I made an action, and worked with that instead, and despite the axis not working how I wanted it to, this action worked exactly how I wanted it to, and only moved the cube in single increments when I clicked the action button<br /></p>
        <h5>BlockyController.cpp</h5>
        {% highlight cpp %}
        // Called to bind functionality to input
        void ABlockyController::SetupPlayerInputComponent(UInputComponent* PlayerInputComponent)
        {
	        Super::SetupPlayerInputComponent(PlayerInputComponent);

	        //The old movement which would call the move forward axis
	        //InputComponent->BindAxis(TEXT("MoveForward"), this, &ABlockyController::MoveForward);

	        //the new movement which detects when it's pressed and only runs once.
	        InputComponent->BindAction("Action", IE_Pressed, this, &ABlockyController::MoveForward);
        }

        void ABlockyController::MoveForward()
        {
	        GEngine->AddOnScreenDebugMessage(-1, 15.0f, FColor::Yellow, TEXT("Some debug message!"));

	        //This moves the player cube -100 on the X axis, which is one unit in the game.
	        const FVector NewLocation = GetActorLocation() + FVector(-100, 0, 0);
	        SetActorLocation(NewLocation);
        }
        {% endhighlight %}
        <p>Some interesting things which I have learnt here is about FVector, and the difference between Axis and Action. And although implementing this mechanic took much longer than it should have, through the failures, I have learnt lots!</p>
        <div class="row">
            <div class="column-one">
                <img src="/assets/img/posts/BlockyRoadUnreal/movement.gif">
            </div>
        </div>
      </div>
    </div>
  </div>
  <div class="panel panel-default">
    <div class="panel-heading" role="tab" id="headingThree">
      <h4 class="panel-title">
        <a class="collapsed" role="button" data-toggle="collapse" data-parent="#accordion" href="#collapseTrigger" aria-expanded="false" aria-controls="collapseTrigger">
          Trigger Box To Next Level
        </a>
      </h4>
    </div>
    <div id="collapseTrigger" class="panel-collapse collapse" role="tabpanel" aria-labelledby="headingThree">
      <div class="panel-body">
        <p>In the original Blocky Road, if you were to go over the end green cube with the players on both sides, you win the level and go onto the next one.<br /> I started this by looking through the code which <a href="https://unrealcpp.com/trigger-box/" target="_blank">Harrison McGurie</a> had wrote on using Trigger Boxes, reading through this gave me a rough idea of how I could approach this, so after reading his code, I done further research into trigger boxes, and found <a href="https://youtu.be/Pi9Nj-yki04" target="_blank">this other tutorial</a> by KeySmash Studios which approach this in a slightly different way, but in both tutorials they use OnActorBeginOverlap, I researched into OnActorBeginOverlap a bit more, and much like the name very obviously suggests, OnActorBeginOverlap is called when another actor begins to overlap the actor</p>
        <h5>EndLevelPoint.h</h5>        
        {% highlight cpp %}
        #pragma once

        #include "CoreMinimal.h"
        #include "Engine/TriggerBox.h"
        #include "EndLevelPoint.generated.h"

        UCLASS()
        class BLOCKYROAD_API AEndLevelPoint : public ATriggerBox
        {
	        GENERATED_BODY()
	
        protected:
	        virtual void BeginPlay() override;

        public:
	        AEndLevelPoint();

	        UFUNCTION()
		        void Event(class AActor* overlappedActor, class AActor* otherActor);
        };
        {% endhighlight %}
        <br />
        <h5>EndLevelPoint.cpp</h5>        
        {% highlight cpp %}
        #include "EndLevelPoint.h"

        AEndLevelPoint::AEndLevelPoint()
        {
	        OnActorBeginOverlap.AddDynamic(this, &AEndLevelPoint::Event);
        }

        void AEndLevelPoint::BeginPlay()
        {
	        Super::BeginPlay();
        }

        void AEndLevelPoint::Event(class AActor* overlappedActor, class AActor* otherActor)
        {
	        if (otherActor && otherActor != this)
	        {
		        GEngine->AddOnScreenDebugMessage(-1, 15.0f, FColor::Yellow, TEXT("Overlap"));
	        }
        }
        {% endhighlight %}
        <p><br />In the end, to get the trigger working there really wasn't much code to write, I would load the next level where I have the overlap debug message.<br /></p>
        <div class="row">
            <div class="column-one">
                <img src="/assets/img/posts/BlockyRoadUnreal/trigger.gif">
            </div>
        </div>
        <p><br />But after I completed this, I found that I had ran into an error which I had no idea how to fix. Although the game worked fine when I pressed play, whenever I would compile the code I would get this error message:<br /></p>
      </div>
    </div>
  </div>
  <div class="panel panel-default">
    <div class="panel-heading" role="tab" id="headingFour">
      <h4 class="panel-title">
        <a class="collapsed" role="button" data-toggle="collapse" data-parent="#accordion" href="#collapseCollectible" aria-expanded="false" aria-controls="collapseCollectible">
          Collectible Particle and User Interface
        </a>
      </h4>
    </div>
    <div id="collapseCollectible" class="panel-collapse collapse" role="tabpanel" aria-labelledby="headingFour">
      <div class="panel-body">
        <p>During the first day, I worked on a particle, for a collectable, this means that we could just have the sparking collectable particles in the world instead of the actual 3D objects, so it’s a mystery what the player picks up, a lot of games do this. <br />I made these particles by making a circle ring and a solid circle ring, along with some star parts, and then I manipulated their particle settings to stay in place, this is what it ended up looking like, and I’m quite proud with how it looks! <br /></p>  
        <div class="row">
            <div class="column-one">
                <img src="/assets/img/posts/SomewhereInBerkshire/collectible.gif">
            </div>
        </div>
        <p><br />We decided that if we have collectables like this, we would need a collectable notification box, so that is what I began working on, it was pretty simple to make and I made use of DOTween to make the UI transition and fade in/out smoothly.<br /></p>
        <div class="row">
            <div class="column-one">
                <img src="/assets/img/posts/SomewhereInBerkshire/collectible2.gif">
            </div>
        </div>
        <p><br />The next thing I had to work on once I finished that was the visuals for the collectables which are picked up, there currently isn’t loads of collectables to collect, but they can easily be added to the game, since the collectables are data objects. <br />The only thing I needed to do was link up the titles, descriptions and the item images to the collectable UI, and then I had to draw images for the 2 collectables which we had in the game at the moment, soil and bugs, I also decided to add a little polish and make a nice shine behind the object, this was heavily inspired by BOTW’s UI when you pick up an object, I then added some tweening and this is the result of the collectable UI, overall I really love this! <br /></p>
        <div class="row">
            <div class="column-one">
                <img src="/assets/img/posts/SomewhereInBerkshire/collectible3.gif">
            </div>
        </div>
        <p><br />To give the game more ‘life’ I decided to add a few more collectables to it instead of just having dirt and bugs, so I began to draw pictures for each collectable and add that data into the game <i>(I didn’t draw the rock image, I forgot to replace the placeholder image)</i> <br /></p>
        <div class="row">
            <div class="column-one">
                <img src="/assets/img/posts/SomewhereInBerkshire/collectible.png">
            </div>
        </div>
      </div>
    </div>
  </div>
  <div class="panel panel-default">
    <div class="panel-heading" role="tab" id="headingFive">
      <h4 class="panel-title">
        <a class="collapsed" role="button" data-toggle="collapse" data-parent="#accordion" href="#collapseShaders" aria-expanded="false" aria-controls="collapseShaders">
          Shader Graph Work
        </a>
      </h4>
    </div>
    <div id="collapseShaders" class="panel-collapse collapse" role="tabpanel" aria-labelledby="headingFive">
      <div class="panel-body">
        <p>During the first day, I worked on a particle, for a collectable, this means that we could just have the sparking collectable particles in the world instead of the actual 3D objects, so it’s a mystery what the player picks up, a lot of games do this. <br />I made these particles by making a circle ring and a solid circle ring, along with some star parts, and then I manipulated their particle settings to stay in place, this is what it ended up looking like, and I’m quite proud with how it looks! <br /></p>  
        <div class="row">
            <div class="column-one">
                <img src="/assets/img/posts/SomewhereInBerkshire/collectible.gif">
            </div>
        </div>
        <p><br />We decided that if we have collectables like this, we would need a collectable notification box, so that is what I began working on, it was pretty simple to make and I made use of DOTween to make the UI transition and fade in/out smoothly.<br /></p>
        <div class="row">
            <div class="column-one">
                <img src="/assets/img/posts/SomewhereInBerkshire/collectible2.gif">
            </div>
        </div>
        <p><br />The next thing I had to work on once I finished that was the visuals for the collectables which are picked up, there currently isn’t loads of collectables to collect, but they can easily be added to the game, since the collectables are data objects. <br />The only thing I needed to do was link up the titles, descriptions and the item images to the collectable UI, and then I had to draw images for the 2 collectables which we had in the game at the moment, soil and bugs, I also decided to add a little polish and make a nice shine behind the object, this was heavily inspired by BOTW’s UI when you pick up an object, I then added some tweening and this is the result of the collectable UI, overall I really love this! <br /></p>
        <div class="row">
            <div class="column-one">
                <img src="/assets/img/posts/SomewhereInBerkshire/collectible3.gif">
            </div>
        </div>
        <p><br />To give the game more ‘life’ I decided to add a few more collectables to it instead of just having dirt and bugs, so I began to draw pictures for each collectable and add that data into the game <i>(I didn’t draw the rock image, I forgot to replace the placeholder image)</i> <br /></p>
        <div class="row">
            <div class="column-one">
                <img src="/assets/img/posts/SomewhereInBerkshire/collectible.png">
            </div>
        </div>
      </div>
    </div>
  </div>
  <div class="panel panel-default">
    <div class="panel-heading" role="tab" id="headingSix">
      <h4 class="panel-title">
        <a class="collapsed" role="button" data-toggle="collapse" data-parent="#accordion" href="#collapseEnvironment" aria-expanded="false" aria-controls="collapseEnvironment">
          Environmental Work & Other Work
        </a>
      </h4>
    </div>
    <div id="collapseEnvironment" class="panel-collapse collapse" role="tabpanel" aria-labelledby="headingSix">
      <div class="panel-body">
        <p>For the game, I decided maybe a new skybox was needed so it doesn't look so generic, I have never worked with skyboxes before, so I decided this was the best time to work on them! I watched a tutorial to give me an idea of how to make skyboxes in Unity, and then I went ahead and made my own, I really like how I drew the clouds.<br /></p>  
        <div class="row">
            <div class="column-one">
                <img src="/assets/img/posts/SomewhereInBerkshire/sky.png">
            </div>
        </div>
        <p><br />After this I began working on the lightning particle FX, since in the story plan for our game, we were planning to have the player struck with electric to gain electric powers, this was pretty simple to make, I began by making a sprite sheet of all of the lightning stages, I then made the particle work by making a texture sheet animation and set the grid to 4 x 1, and this is the result of my lightning:<br /></p>
        <div class="row">
            <div class="column-two">
                <img src="/assets/img/posts/SomewhereInBerkshire/lightning.png">
            </div>
            <div class="column-two">
                <img src="/assets/img/posts/SomewhereInBerkshire/lightning.gif">
            </div>
        </div>
        <p><br />The next environmental work which needed to be done was the atmosphere and fog for the game to make it feel like the player was really in an abandoned English town on a spring day, the artist of the group put together a colour palette to give us a better understanding of the atmosphere we should go for in the game, and so I followed it and created 2 different atmospheres, and in the end, the morning atmosphere was chosen, the colour palette was made by our artist, Louise<br /></p>
        <div class="row">
            <div class="column-two">
                <img src="/assets/img/posts/SomewhereInBerkshire/atmosphere.png">
            </div>
            <div class="column-two">
                <img src="/assets/img/posts/SomewhereInBerkshire/palette.png">
            </div>
        </div>
        <p><br />To go along with the mood of the game I added ambient music, we knew that Brockhampton and Berkshire were english towns, and we knew Brockhampton was an abandoned village, so we decided since these atmosphere felt spring-like we were going to go for a morning spring feeling, so I found a spring atmosphere on Gamesound.xyz, and cut it down slightly so it seamlessly looped, and I inserted it into the game, along with this, I found a guitar loop which was on looperman.com which was free to use and sounded very calming and perfect for the atmosphere of the game. <br />Once I done that I decided to add more to the atmosphere, this included small grass particles to the players feet when they move, and a grass footstep sound FX for feedback to the player, I felt like all of this is very important to add into the game to set the mood.<br /></p>
        <p>To make the beginning cutscene make sense, I decided to make a model for the sign which points toward Bockhampton, this didn’t take me long to model and texture at all and it appears in the beginning cutscene of the game, the spawn area which the player starts in and the icon.<br /></p>
        <p>I needed to work on an electricity shader effect which would be used when the player uses the lightning magic, I followed along with a video to help me create this effect, since I don’t fully understand shader graphs yet, but I learnt lots of stuff as I was following along with the video, I had also made the lightning icon which is on the lightning button, I just improved this from a placeholder one which we had there. And to give feedback to the player, I found some lightning sound FX which were used when the player was casting the lightning and when the player got shocked with the lightning <br /></p>
        <div class="row">
            <div class="column-two">
                <img src="/assets/img/posts/SomewhereInBerkshire/berkshire.gif">
            </div>
            <div class="column-two">
                <img src="/assets/img/posts/SomewhereInBerkshire/berkshire2.gif">
            </div>
        </div>
        <p><br /> To give the game more of a story, I began to add in more conditions and text messages, since in the end, we didn’t really have much of a game, so the player only ended up getting text messages when they collected a collectable, I made some extra text boxes and conditions for the player to meet so the game felt like it had more content in it. <br />Another thing which I worked on was an end screen, which would show the player their statistics when they finish playing the game, that was pretty easy to get working, and it is a nice thing to add into the game so people can have a little competition with competing for who can finish the game the fastest, or who can attack the most enemies.</p>
        <p> By this point it was getting closer to the final deadline, so I decided to work on the itch page to make it look really nice and to work on making a logo/icon for the game, I made these using Blender and Photoshop and I’m really happy with how both the itch page and logo turned out.<br /></p>
        <div class="row">
            <div class="column-two">
                <img src="/assets/img/posts/SomewhereInBerkshire/itch.png">
            </div>
            <div class="column-two">
                <img src="/assets/img/posts/SomewhereInBerkshire/itch2.png">
            </div>
        </div>
        <p><br /> Overall, I’m very happy with making this game with my team, and I really like how it turned out, although it doesn’t have as much content as the other games we have made, we all entered this Game Jam wanting to improve our own skills, and we have all certainly done that! <br /></p>
      </div>
    </div>
  </div>
</div>
</div>

<hr>

<div class="row">
    <div class="column-two">
        <div class = "card">
            <h3>Original Blog</h3>
            <p>On this page, I broke down my blog into sections, and I've taken out information which isn't as important, you can read the full blog here:</p>
            <a href="https://portfolioamyelliott.wordpress.com/portsmouth-uni-gamejam/" target="_blank" class="btn btn-dark btn-lg">Full Blog</a>
        </div>
    </div>
    <div class="column-two">
        <div class = "card">
            <h3>Game Jam Participants</h3>
            <p>I've talked about Team Horsehead a lot in this blog, and you can read more information about the team here:</p>
            <a href="/blog/authors/teamhorsehead/" target="_blank" class="btn btn-dark btn-lg">Team Horsehead</a>
        </div>
    </div>
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

