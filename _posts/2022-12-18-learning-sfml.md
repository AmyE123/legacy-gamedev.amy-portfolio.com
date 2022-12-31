---
layout: post
title:  "I Learnt About SFML & CMake. Here's My Process."
type: "Study Blog"
color: "background-color: darkslateblue"
summary: "From some research, learning about build tools and graphics libraries is benificial for my future roles in the games industry. This was a University assignment."
author: amyelliott
date: '2022-12-18'
category: ['other', 'study', 'research', 'development']
thumbnail: https://am3pap005files.storage.live.com/y4mDRUUPodeb9B4xSjYfTgnlrmsU4TF8nitwAViZjIwdhIPWUYT_AsA7SnUCLKN9HHH91qy4tMMo0WCbJS5dCvaqLrLKq_IApr0T-fTgojV7Z87PyXgznGu5vj6kb6ryG41-Z_RZgrxufLTYUMMldUI_yli1UA9GxU_EjQJKCAhnCpSD0hOVYviY7yrLP1z2x2n?width=1920&height=1634&cropmode=none
keywords: personal, education
permalink: /blog/i-learnt-about-sfml-cmake/
usemathjax: true
---

<hr>
<div class="table-mobile">
    <table>
        <tr>
            <th style="border: 0px !important">Date Project Finished:</th>
            <th style="text-align:right; border: 0px !important"><small class="btn btn-col status-button">14th</small><small class="btn btn-col status-button">December</small><small class="btn btn-col status-button">2022</small></th>
        </tr>
    </table>
</div>
<hr>

<img class="image-heading" src="https://am3pap005files.storage.live.com/y4mWFg5YENa6O4jy31g0QA1wRHN1grbsMtUnHPK7qGoQ-2qujfvVNhNSSAuNuZXJ0DnVbxVxm-o-ry1Obz1vxc7qZrlinjhFg1u17yhUwXrVitBzc193xAOvwAdiDVs4LrzzacoK0nfxfViQncV6HedC5MG9h2YGtCU4a0cGJxvzpGu1e7-FY8nX0k9EOYxfEG1?width=1024&height=684&cropmode=none" style="height: 200px !important; object-position: 50% 60% !important;">
<h3 id="Proposal" style="text-align:center; margin-top: 20px; margin-bottom: 20px">Research, Analysis, & Justification for Choice of API</h3>
<h4>Goals</h4>
<p>With the time I’ve spent working in the Games Industry and building my career, I’ve learnt a lot, and I still am learning new things every day, and my experience has just made me much more aware and prepared to realise where my weaknesses are at.</p>
<p>Because I was at Jagex (Gower &amp; Gower, 2000) for 3 months, I only briefly used C++ (Stroustrup, 1985) with Unreal Engine 4 (Unreal Engine, 2019), and C++ with a Proprietary Engine for Old School Runescape (Jagex, 2007), - I learnt a lot at Jagex, but I never got to the point like at Sumo Digital (Dunn &amp; Woods, 2003) and Altered Gene (Gayle, 2013) where I’ve been there much longer so I got very used to the tools I am using.</p>
<p><br />Because of all of this, I feel I’m at a disadvantage now, because I’ve grown too comfortable with the tools I’ve been using at Sumo Digital and Altered Gene.</p>
<ul>
<li>I would love to be as <strong>confident</strong> as I am in Unity and C# with Unreal and C++. </li>
<li>I would love to be able to <strong>adapt</strong> to new things quicker!</li>
<li>And, I would love to be at a point where <strong>I don’t care what engine or language</strong> I’m using!</li>
</ul>

<h4>Project Research</h4>
<h5>Initial Project Proposal</h5>
<p>I was considering doing something in Unreal Engine, but I wasn’t really keen on that because I already knew how to use Unreal Engine, so I would rather push myself a bit more and do something else which didn’t include an engine.</p>
<p>So, before I began doing further research, my initial idea was to use a graphics library called ‘<a href="https://www.raylib.com/">RayLib</a>’ (Santamaria &amp; Contributors, 2013), to recreate one of my older games, ‘<a href="https://amy-elliott.itch.io/blockyroads">Blocky Road</a>’ (Elliott, 2020) (See figure 1), when I’ve been learning new engines, like Godot (Linietsky &amp; Manzur, 2014) and Unreal Engine, I always like recreating this game, it is like my own ‘Hello World’ when I come to learn new game engines. <br />Doing this also means I don’t get distracted by designing anything for the game, as that has already been done! </p>

<img class="center-img3" src="https://am3pap005files.storage.live.com/y4mPn1WkgRsghLmUwQvlESiFhz9CA2_MVIdf-nRWpwXIh7XV_s2hR4vufjiJAw50e3ldQu2cpGg0iJgzCLQGE0sFuMGMNRCLuBwbfALYypxZ743-dxt4r2XGomRxQjCK5RRqiOdQ92hwEisL757TFrYeRrFGfXeNldh8MJHco7PhvhpKs_57aVuQpjpUKw86OJi?width=488&height=272&cropmode=none">
<p style="text-align:center"><small>Figure 1: Blocky Road Screenshot</small></p>

<p>I did further research into RayLib by looking through the <a href="https://www.raylib.com/examples.html">example code on their website</a>, and I contacted a professional friend of mine to get her opinion on RayLib.</p>
<p>From my research, I figured that I should review my goals for this module again, as RayLib is quite high-level, which means <em>“it will include all of the bells and whistles which would make things much too easy for this project”</em> (A. Smith, personal communication, 2022a), and I wouldn’t be challenging myself enough.</p>

<h4>Project Research, Analysis &amp; Justification</h4>
<p>From here on out, I decided, as I was challenging myself more, I will change the project, instead of recreating Blocky Road, I will create something that can be made in 2D, with a lower-level graphics library. So, I wrote up a few game briefs.</p>
<h5>Graphics Libraries</h5>
<p>I already decided that I wasn’t going to be using RayLib, so the other graphics libraries that I had in mind were SFML (Gomila &amp; SFML Team, 2007) and SDL (Lantinga &amp; Valve Corporation, 1998).</p>

<p>I found out about SDL through a YouTuber called <a href="https://www.youtube.com/c/PolyMars/videos">PolyMars</a> (Wismar, 2017), and two of his videos titled ‘<a href="https://youtu.be/EAMHQfCGymg">Learning SDL2 in 48 Hours</a>’ (PolyMars, 2020) and ‘<a href="https://youtu.be/iEn0ozP-jxc">Making a Game With C++ and SDL2</a>’ (PolyMars, 2021).</p>
<h5>Game Briefs</h5>
<h6>Gobblet Gobblers</h6>
<p>I plan to make a 2D version of <a href="https://youtu.be/nYvYEhBG9HM">Gobblet Gobblers</a> (Denoual, 2003) - Which is a board game, a bit like Tic-Tac-Toe (<em>Tic-Tac-Toe</em>, n.d.) with a twist, and that is that you have 3 sizes of gobblets and they can gobble up your opponent’s pieces if they’re larger than the one placed down.</p>
<h6>Cubey Road</h6>
<p>My 2nd idea is I will be remaking a 2D game inspired by ‘Blocky Road’, with some of the same concepts but adjusted to work well in 2D with some more challenging puzzles, the downside to this is that it would require more design which isn’t what I want to focus on for this module.</p>
<h6>Puzzle Game</h6>
<p>My 3rd idea is making a puzzle game where the player needs to navigate an area to get to the end point without going over the same grid block again, there was a minigame I remember on Club Penguin (<em>Club Penguin</em>, 2005) called ‘Thin Ice’ which I was inspired by.</p>

<h4>Final Project Proposal</h4>
<h5>Further Research, Analysis &amp; Justification</h5>
<p>The idea I have chosen out of the three game briefs is Gobblet Gobblers, because I recently threw together a <a href="https://amy-elliott.itch.io/tactics-toe-3hr-gamejam">really small prototype</a> of this game in Unity during a 3 hour game jam, I could go back to this code to break it down so I have a reference on one way of how I can design my systems, I also think this game is quite fun, and not too design-heavy, so I can focus all my time on my goals.</p>
<p>When it comes to picking the graphics library, there is never a perfect tool for the job. “None of them are better than the others, and they can all achieve the same things, but they do have their differences” (A. Smith, personal communication, 2022b).<br />But with this in mind, I shouldn’t be picking an API just because it’s a ‘favorite’, it’s important to be impartial and admit when something isn’t suitable for the job at hand, much like I did with RayLib.</p>
<p>I decided SFML would be the best for my project, and the reason for this is that upon googling ‘SFML or SDL’ there are A LOT of posts from people in my exact position not knowing which one to use, and reading through the many forums, <a href="https://www.reddit.com/r/gamedev/comments/fk8c1q/comment/fkrbdpi/?utm_source=share&amp;utm_medium=web2x&amp;context=3">this reddit comment</a> goes into more detail:</p>
<ul>
<li aria-level="1">One of the top comments explained that SFML is “More beginner friendly”, and “Has everything you need to make a simple 2D game.” (Giacomand, 2020)</li>
<ul>
<li aria-level="2">Additionally, I have the book titled ‘SFML Game Development By Example’ (Pupius, 2015), and I’m enjoying studying from this book.</li>
</ul>
<li aria-level="1">Whereas SDL is “not beginner friendly” and “is used widely in the industry” (Giacomand, 2020)</li>
<ul>
<li aria-level="2">On the official SDL website, there is a list of professional games produced with SDL, it’s well known in the industry, and <a href="https://github.com/Unity-Technologies/SDL">also used for engines like Unity</a> (See figure 2) So, it still is a graphics library that I really would like to learn more about.</li>
</ul>
</ul>

<img class="center-img3" src="https://am3pap005files.storage.live.com/y4mN1R19LjOvN7WLzsRJze8kzrr94SpjeC9lVVXX2IZ_b5BTB2yi8gen7hzajjKsAoWd0mQRg32E89pgVc-OVXEBVu59yQ7aEdYQT27QfmmdFTvHmMKdWOQE1U-EbSLowOObpoKUN79kDiXmyhZ3zEw24lI6zn_52E-u5vJsj8WnI7WOkkZzz1j--dcDx2exNkc?width=636&height=340&cropmode=none">
<p style="text-align:center"><small>Figure 2: SDL in the Unity Git Repository</small></p>

<p>Looking at my goals, I just want to focus on improving my C++ skill and confidence, so if I were to pick SDL, I would be going too low-level, unnecessarily so.</p>
<p>I will of course be playing around with both libraries, as they both interest me, but my focus for this project will be on SFML.</p>
<p>I decided it would also be a good idea to ask my mentor Kerry and my friend Ashley about their opinions on this.</p>
<ul>
<li aria-level="1">I chatted with my programming mentor, Kerry Turner about what she thinks. Kerry is a senior audio programmer at Rev Rooms (<em>Rev Rooms</em>, n.d.).<br />She mentioned that <em>“SFML is perfect for me as it's the middle ground of RayLib (Too simple, lots of bells and whistles) and SDL (Too low level, I'd be too bogged down doing graphics programming instead of just C++)”</em> (K. Turner, personal communication, 2022).</li>
<li aria-level="1">I asked the same question to Ashley, and she said pretty much the same thing as Kerry, but she also mentioned that <em>“SDL doesn’t handle graphics too well, so it would be much better for my purpose of just learning C++ to use SFML”</em> (A. Smith, personal communication, 2022c).</li>
</ul>
<h5>Inspiration</h5>
<p>I’ve been really inspired by the colour schemes in <a href="https://dinopoloclub.com/">Dinosaur Polo Club</a>’s (<em>Dinosaur Polo Club</em>, 2013) games <a href="https://dinopoloclub.com/games/mini-metro/">Mini Metro</a> (Dinosaur Polo Club, 2014) and <a href="https://dinopoloclub.com/games/mini-motorways/">Mini Motorways</a> (Dinosaur Polo Club, 2019), I will be designing my games with their artstyle as a main inspiration.</p>

<img class="center-img3" src="https://am3pap005files.storage.live.com/y4mRtheKTnYWvrP5XbFDbxEJaXt0nB7Hm07FrBI4CVcmWF96LrTNg_j8A-nR1etZv4FPujsqjCo2r9KJPxbNF9KJcc-A6fXdBt_NnFtyohWeCR3M0A0scpm0XDJAXkeoPRjNeXioxaK55TIYW7Vn9jgYrGs9pJxbptsMlk4BTi2nRumqM5P1yFc-nfBMFSXk3Sl?width=479&height=270&cropmode=none">
<p style="text-align:center"><small>Figure 3: Mini Metro Screenshot</small></p>

<p>In the end, have chosen to use the SFML graphics library to make a 2d board game based on Gobblets Gobblers because this project would be the best project to reach my goals.</p>

<h2>Appraisal of API in Application to Project &amp; Problem Solving</h2>
<h3>Was the chosen API appropriate in practice?</h3>
<p>Beginning my work was the complicated part. There was quite a bit of setup involved.</p>
<h4>Critique of CMake</h4>
<p>I’ve worked with libraries before, so I knew how I can get SFML set up for development, but I wanted to go the extra mile and get this project working with CMake (Kitware, 2000), so I can control the games’ compilation process, and it also means that there is only <em>“one configuration that works for many environments.”</em> (leinaD_natipaC, 2014) - Making things easier in the long run.</p>
<p>One of the reasons I decided to use CMake is because it’s relevant in the Games Industry, as demonstrated here on this <a href="https://jobs.lever.co/jagex/610008ec-0d58-4890-9dd2-a73e9a85581b">Senior Games Systems Engineer role</a> advertised (<em>Jagex - Senior Game Systems Engineer</em>, 2022) (See figure 4) - And if you search ‘CMake’ in the <a href="https://github.com/EpicGames/UnrealEngine">Unreal Engine git repository</a> (Epic Games, 2022), you also get a bunch of CMake-relevant files! (See figure 5), I’ve seen first-hand variants of build tools used in a professional setting when I worked on Old School Runescape (Jagex, 2007), so, hopefully learning more about using CMake can help me when I apply to similar roles in the future.</p>

<img class="center-img3" src="https://am3pap005files.storage.live.com/y4mFDMrh85cOP11WAKcwGjwEUIGZhaPc3SxDDJm_QxcEoyqcKebSth-qIgGqbMokWpSCL86XSj_XAMtEVH904vvPOofMKBp_YYbbfAYmfz8yxuVa2bwGu124jhRIC_Np1fDXv3ZioLEOOwXEGJ1srEBXRw8Buf2g4YWOPpMmAKD5TYoJvWZa1TChxWFvClvZxX4?width=718&height=299&cropmode=none">
<p style="text-align:center"><small>Figure 4: Senior Systems Engineer Job Listing</small></p>

<img class="center-img3" src="https://am3pap005files.storage.live.com/y4m-VsCEdqf-hcWdQy_lFQrqi4Z2KZHII6msy19rWCCUJx_SPGVI3ZN78EsDIeJY3j5UUcJEvoHxMX-TlxZoBTvM-MHCKyHACLojFGdv1P4GmX73QIiE_mNTPGe-B2f-2xtcyJ993eK9HI2LwqLpoW4NqIOImZouK_FnibcxjJe8dJsKJ64mUre8qj8TCEB3GLr?width=718&height=360&cropmode=none">
<p style="text-align:center"><small>Figure 5: CMake files  in Unreal Engine</small></p>

<p>It took quite some time to learn about CMake, and get everything compiling with the SFML library linked up as there really isn’t too much documentation or forums on CMake.<br /></p>
<p>I used a template CMake build file and changed it to suit my project. I will probably keep using this same file over and over again if I were to use CMake with another project, as my friend Ashley stated: <em>“CMake is something that you write once and forget.”</em> (A. Smith, personal communication, 8 October 2022).</p>
<p>Setting up the CMake generation with the SFML project went smoothly though! It was mostly straightforward, as <a href="https://www.sfml-dev.org/tutorials/2.5/compile-with-cmake.php">SFML has a tutorial on how to compile SFML with CMake</a>! (SFML Team, 2015).</p>

<h4>Critique of SFML</h4>
<p>Using SFML in general was great fun, it reminded me of using PICO-8!<br />I was able to dive right into development, and my idea was I would start with a gamejam, so I can learn more about SFML first before diving into my final project - My focus for this was on SFML and <strong><em>not </em></strong>making clean code.</p>
<p>I decided to make a connect-4 game, and learnt a lot through that, like different parts of this code I can reuse, and refactor for my final project.<br />Through reading extracts from the SFML Game Development By Example book and using the <a href="https://en.sfml-dev.org/forums/index.php?topic=23925.0">SFML Official Discord</a> (eXpl0it3r, 2018) to ask questions when I came across issues, I eventually was able to make something that resembles a Connect-4 game (See figure 6) - <em>And this </em><a href="https://youtu.be/ISCLiW1C5sA"><em>YouTube Video</em></a> (Amy Elliott, 2022).</p>

<img class="center-img3" src="https://am3pap005files.storage.live.com/y4m66a9FATGCpx6_nvHliCAgdjbwT4_Nj91XPKWOQ_a46Z6NsD9BxTdCiM7zKczNKUUS6G8morEkbKvMm3iG9Z7IDrwJWEV1wN8XnhFnYkS2NTVV21wpYf6zCkpEx9BEDUUtCSE82yUWh8sUTnZ2Xjwst1ggHkZc1kFtrpk9gbjyd0ZP0HYj9ybsIV9Lhp5al_E?width=718&height=379&cropmode=none">
<p style="text-align:center"><small>Figure 6: Connect 4 Gamejam</small></p>

<p>From here, I decided to take the gamejam and strip it down into its core parts, making a template that I can use for each SFML game I make going forward.<br /></p>
<p>I called this library ‘Inception Engine’, and learnt about how to make it a template on GitHub, so I can use it as such, and through using this tutorial on the GitHub docs (<em>Creating a Template Repository</em>, 2022), I was able to do that (See figure 7).</p>

<img class="center-img3" src="https://am3pap005files.storage.live.com/y4moyH8WCXtAE3RABNhvsOsM0GfH0TpkcLF1P8_-Pl5ovsYZKXarBlQzBRKqI3gzLJGdmD_wph-WvDf2YpZz1pXBYZZDvQWuWSrc5LDVlT37ZODR7XCH_QqTQmUBBXR0VjIVT1A7fdtGN4Lvze__21bVZZehQGtkYs9Zqz_j23yhLoms5ItEHIe5EvXbS-xPr4M?width=718&height=192&cropmode=none">
<p style="text-align:center"><small>Figure 7: Game Engine Library Template in GitHub</small></p>

<p>When it came to making the final project, I was unfortunately not able to complete it within time, I had spent too much time on the Connect-4 gamejam, Inception Engine, and spent too much time making a start on the Gobblet Gobblers game, optimising and cleaning up my code as much as possible.</p>

<h4>Critique of finished products</h4>
<p>I am quite happy with what I have, even though it’s not a complete Gobblet Gobblers game, but I was able to produce:</p>
<ul>
<li aria-level="1">A Connect-4 Gamejam Game, teaching me essential SFML skills.</li>
<li aria-level="1">A game engine library, a template I can keep reusing and improving.</li>
<li aria-level="1">A strong start to the Gobblet Gobblers project.</li>
</ul>
<p>I am happy with what I’ve got at this point with the Gobblet Gobblers game, as the code I have written is <strong>very optimised</strong>, and <strong>clean</strong>, which is contrary to the Connect 4 game, which had messy unoptimized code, due to it being a gamejam.</p>
<p>In my proposal, I stated I wanted to get more confident with C++, and writing clean code helps me reach that goal, as it allows me to explore the language!</p>
<p>The clean, and optimised code took me a while to write, whereas if I took the same approach to the project as I did with the connect 4 game, I’d have messy code which would be difficult to expand upon, and not have learnt as much, this is an important point which is made within the Clean Code book (C. Martin, 2008), I could take hundreds of quotes from this and them to be relevant here, but the ones that sticks out are <em>“The clearer the author can make the code, the less time others will have to spend understanding it. This will reduce defects and shrink the cost of maintenance.”</em> and <em>“the ratio of time spent reading versus writing is well over 10 to 1. We are constantly reading old code as part of the effort to write new code. ...[Therefore,] making it easy to read makes it easier to write.”</em> (C. Martin, 2008) - Clean code is really important, so when starting this project, that was my goal.</p>

<h4>Did you encounter any problems?</h4>
<p>I’ve not encountered too many problems that I thought were worth writing about, I’ve gotten used to doing lots of problem-solving, and fixing errors and bugs quickly without a second thought, so below are issues that have stuck out to me.</p>
<h5>CMake Issues</h5>
<p>I decided to practice how CMake works, so I could get more confident using it, as it was an important skillset to have if I wanted to become a Senior Software Engineer one day, and one of the main problems I had was that I got this error (See figure 8) when trying to generate project files for an SDL test project:</p>

{% highlight txt %}
Module path: C:/Users/amyel/Documents/_University/Year2/PRAPI/SDL_Project/cmake-modules/
CMake Error at CMakeLists.txt:17 (find_package):
  By not providing "FindSDL2.cmake" in CMAKE_MODULE_PATH this project has
  asked CMake to find a package configuration file provided by "SDL2", but
  CMake did not find one.

  Could not find a package configuration file provided by "SDL2" with any of
  the following names:

    SDL2Config.cmake
    sdl2-config.cmake

  Add the installation prefix of "SDL2" to CMAKE_PREFIX_PATH or set
  "SDL2_DIR" to a directory containing one of the above files.  If "SDL2"
  provides a separate development package or SDK, be sure it has been
  installed.
{% endhighlight %}

<img class="center-img3" src="https://am3pap005files.storage.live.com/y4ms0ah7JogKSKIop0cetub91lcRJXcIwI_wNyB50DyjSJ5KbKzO6xd-THu_vTSA-wDiJuxv55YGD8TKzT0kzPu_NEhcy6HHoW1AI4qst2mUKqqNyK5yz_RPYf7qEKP-f05Ga4b0wT8z761EFqcZKwzKSlVk2FkzWFhM6XKgRNx2GAMg2j_FKoj6qznzSqwMPv2?width=718&height=431&cropmode=none">
<p style="text-align:center"><small>Figure 8: CMake errors</small></p>

<p>I used the same setup as I had used with SFML, so I wasn’t sure why it wasn’t working for SDL.<br />I spent a while googling, everything was set up how it was supposed to be.</p>
<p>Renaming the SDL2Config.cmake file so it can be used generated a different error (See figure 9):</p>

<img class="center-img3" src="https://am3pap005files.storage.live.com/y4mHCzXsXrUz1OP6i94iDw2ir_3q0qMVzTAkS9QHYvgUNAeFnZCkKeP6_eJBWa_cf33q8nNEbX993gr3rpynb6Pwc-zI9MHab8QkQceKBaPoHmbZHTDss1m3-_MKYyLnteqvry3T1z9ijfvi3kZFDNruRj4YWuxmWibmRnRRTe6VjN-nJ3WGOs2fmkP9L_Ikxn7?width=711&height=297&cropmode=none">
<p style="text-align:center"><small>Figure 9: CMake errors (2)</small></p>

<p>I was talking to my friend to ask if she had any ideas, and she made a few suggestions, but in the end, this was a rabbit hole, and it was wasting too much time fixing at this point, so I didn't resolve it at the time.</p>
<p>When looking back at this issue, I found a few forum posts where people have had similar issues, and a solution that I propose is that it could be the CMAKE file itself, something written in there incorrectly, specifically something to do with packages, I think line 17 isn’t written correctly, I thought of this because this forum titled <a href="https://discourse.cmake.org/t/how-to-solve-this-parse-error/4890/2">‘How to Solve this Parse error’</a> mentions <em>“You cannot use Makefile syntax in CMake.”</em> (Boeckel, 2022) - To debug, I would change this line, if this is unsuccessful, I’d look at another CMakeLists.txt file specifically for SDL to see how that's written. Unfortunately, I don’t have the time to test this for submission.</p>

<h5>SFML Issues</h5>
<p>When initially setting up the project, I had a small, and really silly mistake when linking SFML!</p>
<p>I downloaded the wrong SFML library (A source library), which lead to issues when setting up the project with CMake.</p>
<p>I fixed this by going to the SFML website and downloading another version of the library, thinking I just had a fault with mine, but then noticing the contents of the files looked different, upon trying out the new version, all the problems fixed themselves.</p>
<h5>General Issues</h5>
<p>Had I not made the Connect-4 Gamejam game, or the Inception Engine library, I may have made more progress with the Gobblet project, but I feel it would’ve been much more complicated, as I wouldn’t have the confidence of using SFML from the gamejam, or a template to work on top of.</p>

<p>Additionally, I feel throughout this project, I could’ve managed my time better.<br />At first, I worked well, I had a milestone plan for the project, as well as sprints, and that went well for a few weeks, but nearing the end of the module, I began feeling burnt out and was producing work of a lower quality than my standards.<br />To combat this, I booked time off work closer to submission and brought a few self-help books to put me in the right mindset for work, these books titled: Hyperfocus (Bailey, 2018) and Deep Work (Newport, 2016). This helped me, but it was all quite last minute, had I noticed my burnout a bit sooner, I may have been able to produce more work.</p>
<h5>C++ Issues</h5>
<p>To become more confident with programming in C++, I need to make sure I’m constantly getting feedback from myself and my peers on my work.<br /><br /></p>
<p>An example of this happening during development is during my first code review for Connect 4 when I implemented a destructor as soon as I read up about it, and when I looked at my code a few days later, I was confused. (See figure 10) I then had to look up what it meant again, but the whole process of learning, forgetting, and then learning again helped me solidify that knowledge.</p>

<img class="center-img3" src="https://am3pap005files.storage.live.com/y4mf8RgNfTUMveR0izSooHasVu1BhFZEQQeapbPSsE4rZYsXtWcm348GSip8itvmnz1vUegdmLHSWq8C4isEKJG5j73PRbF-GUCizgeP17xB9r3B6jDQi2XgFHvvDDasN_ntMyCg9_AUXFKfZjX5M9deNW_yNbZuNGC2im7ekGGc-vF18kcb38wc6KFnk_0h0NU?width=621&height=274&cropmode=none">
<p style="text-align:center"><small>Figure 10: Self-Code-Review</small></p>

<p>During my final code review, Ashley mentioned that I used a lot of ‘summaries’ everywhere (XML Comments) when documenting my code (See figure 11). <br />We talked about how I shouldn’t have to use these, and I would do just fine using the normal comments.<br />I didn’t know ‘Why’ until I looked further, and found out that XML Comments are used to <em>“build API documentation which is readable by external tools.”</em> (TypeIA, 2014) - This is useful to know for future projects.</p>

<img class="center-img3" src="https://am3pap005files.storage.live.com/y4mVBbN890X7QNHBuUPzrVmFc6kwhnRScOF8GsB6Du2e6EkdDnA7whMgv_ekx8MoUIZabS3OMhiH2eWYDyyIiIDRNCNGIjOZV3bKRchCo8hhBfbk_pKhStmgO3o61F-WUtrbfcu8S80T2upCYwvmHXTPr8qp7kjXtA-1wvPKN9L7XkQwAXKvXW-j5ZAlX7bCABq?width=718&height=343&cropmode=none">
<p style="text-align:center"><small>Figure 11: XML Comments vs Normal Comments</small></p>

<p>Ashley gave me a lot of useful tips on documenting my code, for example, in some places, I have some very redundant comments, and I should really spend some more time looking at other people's documentation on their code, to learn some better practices to bring into my own code.</p>

<h2>Reflection on Collaboration and Communication</h2>
<h3>How did you collaborate with others?</h3>
<h4>Rubber Ducking</h4>
<p>In general, a lot of my problems are solved by looking over my code, reading it aloud, and talking my problems through to my fish, and that makes me sound crazy, but sometimes, I have a lightbulb moment, where I figure out a solution because I’ve explained it aloud.</p>
<p>This doesn’t work all the time though, and the approaches mentioned below have been additional help, finding help by collaborating with other people.</p>
<h4>Workshop Collaboration</h4>
<p>During the workshops, we had standups every week, where we talked about our progress, any issues we have, and our plans for the coming weeks.<br />During these standups, I learnt about other people's projects, and I was able to help a few people with issues they have had, like:</p>
<ul>
<li aria-level="1">I helped a classmate make a variable public and editable in Unreal Engine’s inspector.</li>
<li aria-level="1">I helped another classmate that was making a dungeon crawler get in contact with a friend of mine who had made something similar in the past.</li>
</ul>
<p>These standups also helped me figure out whether I was on pace with my own project.<br />Unfortunately, it didn’t really help past that, because the majority of my peers in the workshop were working on Unreal projects, meaning it was harder for me to collaborate with them.</p>
<h4>Discord Collaboration</h4>
<p>I used the SFML official discord quite frequently when I needed help finding documentation, or figuring out how to implement certain functionality.<br />The community is very active and has been a great help, it has also been a great way to network with other users of SFML.</p>
<p>An example of where Discord was useful was when I had an issue with my events, generating an error, and through chatting with a member on discord, I realised that I accidentally included something I shouldn’t have. </p>
<h4>Code Reviews</h4>
<p>I wanted to have good code reviews for this project, because my goal was to improve my C++.</p>
<p>Throughout my jobs in the industry, I’ve done many code reviews, and have had my own code reviewed, and it really has helped me improve my own coding skills over the years.<br />As I want to improve my confidence in C++, code reviews are the best way I can do that as well, as a good skill in the industry is to take constructive criticism on your own work.</p>
<p>When I completed my Connect-4 SFML project, I asked Ashley if she could give me a code review, and from that code review, I learnt a lot and reflected upon that within the Connect-4, whilst also taking some of those comments into consideration on Inception Engine and Gobblet Gobblers.</p>
<p>I even gave myself a code review, adding comments on things I've missed, and also things to learn more about, and reflect on. </p>
<p>Unfortunately, I can’t contain the entire code review here as there is too much to talk about, but here are some important points which I took away from my first code review:</p>
<ul>
<li aria-level="1"><em>“Take a look at the return type of loadFromFile - it actually returns a bool. One challenge you'll have to handle going forward is error handling - what should happen if the loading for the file actually fails? There's no right answer for this, but simply wrapping your initialisation logic with an if statement and logging errors is a good starting point.”</em> (A. Smith, personal communication, 6 November 2022)</li>
<ul>
<li aria-level="2">From this feedback, I made sure I ran checks, and logged errors each time I ran loadFromFile, or any function that acts similarly.</li>
</ul>
<li aria-level="1">“Try to use const wherever possible - sf::Vector2u size` can be const.” (A. Smith, personal communication, 9 November 2022a)</li>
<ul>
<li aria-level="2">As you may see throughout the rest of the projects, I ended up using more constants, as I realized many places which can use them</li>
</ul>
<li aria-level="1">I shouldn’t have used Inline, and the reason why I had to use it was because I was including a .cpp file which I shouldn’t have. When removing that, I didn’t need to use inline anymore (A. Smith, personal communication, 9 November 2022b)</li>
</ul>
<p>Taking all my code review feedback, I reflected upon it on my Connect 4 game.<br />I asked Ashley for another code review once I had made my final changes to Gobblet Gobblers.</p>
<p>Again, there was a lot to reflect on, unfortunately, I didn’t have time to make all the changes she mentioned in the <a href="https://github.com/AmyE123/Gobblet-Gobblers/pull/4">code review</a> though, but this is all still very useful, as reading through her reviews made me realise many more ways I can improve and get stronger with C++</p>
<ul>
<li aria-level="1">Some of my documentation is redundant, I shouldn’t have to use summary documentation for everything, and a single comment should be fine.</li>
<li aria-level="1">If something is private, that doesn’t mean it <em>doesn’t </em>need a comment.</li>
<li aria-level="1">Good use of ++i instead of i++ (pre-increment instead of post)</li>
<li aria-level="1">Using #ifndef in one area, and #pragma once in other areas! Stay consistent.</li>
</ul>
<p>Reflecting, and reading all of the comments left in the code review (You can see the full review <a href="https://github.com/AmyE123/Gobblet-Gobblers/pull/4">here</a>), and chatting with Ashely on a call about my code helped me learn about some of the best practices in C++, and I definitely feel much more confident with the language now.</p>
<p>I also have been able to demonstrate that I can adapt quickly, through learning about CMake and SFML in a short amount of time.</p>

<details>
    <summary>Bibliography</summary>
    <p><a href="https://discourse.cmake.org/t/how-to-solve-this-parse-error/4890/2">Ben Boeckel (2022, January 24). How to Solve this Parse error ??. https://discourse.cmake.org/t/how-to-solve-this-parse-error/4890/2</a></p>
    <p><a href="https://www.youtube.com/watch?v=ISCLiW1C5sA">Amy Elliott (Director). (2022, December 13). <em>Connect 4 SFML Gamejam</em>. https://www.youtube.com/watch?v=ISCLiW1C5sA</a></p>
    <p>Bailey, C. (2018). <em>Hyperfocus</em>.</p>
    <p>Martin, R. (2008). <em>Clean Code</em>.</p>
    <p><em>Club Penguin</em>. (2005).</p>
    <p><a href=" https://ghdocs-prod.azurewebsites.net/en/repositories/creating-and-managing-repositories/creating-a-template-repository"><em>Creating a template repository</em>. (2022). GitHub Docs. https://ghdocs-prod.azurewebsites.net/en/repositories/creating-and-managing-repositories/creating-a-template-repository</a></p>
    <p><a href="https://boardgamegeek.com/boardgame/13230/gobblet-gobblers">Denoual, T. (2003). <em>Gobblet Gobblers</em>. BoardGameGeek. https://boardgamegeek.com/boardgame/13230/gobblet-gobblers</a></p>
    <p><a href="https://dinopoloclub.com/"><em>Dinosaur Polo Club</em>. (2013, May 1). https://dinopoloclub.com/</a></p>
    <p><a href="https://dinopoloclub.com/games/mini-metro/">Dinosaur Polo Club. (2014). <em>Mini Metro</em>. https://dinopoloclub.com/games/mini-metro/</a></p>
    <p><a href="https://dinopoloclub.com/games/mini-motorways/">Dinosaur Polo Club. (2019). <em>Mini Motorways</em>. https://dinopoloclub.com/games/mini-motorways/</a></p>
    <p><a href="https://www.sumo-digital.com/">Dunn, G., &amp; Woods, J. (2003). <em>Sumo Digital</em>. https://www.sumo-digital.com/</a></p>
    <p><a href="https://amy-elliott.itch.io/blockyroads">Elliott, A. (2020). <em>Blocky Road</em>. https://amy-elliott.itch.io/blockyroads</a></p>
    <p><a href="https://github.com/EpicGames/UnrealEngine">Epic Games. (2022). <em>EpicGames/UnrealEngine: Unreal Engine source code</em>. https://github.com/EpicGames/UnrealEngine</a></p>
    <p><a href="https://en.sfml-dev.org/forums/index.php?topic=23925.0">eXpl0it3r. (2018, April 19). <em>Discord server</em>. https://en.sfml-dev.org/forums/index.php?topic=23925.0</a></p>
    <p><a href="https://www.alteredgene.co.uk">Gayle, D. (2013, September 14). <em>Altered Gene</em>. Altered Gene. https://www.alteredgene.co.uk</a></p>
    <p><a href="https://www.reddit.com/r/gamedev/comments/fk8c1q/sfml_vs_sdl_in_2020/fkrbdpi/">Giacomand. (2020, March 17). <em>SFML * More beginne…</em> [Reddit Comment]. R/Gamedev. www.reddit.com/r/gamedev/comments/fk8c1q/sfml_vs_sdl_in_2020/fkrbdpi/</a></p>
    <p><a href="https://www.sfml-dev.org/">Gomila, L. &amp; SFML Team. (2007). <em>SFML</em>. https://www.sfml-dev.org/</a></p>
    <p><a href="https://www.jagex.com/en-GB/">Gower, A., &amp; Gower, P. (2000, April 28). <em>Jagex</em>. https://www.jagex.com/en-GB/</a></p>
    <p><a href="https://oldschool.runescape.com/">Jagex. (2007). <em>Old School Runescape</em>. Jagex. https://oldschool.runescape.com/</a></p>
    <p><a href="https://jobs.lever.co/jagex/610008ec-0d58-4890-9dd2-a73e9a85581b"><em>Jagex—Senior Game Systems Engineer</em>. (2022). https://jobs.lever.co/jagex/610008ec-0d58-4890-9dd2-a73e9a85581b</a></p>
    <p><a href="https://cmake.org/">Kitware. (2000). <em>CMake</em>. https://cmake.org/</a></p>
    <p><a href="https://www.libsdl.org/">Lantinga, S. &amp; Valve Corporation. (1998). <em>SDL</em>. https://www.libsdl.org/</a></p>
    <p><a href="https://stackoverflow.com/a/26007567">leinaD_natipaC. (2014, September 24). <em>Answer to ‘How is CMake used?’</em> Stack Overflow. https://stackoverflow.com/a/26007567</a></p>
    <p><a href="https://godotengine.org/">Linietsky, J., &amp; Manzur, A. (2014). <em>Godot</em>. https://godotengine.org/</a></p>
    <p>Newport, C. (2016). <em>Deep Work</em>.</p>
    <p><a href="https://www.youtube.com/watch?v=EAMHQfCGymg">PolyMars (Director). (2020, July 20). <em>Learning SDL2 in 48 Hours—GMTK Game Jam 2020</em>. https://www.youtube.com/watch?v=EAMHQfCGymg</a></p>
    <p><a href="https://www.youtube.com/watch?v=iEn0ozP-jxc">PolyMars (Director). (2021, August 2). <em>Making a Game With C++ and SDL2</em>. https://www.youtube.com/watch?v=iEn0ozP-jxc</a></p>
    <p>Pupius, R. (2015). <em>SFML Game Development By Example</em>.</p>
    <p><a href="https://www.revrooms.co.uk"><em>Rev Rooms</em>. (n.d.). Rev Rooms. Retrieved 13 December 2022, from https://www.revrooms.co.uk</a></p>
    <p><a href="https://www.raylib.com/">Santamaria, R. &amp; Contributors. (2013). <em>RayLib</em>. https://www.raylib.com/</a></p>
    <p><a href="https://www.sfml-dev.org/tutorials/2.5/compile-with-cmake.php?fbclid=IwAR1PyaLU7GEk45bHvcXmam22Vuik3fhCv0HXf0chHzVSb1OMpcp1td74lZM">SFML Team. (2015). <em>Compiling SFML with CMake (SFML / Learn / 2.5 Tutorials)</em>. https://www.sfml-dev.org/tutorials/2.5/compile-with-cmake.php?fbclid=IwAR1PyaLU7GEk45bHvcXmam22Vuik3fhCv0HXf0chHzVSb1OMpcp1td74lZM</a></p>
    <p>Smith, A. (2022a). <em>It will include all of the bells and whistles which would make things much too easy for this project, and I wouldn’t be challenging myself enough</em> [Personal Communication].</p>
    <p>Smith, A. (2022b). <em>None of them are better than the others, and they can all achieve the same things, but they do have their differences</em> [Personal Communication].</p>
    <p>Smith, A. (2022c). <em>SDL doesn’t handle graphics too well, so it would be much better for my purpose of just learning C++ to use SFML</em> [Personal Communication].</p>
    <p>Smith, A. (2022, October 8). <em>No one understand cmake fully, we just use it. Cmake is something that you write once and forget, since its only done at the start of the project. Everyone just goes online and rips something and adapts it, never start from scratch</em> [Personal communication].</p>
    <p>Smith, A. (2022, November 6). <em>Ashley Code Review: LoadFromFile</em> [Code Review].</p>
    <p>Smith, A. (2022a, November 9). <em>Ashley Code Review: Consts</em> [Code Review].</p>
    <p>Smith, A. (2022b, November 9). <em>Ashley Code Review: Inline</em> [Personal communication].</p>
    <p>Stroustrup, B. (1985). <em>C++</em>.</p>
    <p><a href="https://boardgamegeek.com/boardgame/11901/tic-tac-toe"><em>Tic-Tac-Toe</em>. (n.d.). BoardGameGeek. Retrieved 13 December 2022, from https://boardgamegeek.com/boardgame/11901/tic-tac-toe</a></p>
    <p>Turner, K. (2022). <em>SFML is perfect for me as it’s the middle ground of RayLib (Too simple, lots of bells and whistles) and SDL (Too low level, I’d be too bogged down doing graphics programming instead of just C++)</em> [Personal Communication].</p>
    <p><a href="https://stackoverflow.com/a/21728516">TypeIA. (2014, February 12). <em>Answer to ‘What is the use of XML comments in C#’</em>. Stack Overflow. https://stackoverflow.com/a/21728516</a></p>
    <p><a href="https://www.unrealengine.com"><em>Unreal Engine</em>. (2019). Epic Games. https://www.unrealengine.com</a></p>
    <p><a href="https://www.youtube.com/c/PolyMars">Wismar, J. (2017, December 22). <em>PolyMars</em>. YouTube. https://www.youtube.com/c/PolyMars</a></p>
</details>