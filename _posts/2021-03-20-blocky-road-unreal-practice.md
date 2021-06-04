---
layout: post
title:  "Blocky Road in Unreal Engine C++ Practice"
type: "Study Blog"
color: "background-color: darkslateblue"
summary: "I decided to tackle Unreal Engine C++ straight on to remake one of my older game jam games."
author: amyelliott
date: '2021-03-20'
category: ['study', 'self-directed', 'programming']
thumbnail: /assets/img/posts/BlockyRoadUnreal/cover.png
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
    <div id="collapseOverview" class="panel-collapse collapse in collapse show" role="tabpanel" aria-labelledby="headingOne">
      <div class="panel-body">
        <p>Like mentioned in the About section, I tackled this project to learn Unreal Engine's C++. <br /> Beforehand, I have made a few small things using blueprints and I have worked on Unreal Engine C++ courses, but all I was doing was following along with the courses, I didn't feel as if I was learning much, so I decided that I should remake Blocky Road, so I can do my own research and implementation of code, and with that technique, I learnt much better then taking the courses which I have.<br /> Of course, as Unreal Engine's C++ and general C++ feel very different, I didn't do this without the help of tutorials, documentation and forums, on the sections of the blog, I mention tutorials and forums which I have used to help me out. <br /> I didn't do the full Game Jam hours either, I wasn't worrying too much if I couldn't submit on time as my studying took prioirity over submitting on time, so I accepted that if I wasn't ready by the end of the game jam, it wasn't an issue. <br /> <br /> In the end, I'm aware that I didn't get much done at all, but I feel like with more practice I will speed up overtime, as I have learnt from any mistakes which I have made on this project.</p>
      </div>
    </div>
  </div>
  <div class="panel panel-default">
    <div class="panel-heading" role="tab" id="headingTwo">
      <h4 class="panel-title">
        <a class="collapsed" role="button" data-toggle="collapse" data-parent="#accordion" href="#collapseGridMovement" aria-expanded="true" aria-controls="collapseGridMovement">
          Grid Movement
        </a>
      </h4>
    </div>
    <div id="collapseGridMovement" class="panel-collapse collapse in collapse show" role="tabpanel" aria-labelledby="headingTwo">
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
        <a class="collapsed" role="button" data-toggle="collapse" data-parent="#accordion" href="#collapseTrigger" aria-expanded="true" aria-controls="collapseTrigger">
          Trigger Box To Next Level
        </a>
      </h4>
    </div>
    <div id="collapseTrigger" class="panel-collapse collapse in collapse show" role="tabpanel" aria-labelledby="headingThree">
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
        <!---<p><br />But after I completed this, I found that I had ran into an error which I had no idea how to fix. Although the game worked fine when I pressed play, whenever I would compile the code I would get this error message:<br /></p>-->
      </div>
    </div>
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

