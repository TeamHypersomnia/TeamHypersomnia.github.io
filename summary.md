---
layout: defaultnofooter
title: Summary
permalink: /summary/
---

<div style="text-align: center">

</div>
<div>
<br/>
 <!-- <span class="vscomment">// =============================================================================================================
<br/>
  </span> -->


  <span style="font-size:21px">Summary</span>
<br/>

  <span class="vsparam">Jump to: [<a class="vsenum" href="{{ "/summary/#TECHNICALITIES "| prepend: site.baseurl }}">Technicalities</a>]
[<a class="vsenum" href="{{ "/summary/#JOIN "| prepend: site.baseurl }}">Join</a>]
[<a class="vsenum" href="{{ "/summary/#AUTHOR "| prepend: site.baseurl }}">Author</a>]</span> <br/>
<br/>

    <span class="vstype">Hypersomnia</span> is an upcoming 2D multiplayer <span class="vstype">futuristic</span> universe with elements of <span class="vskeyword">fast-paced shooter</span>, <span class="vskeyword"> stealth </span> and <span class="vskeyword">role-playing game</span>. 
    <br/>Set in a hypothetical afterlife reality, it is meant to provide joy through altruistic behaviours and fulfillment of elaborate social roles,<br/>including, but not limited to, sowing panic as a traitor to benevolent ones. <br/><br/>
    Decide upon your allegiance to one of the three warring factions whose apple of discord is
    a disparity between prevailing notions of <span class="vsmacro">moral excellence</span>.<br/>
 <span class="vstype">Metropolis</span>; <span class="vstype">Atlantis</span>; <span class="vstype">Resistance.</span><br/>

    <br/>The project is being brought to life with mere forces of a single man; <br/>
    he holds the project in his highest esteem and is well aware it will necessarily take months of intense, wholehearted labour. <br/>

<div>

<div>
<br/>
  <span class="vscomment">// Progress</span><br/><br/>
  I will not keep any official list with current features for it is bound to outdate in a matter of days.<br/>
  The purpose of this website is to portray state-of-the-art through <a class="vsenum" href="https://drive.google.com/folderview?id=0B_gBQSJQBKcjTzJ2bDVhWDhxSjQ&usp=sharing">in-game pictures</a> and most importantly, <a class="vsenum" href="{{site.url}}">blog posts</a>.
  
<br/>
    <br/>
    There is yet no official <span class="vskeyword">lore</span> or <span class="vskeyword">wiki</span> apart from a huge <span class="vstype">Game Design Document</span> whose assumptions are being slowly, yet steadily, fulfilled.<br/>
    The stories written are many, but they will be polished and revealed when all else is complete. Stay tuned!<br/>

<br/>

  <span class="vscomment">// Tiled cathedral with dynamic pixel-art lighting </span>
<br/>
<br/>
<img src="{{ site.img_dir }}summary.png"/>
<br/>
<br/>
[<a class="vsenum" href="{{ "/screenshots"| prepend: site.baseurl }}">More screenshots</a>]
<br/>
<br/>
<a class="vsenum" href="https://www.youtube.com/watch?v=Z622YeKcv9k">Here you can watch a very old singleplayer version with nasty enemies.</a>
<br/>
<br/>
  </div>
  <span class="vscomment" id="TECHNICALITIES">// Technicalities </span>
    <br/>

    <br/>
    As of currently, the project takes advantage of the following technologies:<br/>
    * <span class="vsenum">C++</span><br/>
    * <a href="https://www.opengl.org/" class="vsenum">OpenGL</a><br/>
    * <a href="https://www.box2d.org/" class="vsenum">Box2D</a> <span class="vscomment">  // physics simulation engine</span><br/>
    * <a href="http://www.rasterbar.com/products/luabind.html" class="vsenum">Lua with Luabind</a><span class="vscomment">  // mostly configuration</span><br/>
    * <a href="http://www.jenkinssoftware.com/" class="vsenum">RakNet</a><span class="vscomment">  // networking engine </span><br/>
    * <a href="https://github.com/ivanfratric/polypartition" class="vsenum">polypartition</a><span class="vscomment"> // polygon partitioning library </span><br/>
    * <a href="https://www.freetype.org/" class="vsenum">FreeType</a><span class="vscomment">  // font glyph rendering </span><br/>
    <br/>
    The rest being the craftsmanship of the author.<br/>
    <br/>
I am currently in the process of rewriting some of the major features from <span class="vstype">Lua</span> into <span class="vstype">C++</span>,<br/>most notably working multiplayer server (can connect with 3-4 players and shoot each other), pixel-art lighting and enemy AI.<br/>
This is necessary as I want to be able to handle tens or maybe hundreds of simultaneous players easily.<br/> 
    <br/>
  <span id="JOIN" class="vscomment">// Join </span>
<br/>
<br/>

  If you wish to contribute to development of Hypersomnia, you are free to fork <a class="vsenum" href="https://github.com/geneotech/Augmentations">Augmentations</a> (the codebase) and <a class="vsenum" href="https://github.com/geneotech/Hypersomnia">Hypersomnia</a> (mostly assets and configs).<br/>
  I currently do not distribute up-to-date executables, but it is trivial to build and launch the current version using <span class="vsstring">instructions</span> <a class="vsenum" href="https://github.com/geneotech/Augmentations/blob/master/build_instructions.txt">here</a>.
<br/>
<br/>

If you dream about creating an entirely new mechanic, I recommend that you be familiar with <a class ="vsenum" href="http://gamedev.stackexchange.com/questions/31473/what-is-the-role-of-systems-in-a-component-based-entity-
architecture">component-based entity architecture</a> beforehand.<br/> Better yet, tell me about your plans! Together we can deal with problems more swiftly.
<br/>
<br/>
This website's repository is located <a class="vsenum" href="https://github.com/geneotech/geneotech.github.io">here.</a>
<br/>
<br/>
I am sure to consider every <span class="vstype">pull request</span>.

<br/>
<br/>
  If you have a serious offer, <a class="vsenum" href="mailto:patryk.czachurski@gmail.com">contact me via mail.</a> <br/>
  Or if you just can't wait to utter some brilliant suggestions regarding the game or the website, please do so, too! 
<br/>

<!--
<div class="vsparam" style="text-align: center">
Copyright © 
<script type="text/javascript">
var d = new Date()
document.write(d.getFullYear())
</script> Patryk Czachurski
</div>
-->

<br/>

  <span id="AUTHOR" class="vscomment">// Author </span>
<br/>
<br/>

  I am an independent developer with a lifelong interest in study and practice of engineering simulations. <br/>
  I was born in <span class="vsnumber">1995</span>, involved myself deeply in programming by <span class="vsnumber">2008</span> and have been enamoured with this activity ever since.<br/><br/>

I am currently working full-time on Hypersomnia project and will continue to do so regardless of hardships to come.
<br/><br/>

  You can find me on <a class="vsenum" href="http://stackexchange.com/users/236344/devdalus?tab=accounts">StackExchange</a> and all of my former projects on <a class="vsenum" href="https://github.com/geneotech/">GitHub</a>. 
  <br/>Contact me via <a class="vsenum" href="mailto:patryk.czachurski@gmail.com">e-mail</a>.<br/>
  Most of the time I'm also active on our official <a class="vsenum" href="{{ "/ts3"| prepend: site.baseurl }}">TeamSpeak 3 server</a>.<br/>
  Want to play vidya? <a class="vsenum" href="http://steamcommunity.com/id/hypersomnialeaddev/">Add me on Steam</a>.
<br/><br/>

<span class="vscomment">// Trivia</span><br/><br/>
<a class="vsenum" href="http://math.stackexchange.com/questions/1579998/fractals-using-just-modulo-operation">My research on prime numbers<br/>
<a class="vsenum" href="https://www.youtube.com/watch?v=pjolw0OFPKM"><span class="vstype">Sensibilia</span> - my game project for ImagineCup Contest</a> <span class="vscomment"> // its description got me TOP30 of Poland. The project is abandoned</span><br/>

<br/>

<span class="vsparam">
  I envision a server populated with players of my game, a warm processing unit that continuously propagates schemata I've designed;<br/>
  an entropic entity that tirelessly exchanges state of my macrocosm with hundreds of individuals across the planet, whilst scattering <span class="vstype">cyan neons</span> across the dark bedroom.<br/><br/>
  When I place this machine under my pillow and fall asleep while listening to the heartbeat of my universe, my life will be complete.<br/>
</span>

<br/>
<div style="text-align:center">
<a class="vsparam" href="{{ "/summary/#TOP"| prepend: site.baseurl }}"> <img src="{{ "/dove.gif "| prepend: site.baseurl }}" style="border: 0"/></a>
</div>
