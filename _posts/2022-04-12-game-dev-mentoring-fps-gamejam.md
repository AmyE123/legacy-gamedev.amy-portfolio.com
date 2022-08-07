---
layout: post
title:  "Game Dev Mentoring - Making FPS Gamejams"
type: "Mentoring Blog"
color: "background-color: #c36114"
summary: "After working on his prophunt game for a while, Thomas wanted to try out different game ideas, and so I helped him with making some of his own FPS Gamejam Games inspired by some games he enjoyed playing!"
author: amyelliott
date: '2022-04-12'
category: ['mentoring', 'teaching']
thumbnail: /assets/img/posts/GameDevMentoring/FpsGamejams/cover.png
keywords: mentoring, education, teaching, reflection, development, improvement
permalink: /blog/game-dev-mentoring/fps-gamejam
usemathjax: true
---
<img class="image-heading" src="/assets/img/posts/GameDevMentoring/FpsGamejams/1.png">
<p>This blog is part of a blog series where I talked about my Game Development Mentoring sessions! You can see all the different blogs in that series by clicking <a href="/blog/categories/mentoring" style="padding: 0px" target="_blank">here</a>.</p>
<p>As mentioned in the <a href="/blog/game-dev-mentoring/greyboxing-design" style="padding: 0px" target="_blank">previous blog post</a>, Thomas wanted to try out other game ideas, as the prop hunt game was a big project, and he wanted a change of pace.</p>
<p>So we can quickly and iteratively try out lots of different game ideas, I proposed the idea of doing 3-hour gamejams with him! Thomas hasn&rsquo;t done a gamejam, and our sessions are an hour and a half each, so the plan was to spend 2 sessions on each game.</p>
<p>I asked which types of games he wanted to make, and he mentioned 2 shooter games that he really enjoyed playing!</p>
<p>In this blog, I will talk about the gamejams that Thomas worked on in my sessions, and what he has learned and produced, as well as how I think these sessions would benefit him more than the long-term prop hunt project we began with.</p>
<hr>

<img class="image-heading" src="/assets/img/posts/GameDevMentoring/FpsGamejams/screenshot.png" style="height: 200px !important">
<h3 style="text-align:center; margin-top: 20px; margin-bottom: 20px">Gamejam #1: Gun Ninja</h3>
<h4 style="margin-top: 20px; margin-bottom: 20px">Artwork Session</h4>
<p>Gun Ninja was the first Gamejam game that Thomas wanted to work on, before the session began, he told me that he wanted to work on a 2D dungeon shooter, similar to a game he really enjoyed called <a href="https://stepford.itch.io/gun-knight" style="padding: 0px" target="_blank">Gun Knight</a>, so we spent some time playing the game, and chatting about what parts of the game he enjoyed, writing that down so we can refer to it later.</p>
<p>In the first session, I decided it would be a good idea to focus just on the 2d pixel art, that way, we can spend half the gamejam on art, and the other half on Unity.</p>
<p>I wrote down a list of things which he can make pixel art for, and then made a page of reference for him to use if he gets stuck with how to make pixel art.</p>
<img src="/assets/img/posts/GameDevMentoring/FpsGamejams/sprites.png" class="center-img2">
<h4 style="margin-top: 20px; margin-bottom: 20px">Unity Session</h4>
<p>For the next session, I found a <a href="https://github.com/tarush-r/Top-Down-Shooter-Game" style="padding: 0px" target="_blank">template project of a 2d Dungeon Shooter</a> which Thomas can use which was made by Tarush Rajput. I took this and put his sprite assets into the game and sent Thomas over a download of the files before the session.</p>
<p>In the session, I asked Thomas to list out a few things he wanted to change about the gameplay, and so we went through those things and changed them, and doing this helped him learn about how to adjust properties within Unity.</p>
<p>A few of the things that Thomas changed during this session were the colour of sprites, adding enemy sprites, enemy firing rate, level design, and UI placement.</p>
<div style="text-align: center;"> <iframe frameborder="0" src="https://itch.io/embed/1441718?border_width=0&amp;bg_color=1c1c1e&amp;fg_color=8b8b8b&amp;link_color=FF7901" width="80%" height="165"><a href="https://thomase1.itch.io/gun-ninja">Gun Ninja by ThomasE1</a></iframe> </div>

<hr>

<img class="image-heading" src="/assets/img/posts/GameDevMentoring/FpsGamejams/screenshot3.png" style="height: 200px !important">
<h3 style="text-align:center; margin-top: 20px; margin-bottom: 20px">Gamejam #2: Purple Gun Game</h3>
<h4 style="margin-top: 20px; margin-bottom: 20px">Map Design Session</h4>
<p>For his second Gamejam, Thomas told me he wanted to make a 3D shooter, similar to <a href="https://store.steampowered.com/app/1229490/ULTRAKILL/" style="padding: 0px" target="_blank">ULTRAKILL </a>- So, I found a <a href="https://assetstore.unity.com/packages/templates/systems/low-poly-shooter-pack-free-sample-144839" style="padding: 0px" target="_blank">3d shooter asset</a> on the Unity asset store, and put together a scene that Thomas can work in, I also imported his city greybox from the Roblox prop hunt session so we can work around using that.</p>
<p>During this session, Thomas worked on putting down <a href="https://assetstore.unity.com/packages/3d/environments/urban/simple-city-pack-plain-100348#publisher" style="padding: 0px" target="_blank">building assets</a> where the greyboxes of the buildings were and putting down city props in places where he thinks they look nice. As well as this, he decided to put in a few easter eggs, like some crates flying in the air like birds for the fun of it! Thomas also placed down a few enemy props, but these weren&rsquo;t in final locations yet as the focus for this session was just to make the city look like a fun map to play in</p>
<img src="/assets/img/posts/GameDevMentoring/FpsGamejams/screenshot5.png" class="center-img2">
<h4 style="margin-top: 20px; margin-bottom: 20px">Unity & Art Session</h4>
<p>For this session, we were going to focus more on mechanics and gameplay.</p>
<p>Before this session, I put together a gameplay loop in the game. The player has to shoot down the enemy props within a timer.</p>
<p>In comparison to changing random things that Thomas spotted as we did for Gun Ninja, I decided to write down some challenges and add some fake bugs in the game which Thomas can learn to fix!</p>
<p>One of the first things which we worked on was more art-focused, but it also allowed Thomas to learn about how materials work in Unity as well as the difference between materials and textures and how they work together. The task was to make and replace the material and its texture on the main gun in the game.</p>
<p>It was originally an orange/white texture, and Thomas&rsquo;s favorite colour is purple, so we put together a purple camouflage texture and put that into Unity and on the Gun.</p>
<p>The next challenge was to do with fixing the UI, as I had purposely made it so the win screen appears when the player loses the game, this involved looking around in the hierarchy for the win UI, and then finding the script which this win screen is activated, Thomas found where this was and was able to fix it so the lose screen activates when the player loses!</p>
<p>Another thing I added into the game for Thomas to fix was the gameplay timer. I made it so the player only had 10 seconds to shoot down all the enemies, which was far too short! He was able to adjust this to an appropriate time by adjusting the time parameter on the Gameplay Manager.</p>
<p>Similar to this, I made it so the intro camera that is in the main menu screen is spinning around the map far too quickly, this was another parameter that was on the camera which Thomas adjusted to be a better speed.</p>
<p>Outside of adjusting gameplay parameters, another thing that was adjusted was the enemy positions, as some of them were in places inside of walls, and places that can&rsquo;t be reached.</p>
<p>And to finish off the game, Thomas worked on an icon,&nbsp;and I taught him how to build a windows version of the game!</p>
<div style="text-align: center;"> <iframe frameborder="0" src="https://itch.io/embed/1459943?border_width=0&amp;bg_color=1c1c1e&amp;fg_color=8b8b8b&amp;link_color=FF7901" width="80%" height="165"><a href="https://thomase1.itch.io/test-purple-gun-game">Test Purple Gun Game by ThomasE1</a></iframe> </div>
<hr>

<img class="image-heading" src="/assets/img/posts/GameDevMentoring/FpsGamejams/conclusion.png" style="height: 200px !important">
<h3 style="text-align:center; margin-top: 20px; margin-bottom: 20px">Conclusion</h3>
<p>I think this gamejam approach to Thomas&rsquo;s sessions really helps him learn a lot quicker, and try out different game ideas, as he had lots of things he wanted to try out! I&rsquo;m really happy with the work he has produced, and when chatting to him about this, he really likes the gamejam approach to these sessions, so in the future, we will be trying out gamejams in Roblox, as that is what he wants to use more of!</p>
