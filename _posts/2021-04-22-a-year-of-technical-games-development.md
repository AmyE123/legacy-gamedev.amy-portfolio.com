---
layout: post
title:  "A Year Of Technical Games Development"
type: "Personal Blog"
color: "background-color: firebrick"
summary: "In this blog, I discuss my Technical Games Development module, And how it helped me learn to develop my core team working skills for use in games development."
author: amyelliott
date: '2021-04-22'
category: ['personal-blog', 'university', 'unity', 'csharp', 'project-management']
thumbnail: /assets/img/posts/YearTDEMO/cover.png
keywords: university, gamejam, unity
permalink: /blog/a-year-of-technical-games-development/
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

<img src="/assets/img/posts/YearTDEMO/cover2.png" style="width: 100%; border-radius: 50px 50px">



<!--- -------------------------------------------------------------------- -->
<!--- This is for the main description of the game, this is very important -->
<!--- -------------------------------------------------------------------- -->
<p>One of my favourite modules in University has to be my Technical Games Development module (TDEMO), this module helped me learn to develop my core team working skills for use in games development, as well as this, it helped me develop my awareness of group dynamics, and gave me the opportunity to test out any potential career paths and the problems usually faced in those. <br /><br /> For this module, I made <b>5 games</b>, and in this blog I will be discussing and comparing a handful of important mechanics & problems from each of them, I would also be reflecting on those games and what I've learnt from them, and how the materials learnt in other modules have impacted my approach to certain games and mechanics made in this module.</p>

<hr>


<!--- -------------------------------------------------------- -->
<!--- This is the collapsible which I will be using.           -->
<!--- I will use these to write about what I done for the game -->
<!--- -------------------------------------------------------- -->
<div class="wrapper center-block">
    <div class="panel-group" id="accordion" role="tablist" aria-multiselectable="true">
        <div class="panel panel-default">
            <div class="panel-heading active" role="tab" id="headingOne">
                <h2 class="panel-title">
                <a role="button" data-toggle="collapse" data-parent="#accordion" href="#collapseBlockyRoad" aria-expanded="true" aria-controls="collapseBlockyRoad" style="font-size: 25px">
                    Blocky Road
                </a>
                </h2>
            </div>
            <div id="collapseBlockyRoad" class="panel-collapse collapse in collapse show" role="tabpanel" aria-labelledby="headingOne" style="margin-left: 50px">
                <div class="panel-body">
                    <img src="/assets/img/posts/YearTDEMO/blockyroad.png" style="width: 100%; border-radius: 50px 50px">
                    <br /><br />
                    <p>Blocky Road is a <b>puzzle game</b>, designed to fit around the well-known <b>'Hypercasual' genre.</b>  I had to do some research into this genre before starting to make sure I was completely clear on what type of game I could make so I can begin thinking of ideas, this definition on Wikipedia summarised the genre very well: <a href = "https://en.wikipedia.org/wiki/Hyper-casual_game" target="_blank" style="padding: 2px"> “A hyper-casual game is a mobile video game which is easy-to-play and usually free-to-play; they also feature very minimalistic user interfaces.” </a> (‘Hyper-Casual Game’, 2021) <br /> My goal for this game jam project was to make a game which can do all of that, I had a week to make this game, but I couldn’t just work on this game as there was other university work to do as well within that week, so one of my main challenges was to be able to make an enjoyable Hyper casual game <b>within 9 hours.</b> </p>
                    <div class = "card">
                        <div class="panel-group" id="accordion" role="tablist" aria-multiselectable="true">
                            <div class="panel panel-default">
                                <div class="panel-heading active" role="tab" id="headingOne">
                                    <h2 class="panel-title">
                                    <a role="button" data-toggle="collapse" data-parent="#accordion" href="#collapseBDevDiary" aria-expanded="true" aria-controls="collapseBDevDiary" style="font-size: 18px">
                                        Development Diary - What Is It, Why Am I Doing It & How Can I Keep Up With It?
                                    </a>
                                    </h2>                                
                                </div>
                                <div id="collapseBDevDiary" class="panel-collapse collapse" role="tabpanel" aria-labelledby="headingOne" style="margin-left: 50px">
                                    <div class="panel-body">
                                        <p>Development Diaries are simply what the name suggests, <i><b>a write up of the development of something in a diary structure</b></i>, I had <a href = "https://amyelliottuop.wordpress.com/technical-game-development-tdemo/game-2-23-10-20/" target="_blank" style="padding: 2px">written one myself</a> throughout the development for Blocky road to document my process. Initially, however, I found that it had been <b>difficult to keep up with this on a day-to-day basis</b>, as I had a lot to write about in little time. I thought about how I can write development logs <i>differently</i>, so I don’t have to write them each day. <br /> <img src="/assets/img/posts/YearTDEMO/br1.PNG" style="width: 40%; border-radius: 50px 50px; float: left; margin: 30px"> One reason I like writing Development Diaries is because it gives me <b>something to look back, and reflect on when I grow my skills, and it can look really good on my portfolio!</b> Another reason is, on a blog post I read, Sokolovski (2020) stated that <a href = "https://www.thegamer.com/dev-diaries-direct-updates-habit-game-studios/" target="_blank" style="padding: 2px">“Transparency and engagement with fans can positively contribute to the player-base's impression of the studio and, in turn, make them want to play the game even more, therefore attracting even more potential players.”</a> This really motivated me to keep up with my own diaries. <br /> To make sure I’m able to write <i>good</i> development diaries without forgetting important details, I figured the best way to approach this for this game in particular was to <b>build up a list of tasks</b> which I’ve done on Trello, and at the end of development, update my development diary, for other projects with a longer production time, I would update my development diary every-other-day. <br /> <b>It’s useful to be able to use Trello to note down what I was able to do, as otherwise I may have forgotten about them!</b> <br /> When I was doing this, <b>I was relying on my memory to remember what I have done on each task</b>, as I only noted down what the task was and not what I done to complete it! I think to improve, <b>I could’ve left comments or a short sentence explaining what I did for the task with some images to support that.</b></p>                                        
                                    </div>
                                </div>
                            </div>
                            <div class="panel panel-default">
                                <div class="panel-heading active" role="tab" id="headingOne">
                                    <h2 class="panel-title">
                                    <a role="button" data-toggle="collapse" data-parent="#accordion" href="#collapseBMovementUI" aria-expanded="true" aria-controls="collapseBMovementUI" style="font-size: 18px">
                                        Charge Movement User Interface
                                    </a>
                                    </h2>                                
                                </div>
                                <div id="collapseBMovementUI" class="panel-collapse collapse" role="tabpanel" aria-labelledby="headingOne" style="margin-left: 50px">
                                    <div class="panel-body">
                                        <img src="/assets/img/posts/YearTDEMO/br3.PNG" style="width: 30%; border-radius: 50px 50px; float: left; margin: 30px"><p>For my game, I needed some way of telling the player how much they can charge up their movement before they move, so I came up with a circle charge UI design, Quintans (2013) gave an example of Good UI by mentioning <a href = "https://gamedevelopment.tutsplus.com/tutorials/game-ui-by-example-a-crash-course-in-the-good-and-the-bad--gamedev-3943" target="_blank" style="padding: 2px">“the role of a good UI is to provide relevant information clearly and quickly, and to get out of the way once it has done its job.”</a> – So, I took that into consideration when implementing the charge movement which follows the players mouse. <br /> The reason why I had to implement this way of movement is because I couldn’t use the WASD keys to move the player character, instead, I had to think of how to <b>move the player with a single key</b>, so the entire game can be played with one key. This makes the game <b>easy-to-play for anyone.</b> <br /> For the visual side of the charge movement, I made 2 transparent rings in Photoshop, and applied the code of the charging to the fill of one of the rings inside of Unity. <br /> I got this working pretty quickly, as I already had all the code I needed in place, but there was a bug which I had, which I couldn’t fix in the time I had. <br /> <img src="/assets/img/posts/YearTDEMO/br2.PNG" style="width: 20%; border-radius: 50px 50px; float: right; margin: 30px">  For me, this was one of the most <b>significant bugs</b> in the game, and in more detail, the bug was that the bar would fill up, and go up to being full, but then I would want it to go back to 1, instead, the bar never got to 4, and then skipped right to 1, so in the end, I made the bar so it stayed full once you’ve already charged it to 4. <br /> <b>At the time I felt this was fine</b>, but looking back onto this broken UI now, <b><i>it doesn’t make any sense to a new player</i></b>, and may confuse them when they’re playing. <br /> This understanding will be essential to me going forward, <b>if I ever want to further develop this game, I know what to work on and fix first.</b></p>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                    <br />
                    <h3> Reflection on Blocky Road </h3>
                    <p>Overall, making Blocky Road was a <b>creative, and technical challenge</b> for me, but a challenge I was happy to take on! It allowed me to <b>push my creativity, whilst also trying to stick to the genre</b> – Which is one I’ve never explored before! <br /> Having experienced developing one of my own hyper casual games I now know I really enjoy making them, and <b>it’s something I can look into for any future games!</b> Something I’m interested in doing with this game in the future, is <b>putting it on the Google Playstore</b>, as this game was <b>designed from the ground up with mobile gaming in mind.</b> <br /> My <b>TOGA</b> (Tools for Games & Animation) module helped me out with making this game as well, as during that module, we were tasked to <b>design simple systems to use in simple text-based games</b>, and though this game isn’t text based, it is simple, so I was able to design my game systems <b>with those good practices in mind.</b></p>
                    <br />
                    <img src="/assets/img/posts/YearTDEMO/br4.PNG" style="width: 30%; border-radius: 10px 10px; float: right; margin: 30px"><h3> Ranking & Player Feedback </h3>
                    <p>This game ranked <b>#1</b> Overall, which I was really happy with! <br /> There was some positive feedback which I got when I first uploaded the game to the game jam! I uploaded the game early so I could get any feedback on bugs and do a version 2 of the game before the end of the game jam! <br /> Some of the main bugs or quality fixes which I had gotten in the feedback was minor, and only required quick fixes which I would be able to do with the time I had left on the game jam, and once these were fixed, a version 2 of the game was released!</p>
                    <br />
                    <iframe frameborder="0" src="https://itch.io/embed/801093?border_width=2&amp;bg_color=1c1c1e&amp;fg_color=ffffff&amp;border_color=1c1c1e" width="100%" height="169" style="box-shadow: 1px 2px 8px #151517"><a href="https://amy-elliott.itch.io/blockyroads">Blocky Road by Amy Elliott</a></iframe>
                </div>
            </div>
        </div>
        <hr>
        <div class="panel panel-default">
            <div class="panel-heading active" role="tab" id="headingOne">
                <h2 class="panel-title">
                <a role="button" data-toggle="collapse" data-parent="#accordion" href="#collapsePetPal" aria-expanded="true" aria-controls="collapsePetPal" style="font-size: 25px">
                    Pet Pal
                </a>
                </h2>
            </div>
            <div id="collapsePetPal" class="panel-collapse collapse in collapse show" role="tabpanel" aria-labelledby="headingOne" style="margin-left: 50px">
                <div class="panel-body">
                    <img src="/assets/img/posts/YearTDEMO/petpal.png" style="width: 100%; border-radius: 50px 50px">
                    <br /><br />
                    <p>Pet Pal is a <b>clicker game</b>, designed to fit around the <b>‘Incremental’ genre.</b> I knew this genre pretty well from the famous mobile and browser game Cookie Clicker where <a href="https://en.wikipedia.org/wiki/Cookie_Clicker" target="_blank" style="padding: 2px">“The user initially clicks on a big cookie on the screen, earning a single cookie per click. They can then spend their earned cookies upon purchasing assets that automatically produce cookies.”</a> (<i>‘Cookie Clicker’</i>, 2021). <br /> My teams' goal for this game jam was to make a simple 2D incremental game, it was the first group game jam in this module, and I was in a team of 5, including mysef, so we had to learn how to work together. Our group had <b>a week to make this game</b>, but as we were a group there was less stress as each of us were working on a specialism.</p>
                    <div class = "card">
                        <div class="panel-group" id="accordion" role="tablist" aria-multiselectable="true">                       
                            <div class="panel panel-default">
                                <div class="panel-heading active" role="tab" id="headingOne">
                                    <h2 class="panel-title">
                                    <a role="button" data-toggle="collapse" data-parent="#accordion" href="#collapseMec3" aria-expanded="true" aria-controls="collapseMec3" style="font-size: 18px">
                                        Insert Mechanic/Problem/Something here
                                    </a>
                                    </h2>                                
                                </div>
                                <div id="collapseMec3" class="panel-collapse collapse" role="tabpanel" aria-labelledby="headingOne" style="margin-left: 50px">
                                    <div class="panel-body">
                                        <p>Text here</p>
                                    </div>
                                </div>
                            </div>
                            <div class="panel panel-default">
                                <div class="panel-heading active" role="tab" id="headingOne">
                                    <h2 class="panel-title">
                                    <a role="button" data-toggle="collapse" data-parent="#accordion" href="#collapseMec4" aria-expanded="true" aria-controls="collapseMec4" style="font-size: 18px">
                                        Insert Second Mechanic/Problem/Something here
                                    </a>
                                    </h2>                                
                                </div>
                                <div id="collapseMec4" class="panel-collapse collapse" role="tabpanel" aria-labelledby="headingOne" style="margin-left: 50px">
                                    <div class="panel-body">
                                        <p>Text here</p>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                    <br />
                    <h3> Reflection on Pet Pal </h3>
                    <p>Reflection Work</p>
                    <br />
                    <iframe frameborder="0" src="https://itch.io/embed/809572?border_width=2&amp;bg_color=1c1c1e&amp;fg_color=ffffff&amp;border_color=1c1c1e" width="100%" height="169" style="box-shadow: 1px 2px 8px #151517"><a href="https://laylamccahon.itch.io/pet-pals">Team ; : Pet Pal by LaylaMcCahon, xXbollerXx, Amy Elliott, Lewis Roberts, Jacob Kelly</a></iframe>
                </div>
            </div>
        </div>
        <hr>
        <div class="panel panel-default">
            <div class="panel-heading active" role="tab" id="headingOne">
                <h2 class="panel-title">
                <a role="button" data-toggle="collapse" data-parent="#accordion" href="#collapsePopHop" aria-expanded="true" aria-controls="collapsePopHop" style="font-size: 25px">
                    Poppin' Hoppin' Unlockin'
                </a>
                </h2>
            </div>
            <div id="collapsePopHop" class="panel-collapse collapse in collapse show" role="tabpanel" aria-labelledby="headingOne" style="margin-left: 50px">
                <div class="panel-body">
                    <img src="/assets/img/posts/YearTDEMO/pophop.png" style="width: 100%; border-radius: 50px 50px">
                    <br /><br />
                    <p>Poppin’ Hoppin’ Unlockin’ is a <b>puzzle game</b>, designed to fit around the <b>‘Platformer’ genre.</b> This genre is popular and most influenced from games such as Super Mario Bros because <a href="https://en.wikipedia.org/wiki/Platform_game" target="_blank" style = "padding: 2px">“Its success as a pack-in led many companies to see platform games as vital to their success and contributed greatly to popularizing the genre during the 8-bit console generation.”</a> (‘Platform Game’, 2021). <br /> My teams’ goal for this game jam project was to make a stylish 3D platformer with a back story, we were all a bit more confident approaching this game jam as we had practice from the previous. Our group had <b>2 weeks to make this game</b>, but again, as we were a group there was less stress as each of us were working on a specialism. </p>
                    <div class = "card">
                        <div class="panel-group" id="accordion" role="tablist" aria-multiselectable="true">
                            <div class="panel panel-default">
                                <div class="panel-heading active" role="tab" id="headingOne">
                                    <h2 class="panel-title">
                                    <a role="button" data-toggle="collapse" data-parent="#accordion" href="#collapseMec5" aria-expanded="true" aria-controls="collapseMec5" style="font-size: 18px">
                                        Insert Mechanic/Problem/Something here
                                    </a>
                                    </h2>                                
                                </div>
                                <div id="collapseMec5" class="panel-collapse collapse" role="tabpanel" aria-labelledby="headingOne" style="margin-left: 50px">
                                    <div class="panel-body">
                                        <p>Text here</p>
                                    </div>
                                </div>
                            </div>
                            <div class="panel panel-default">
                                <div class="panel-heading active" role="tab" id="headingOne">
                                    <h2 class="panel-title">
                                    <a role="button" data-toggle="collapse" data-parent="#accordion" href="#collapseMec6" aria-expanded="true" aria-controls="collapseMec6" style="font-size: 18px">
                                        Insert Second Mechanic/Problem/Something here
                                    </a>
                                    </h2>                                
                                </div>
                                <div id="collapseMec6" class="panel-collapse collapse" role="tabpanel" aria-labelledby="headingOne" style="margin-left: 50px">
                                    <div class="panel-body">
                                        <p>Text here</p>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                    <br />
                    <h3> Reflection on Poppin' Hoppin' Unlockin' </h3>
                    <p>Reflection Work</p>
                    <br />
                    <iframe frameborder="0" src="https://itch.io/embed/817536?border_width=2&amp;bg_color=1c1c1e&amp;fg_color=ffffff&amp;border_color=1c1c1e" width="100%" height="169" style="box-shadow: 1px 2px 8px #151517"><a href="https://amy-elliott.itch.io/poppin-hoppin-unlockin">Poppin' Hoppin' Unlockin' by Amy Elliott, Gabe, UP2014114, Mohamed.Elfayoumy, Ben Webb, Bryce Reading, Rob Cole, UP2023255</a></iframe>
                </div>
            </div>
        </div>
        <hr>
        <div class="panel panel-default">
            <div class="panel-heading active" role="tab" id="headingOne">
                <h2 class="panel-title">
                <a role="button" data-toggle="collapse" data-parent="#accordion" href="#collapseAqua" aria-expanded="true" aria-controls="collapseAqua" style="font-size: 25px">
                    Aqua Adventure
                </a>
                </h2>
            </div>
            <div id="collapseAqua" class="panel-collapse collapse in collapse show" role="tabpanel" aria-labelledby="headingOne" style="margin-left: 50px">
                <div class="panel-body">
                    <img src="/assets/img/posts/YearTDEMO/aqua.png" style="width: 100%; border-radius: 50px 50px">
                    <br /><br />
                    <p>Aqua Adventure is an <b>on-rails shooter game</b>, designed to fit around the <b>‘StarFox’ theme.</b> This theme is based off of, well, you guessed it; Nintendo’s beloved StarFox series! Mainly the 1993 title. <a href="https://en.wikipedia.org/wiki/Star_Fox" target="_blank" style="padding: 2px">“StarFox is a spaceship shooter and third person action-adventure video game”</a> (<i>‘Star Fox’</i>, 2021) – This Wikipedia article is where we got the idea of what genres to base our game off of. <br /> My teams’ goal for this game jam was to make an underwater on-rails shooter, <b>we had 2 weeks.</b> This group mostly consisted of artists and 3D modellers, so I happily proposed to take on the entirety of the programming myself as a personal challenge. </p>
                    <div class = "card">
                        <div class="panel-group" id="accordion" role="tablist" aria-multiselectable="true">
                            <div class="panel panel-default">
                                <div class="panel-heading active" role="tab" id="headingOne">
                                    <h2 class="panel-title">
                                    <a role="button" data-toggle="collapse" data-parent="#accordion" href="#collapseMec7" aria-expanded="true" aria-controls="collapseMec7" style="font-size: 18px">
                                        Insert Mechanic/Problem/Something here
                                    </a>
                                    </h2>                                
                                </div>
                                <div id="collapseMec7" class="panel-collapse collapse" role="tabpanel" aria-labelledby="headingOne" style="margin-left: 50px">
                                    <div class="panel-body">
                                        <p>Text here</p>
                                    </div>
                                </div>
                            </div>
                            <div class="panel panel-default">
                                <div class="panel-heading active" role="tab" id="headingOne">
                                    <h2 class="panel-title">
                                    <a role="button" data-toggle="collapse" data-parent="#accordion" href="#collapseMec8" aria-expanded="true" aria-controls="collapseMec8" style="font-size: 18px">
                                        Insert Second Mechanic/Problem/Something here
                                    </a>
                                    </h2>                                
                                </div>
                                <div id="collapseMec8" class="panel-collapse collapse" role="tabpanel" aria-labelledby="headingOne" style="margin-left: 50px">
                                    <div class="panel-body">
                                        <p>Text here</p>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                    <br />
                    <h3> Reflection on Aqua Adventure </h3>
                    <p>Reflection Work</p>
                    <br />
                    <iframe frameborder="0" src="https://itch.io/embed/838435?border_width=2&amp;bg_color=1c1c1e&amp;fg_color=ffffff&amp;border_color=1c1c1e" width="100%" height="169" style="box-shadow: 1px 2px 8px #151517"><a href="https://amy-elliott.itch.io/aqua-adventure">Aqua Adventure by Amy Elliott, scarlettyeats0, up2015448TessaSmith, Hannahwaard, UP2022388 Hayley L, Denisa Maximova-2032161, Abbymcgreavey1</a></iframe>
                </div>
            </div>
        </div>
        <hr>
        <div class="panel panel-default">
            <div class="panel-heading active" role="tab" id="headingOne">
                <h2 class="panel-title">
                <a role="button" data-toggle="collapse" data-parent="#accordion" href="#collapseSub" aria-expanded="true" aria-controls="collapseSub" style="font-size: 25px">
                    Submarine Simulator
                </a>
                </h2>
            </div>
            <div id="collapseSub" class="panel-collapse collapse in collapse show" role="tabpanel" aria-labelledby="headingOne" style="margin-left: 50px">
                <div class="panel-body">
                    <img src="/assets/img/posts/YearTDEMO/sub.png" style="width: 100%; border-radius: 50px 50px">
                    <br /><br />
                    <p>Submarine Simulator is a <b>Planesman trainer</b>, designed and made for <b>The Royal Navy’s Recruitment Events.</b> Our target audience for this game are young teenagers ranging from 12-16, as they would be the ones attending these events. <br /> My teams’ goal for this game jam project was to make a fun and engaging, but short gameplay loop of around 90-120 seconds where the player gets to control both the planesman and the periscope view, and it also had to impress our clients! <br /> I gathered the group from other students who I’ve enjoyed working with in the past game jams or have seen good work from. Our group had around <b>5 months to make this simulator</b>, at the beginning, there was less stress as we were a 7-person group (including myself) so each of us worked on our own specialism, but nearer the end, it got a bit more stressful, as we all took on multiple specialisms to get the simulator finished on time. </p>
                    <div class = "card">
                        <div class="panel-group" id="accordion" role="tablist" aria-multiselectable="true">
                            <div class="panel panel-default">
                                <div class="panel-heading active" role="tab" id="headingOne">
                                    <h2 class="panel-title">
                                    <a role="button" data-toggle="collapse" data-parent="#accordion" href="#collapseMec9" aria-expanded="true" aria-controls="collapseMec9" style="font-size: 18px">
                                        Insert Mechanic/Problem/Something here
                                    </a>
                                    </h2>                                
                                </div>
                                <div id="collapseMec9" class="panel-collapse collapse" role="tabpanel" aria-labelledby="headingOne" style="margin-left: 50px">
                                    <div class="panel-body">
                                        <p>Text here</p>
                                    </div>
                                </div>
                            </div>
                            <div class="panel panel-default">
                                <div class="panel-heading active" role="tab" id="headingOne">
                                    <h2 class="panel-title">
                                    <a role="button" data-toggle="collapse" data-parent="#accordion" href="#collapseMec10" aria-expanded="true" aria-controls="collapseMec10" style="font-size: 18px">
                                        Insert Second Mechanic/Problem/Something here
                                    </a>
                                    </h2>                                
                                </div>
                                <div id="collapseMec10" class="panel-collapse collapse" role="tabpanel" aria-labelledby="headingOne" style="margin-left: 50px">
                                    <div class="panel-body">
                                        <p>Text here</p>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                    <br />
                    <h3> Reflection on Submarine Simulator </h3>
                    <p>Reflection Work</p>
                </div>
            </div>
        </div>
    </div>
</div>

<hr>

<h2> Final Evaluation & Reflection </h2>
<p>text here</p>

<hr>