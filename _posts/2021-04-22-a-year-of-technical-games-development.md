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
                                    <a role="button" data-toggle="collapse" data-parent="#accordion" href="#collapsePGL" aria-expanded="true" aria-controls="collapsePGL" style="font-size: 18px">
                                        Being A Group Lead For The First Time - What I Did, Why I Did It, & How I Made Sure Everything Turned Out Okay.
                                    </a>
                                    </h2>                                
                                </div>
                                <div id="collapsePGL" class="panel-collapse collapse" role="tabpanel" aria-labelledby="headingOne" style="margin-left: 50px">
                                    <div class="panel-body">
                                        <p>One thing I have always wanted to do was be a <b>group lead for a game jam</b>, and this is because <b>I wanted to know what the workflow was like, and if I would be a good lead.</b> <br /> At first, I thought that being a group lead meant that I deal with some project management and have <i>plenty</i> of time to work on other things for the game, in my case, the programming, but <b>I quickly learnt that this wasn’t the case.</b> <br /> <br /> As I was new to leading, I had to learn a bit more about it. Kantilaftis (2014) wrote an excellent blog post called <a href="https://www.nyfa.edu/student-resources/forming-solid-indie-game-development-team/" target="_blank" style="padding: 2px">‘How To Form A Solid Indie Game Development Team’</a> – This blog post gave me an insight on the many different roles that could be taken on in Games Development excluding the handful which I already knew about. <b>Kantilaftis’s description of a Project Manager helped me realise what my role was</b>, as quoted by her; <a href="https://www.nyfa.edu/student-resources/forming-solid-indie-game-development-team/" target="_blank" style="padding: 2px">“(their) responsibility is to make sure the team works fast and efficiently.” </a> She followed this by answering our burning question of <i><b>why</b></i> it should be done; <a href="https://www.nyfa.edu/student-resources/forming-solid-indie-game-development-team/" target="_blank" style="padding: 2px">“(they) will be the one that sets milestones for the team and sees to it that they are achieved in a reasonable time frame”</a> and <i><b>how</b></i> to do so; <a href="https://www.nyfa.edu/student-resources/forming-solid-indie-game-development-team/" target="_blank" style="padding: 2px">“This involves motivating team members that fall behind and making sure everyone is performing their tasks.”</a> <br /> To make sure members are <b>performing their tasks, staying motivated and not falling behind</b>, I made a <b>working schedule</b> for the group, as it was only a weeklong game jam, we <b>each</b> put in around <b>7 to 9 hours</b> into this game. <br /> For me, the most <b>useful</b> way I knew to stay on track was to <b>not cram work in</b> at once, but to instead <b>work in chunks of 3 hours</b>, this ensures we can <b>stay focused</b>, we aren’t putting in <b>too many hours</b> and we are working to the <b>best of our abilities</b>. <img src="/assets/img/posts/YearTDEMO/pp1.png" style="width: 50%; border-radius: 10px 10px; float: right; margin: 30px"> At the time, <i><b>I didn’t think about how everyone may have different schedules</b></i>, alternatively, keeping the team on a work schedule <i>can be good</i>, as it’s not long term, and it ensures everyone is working at the same time. <br /> <br /> On my <a href="https://amyelliottuop.wordpress.com/technical-game-development-tdemo/game-3-30-10-20/" target="_blank" style="padding: 2px">development diary</a>, I wrote about how some members <b>weren’t available during the sessions</b>, so I trusted them to work on their own accord to reach the same amount of work hours as everyone else in the group, <b>I had no way of checking the working hours</b>, so it was <b>entirely possible</b> that group members who aren’t available during the scheduled hours may <b>overwork or underwork</b> themselves, <b><i>in the future</i>, if I were to lead another project, this is something which I could do further research into, and improve on</b>. To check our members were performing their tasks, for each working session, we joined a group call, and during this group call, <b>I checked where everyone is</b> and their <b>plan of action</b> for the session, I would also work on <b>assigning tasks</b> by sharing my screen and <b>going through our groups Trello task list.</b> We would remain on the call whilst we worked just to <b>simulate a work environment.</b></p>
                                    </div>
                                </div>
                            </div>
                            <div class="panel panel-default">
                                <div class="panel-heading active" role="tab" id="headingOne">
                                    <h2 class="panel-title">
                                    <a role="button" data-toggle="collapse" data-parent="#accordion" href="#collapsePSC" aria-expanded="true" aria-controls="collapsePSC" style="font-size: 18px">
                                        Teaching Source Control
                                    </a>
                                    </h2>                                
                                </div>
                                <div id="collapsePSC" class="panel-collapse collapse" role="tabpanel" aria-labelledby="headingOne" style="margin-left: 50px">
                                    <div class="panel-body">
                                        <p><img src="/assets/img/posts/YearTDEMO/pp2.png" style="width: 30%; border-radius: 10px 10px; float: right; margin: 30px">Teaching and explaining source control is <b>very important</b>, especially for a group project like this, since we are all working on the same Unity Project, but I thought to make things easier and to get less conflicts, I would <i>only set up, and teach git to the programmers of the group</i>, so that means Layla and Fabio, it would be extra unneeded work to set up git for the artists for a game which we are only going to work on shortly. <br /> I <b>explained source control</b>  and <b>how it worked</b> to <b>everyone</b> on a discord call, and then guided Layla and Fabio through <b>how</b> to install Github Desktop and <b>use it</b> with the games repository, which I had set up with an empty Unity Project. <br /> I <b>explained why it is important</b> to have <b>useful, descriptive comments on each commit</b> and how they should try not to <b>work on the same stuff</b> at the same time to <b>avoid coming across conflicts</b> (We never even got one!) We avoided working on multiple branches and just <b>pushed all of our commits to the master branch</b>, since the game is only a small game. They both picked up how it worked <b>very quickly</b>, so in the end working on this game with source control made it so much easier then working on separate unity projects!</p>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                    <br />
                    <h3> Reflection on Pet Pal </h3>
                    <p>Overall, making Pet Pal was a great opportunity for me to <b>lead and teach</b>, which I’ve discovered is something I’m quite interested in, so now I know <b>leadership is something I can consider for any future careers.</b> For me, one of the most <b>significant experiences</b> arose from <b>teaching source control to the team</b>, as later on in the module, I found myself teaching source control multiple times for each game jam group. <br /> I personally didn’t like Pet Pal, so I don’t see it going much further than it has. I see clicker games like this quite boring, and the game itself isn’t unique, although given an opportunity to expand this game, I feel it would have to be <i>remade from the beginning again</i>, including all assets, with a more creative twist to the game to make it more unique. <br /> <img src="/assets/img/posts/YearTDEMO/pp4.PNG" style="width: 30%; border-radius: 10px 10px; float: right; margin: 30px"> My <b>Image Creation</b> module helped me, and most likely my teammates out with making assets for this game, as <b>Photoshop was used to produce art assets for the game</b>, another module which I find helped the programmers was <b>TOGA (Tools for Games & Animation)</b> as at this point, the <b>programming fundamentals</b> were being taught, and these fundamentals were used in the game.</p>
                    <h3> Ranking, Group & Player Feedback </h3>
                    <p>This game ranked <b>#15</b> Overall, which is quite a low ranking, but I wasn’t too surprised given the simplistic gameplay, now I feel <img src="/assets/img/posts/YearTDEMO/pp6.png" style="width: 30%; border-radius: 10px 10px; float: right; margin: 30px"><b>we could’ve scored higher if we had been a little more creative</b> with the idea and having discussed our opinions on the game with the rest of the group a few months after we finished the game, <b>the other team members felt much the same.</b> <br /> I asked for feedback on my leadership from the rest of the group to see how I did and how I can improve. The responses which I have gotten were <b>all positive, which is great! </b> Key words which I have picked out from this feedback was that when leading the game, I showed that I was <b>“Organised”</b>, <b>“[Kept things] within scope”</b>, <b>“Ensured [the group] stayed on task”</b> and <b>“Made sure [the group] finished early so we could improve the game based on feedback”</b> – And for me, the most useful positive feedback which I got was the last point of finishing the game early to get feedback, as <b>for future games, I tried my best to enforce this idea.</b><br /> Here is some feedback which we have got from some players:</p> 
                    <img src="/assets/img/posts/YearTDEMO/pp3.png" style="border-radius: 10px 10px; width: 100%; text-align: center">
                    <br />
                    <!--<div class="row">
                        <div class="column-two" style="text-align: center">
                            <img src="/assets/img/posts/YearTDEMO/pp_1.png" style="border-radius: 10px 10px; margin: 50px; text-align: center">                           
                            <img src="/assets/img/posts/YearTDEMO/pp_4.png" style="border-radius: 10px 10px; margin: 50px; text-align: center">                            
                        </div>
                        <div class="column-two" style="text-align: center">         
                            <img src="/assets/img/posts/YearTDEMO/pp_3.png" style="border-radius: 10px 10px; margin: 20px; text-align: center">
                            <img src="/assets/img/posts/YearTDEMO/pp_2.png" style="border-radius: 10px 10px; margin: 20px; text-align: center">
                        </div>
                    </div>-->
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