---
layout: post
title:  "Linked Lists & Dictionaries C++ Studies"
type: "Study Blog"
color: "background-color: darkslateblue"
summary: "I needed to understand more about how Linked Lists, Dictionaries work to get a better understanding of the different data structures."
author: amyelliott
date: '2021-04-13'
category: ['study', 'self-directed', 'programming']
thumbnail: /assets/img/posts/BlockyRoadUnreal/cover.png
keywords: cplusplus, self-directed-study
permalink: /blog/linked-list-dictionary-study/
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

    <h6 style="text-align: center;">Project Type <a style="text-align: center;">Study</a> </h6>      

    <h6 style="text-align: center;">Software Used <a style="text-align: center;">Internet Research</a> </h6>    
</div>

<!--- This HR is nice to have here, to seperate the status of the game -->
<hr>

<!--- -------------------------------------------------------------------- -->
<!--- This is for the main description of the game, this is very important -->
<!--- -------------------------------------------------------------------- -->
<div class = "card">
    <h2 style="text-align: center;">C++ Study</h2>
    <p style="text-align: center;">I needed to understand more about how Linked Lists, Dictionaries work to get a better understanding of the different data structures</p>
</div>

<hr>

<!--- -------------------------------------------------------- -->
<!--- This is the collapsible which I will be using.           -->
<!--- I will use these to write about what I done for the game -->
<!--- -------------------------------------------------------- -->

<h4>Dictionaries</h4>
<h6>DICTIONARIES – INTRODUCTION TO DATA STRUCTURES ((39) DICTIONARIES - INTRODUCTION TO DATA STRUCTURES (EPISODE 8) - YOUTUBE, N.D.): </h6>
<p>Dictionaries can also be called <b>Maps and Associative Arrays.</b> <br /> The <b>2 important restrictions</b> with using dictionaries is that: <br /> <li>Each key can only appear <b>once</b> within the dictionary. </li> <li> Each key can only have <b>one value.</b> </li> </p>
<br /> 
<h6>PROFESSIONAL C++ BY EXAMPLE, CHAPTER 15 (GREGOIRE, N.D.): </h6>
<p>The map header defines the map template which stores key/value pairs. These maps keep its elements in sorted order based on the key values. <br /> An example of using dictionaries is you might want to store the books in a map where the key is the ISBN number of the book and the value is a Book object containing detailed information for that specific book.</p>

<br />
<h4>Linked Lists</h4>
<h6>LINKED LISTS (COLVIN, N.D.): </h6>
<p>In Erin’s video, she describes a Linked List as a list of <b>structs or classes that include a pointer.</b> <br />The pointer <b>points to the next struct or class in its list as it gets added.</b> <br /> Unlike an array,  where you have to statically set the number of elements you need, a linked list can be linked dynamically which means your list can grow or shrink as needed. Erin inserts nodes into the list and runs a while loop, which checks <b>while it’s not equal to null (not at the end of the list) we print out the data in the node we are pointing to, and then move to the next node.</b></p>        
<br />
<h6>DATA STRUCTURES: LINKED LISTS (COMRADE CORA, 2016): </h6>
<p>A linked list, instead of an array, isn’t indexed, so if you want to get to a specific value in the list you have to go through the list starting from the head (the first in the list) until you reach what you want to <br /></p>
<p>The disadvantage of this is that <b>it’s slower</b> to get to the nth element as it linearly goes through the list, unlike arrays which would go directly to the inserted index. <br /></p>
<p>The advantage of using linked lists is that you can <b>insert and delete elements during runtime.</b><br /></p>
<p>There is a thing called a <b>Doubly Linked List</b>, which means <b>instead of having a link to the next element, each element also links to the previous element.</b><br /></p>
<p>If we want to <b>delete the first element of the list, we just need to set the head to the next value.</b><br /></p>
<p><i>This reminds me of some of the code I had to write for my pathfinding practice, I used adjacency lists for this to do BFS.</i><br /></p>

<br />

<h4><b>Bibliography / Sources Used To Study</b></h4>
<p><small>(39) Dictionaries—Introduction to Data Structures (Episode 8)—YouTube. (2020, June 24). https://www.youtube.com/watch?v=j0cPnbtp1_w&ab_channel=NullPointerException </small> <br /><p>
<p><small>Colvin, E. (n.d.). Linked Lists. Retrieved 13 April 2021, from https://www.linkedin.com/learning/learning-c-plus-plus-3/linked-lists </small><br /><p>
<p><small>Comrade Cora. (2016, September 27). Data Structures: Linked Lists. https://www.youtube.com/watch?v=njTh_OwMljA&ab_channel=HackerRank </small><br /><p>
<p><small>Gregoire, M. (n.d.). Overview of the C++ Standard Library. In Professional C++ (pp. 452–453). </small><br /><p>