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

<img src="/assets/img/posts/YearTDEMO/cover.png" style="width: 100%">

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
                    TITLE HERE
                </a>
                </h4>
            </div>
            <div id="collapseOverview" class="panel-collapse collapse in collapse show" role="tabpanel" aria-labelledby="headingOne" style="margin-left: 50px">
                <div class="panel-body">
                    <p>TEXT HERE</p>
                </div>
            </div>
        </div>
    </div>
</div>

<hr>

<!--- -------------------------------------------------------- -->
<!--- This is another style of a collapsible which I could use -->
<!--- -------------------------------------------------------- -->

<details> 
    <summary>Some Words</summary> 
    some text here
</details>



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

