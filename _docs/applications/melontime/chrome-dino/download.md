---
layout: post
title: MelonTime﹕Chrome Dino game hacks download
date: 2022-04-16 17:20
author: yeahgamesdevs
tags: 
- download 
- exploits 
- Hack downloads 
- hacking
- melontime
---

{% include alert.html type="danger" title="Do not paste random scripts into the developer console!" content="Pasting scripts into the developer console can expose vulnerabilities that can expose vulnerable information, like your account credentials and IP address.  We have tested these scripts to ensure that they are safe, but use them at your own risk. The yEAh Games Corporation, LLC. waves all liability regarding MelonTime Hack downloads; if any damages occur, we are not responsible." %}

<!-- wp:paragraph -->
<p>This page lists the most recent version of hacks developed by the MelonTime team<sup>® </sup>(yEAh Games' hack series) for the Chrome dinosaur game.<br>

{% include alert.html type="info" title="The original hacks, along with other downloads, can be access from our Discord server." content="All original MelonTime<sup>®</sup> hacks, as well as other hack downloads, can be viewed in the [#hax-download](https://discord.com/channels/887052880782176266/894730499405258753) channel on our Discord server." %}

Please follow the instructions as we have listed them; there should be no threat if you follow these steps exactly as they are. 

<!-- wp:separator -->
<hr class="wp-block-separator has-alpha-channel-opacity" />
<!-- /wp:separator -->

<!-- wp:heading -->
<h2>EXPLOIT DOWNLOAD:</h2>
<!-- /wp:heading -->

<!-- wp:paragraph -->
<p><strong>All of the ChromeDino MelonTime</strong> <strong>hacks require you to do the following first steps: </strong></p>
<!-- /wp:paragraph -->

<!-- wp:list {"ordered":true} -->
<ol><li>Visit <a href="//dino">chrome://dino</a>, or cut off your internet connection and try searching something; this only works on <strong>Chrome</strong>, obviously.</li><li>Open up the executor by pressing <code>ctrl+shift+i</code> on your keyboard, and click on the "console" tab at the top.</li></ol>
<!-- /wp:list -->

<!-- wp:heading {"fontSize":"medium"} -->
<h2 class="has-medium-font-size">Invincibility (V. 1.0):</h2>
<!-- /wp:heading -->

<!-- wp:paragraph -->
<p>1. Start the exploiting system by pasting this JavaScript command into the console, and clicking "enter": <code>var original = Runner.prototype.gameOver</code><br>2. Start executing the command by pasting this command, and clicking "enter": <code>Runner.prototype.gameOver = function (){}</code><br>3. Try it!</p>
<!-- /wp:paragraph -->

<!-- wp:heading {"fontSize":"medium"} -->
<h2 class="has-medium-font-size">Jump height control (V. 2.0):</h2>
<!-- /wp:heading -->

<!-- wp:paragraph -->
<p>1. Start executing the exploit by pasting this command, and clicking "enter": <code>Runner.instance_.tRex.setJumpVelocity(x)</code> <br>⠀⠀▶︎ You will have to change the <em>x</em> variable to whatever <strong>number</strong> you want. So far, our tests have concluded that <strong>20</strong> is the max (nothing will change after that), and around <strong>10</strong> is the default. <br>⠀⠀▶︎ This is more useful for <strong>lowering</strong> the jump height than increasing it. <br>2. Close the executor panel by clicking on the "X" at the top right, and try a game.</p>
<!-- /wp:paragraph -->

<!-- wp:heading {"fontSize":"medium"} -->
<h2 class="has-medium-font-size">Speed control (V. 2.0):</h2>
<!-- /wp:heading -->

<!-- wp:list {"ordered":true} -->
<ol><li>Start executing the exploit by pasting this command, and clicking "enter": <code>Runner.instance_.setSpeed(x)</code> <br>⠀⠀▶︎ You will have to change the <em>x</em> variable to whatever <strong>number</strong> you want. This command is quite buggy and doesn't always work. </li><li>Close the executor panel by clicking on the "X" at the top right, and try a game.</li></ol>
<!-- /wp:list -->

<!-- wp:heading {"fontSize":"medium"} -->
<h2 class="has-medium-font-size"><strong>Automated jumping/crouching and obstacle-avoiding</strong> (V. 3.0):</h2>
<!-- /wp:heading -->

<!-- wp:paragraph -->
<p>Start executing the exploit by pasting this command, and clicking "enter":</p>
<!-- /wp:paragraph -->

<!-- wp:syntaxhighlighter/code -->
```js
function keyDown(e){Podium={};var n=document.createEvent("KeyboardEvent");Object.defineProperty(n,"keyCode",{get:function(){return this.keyCodeVal}}),n.initKeyboardEvent?n.initKeyboardEvent("keydown",!0,!0,document.defaultView,e,e,"","",!1,""):n.initKeyEvent("keydown",!0,!0,document.defaultView,!1,!1,!1,!1,e,0),n.keyCodeVal=e,document.body.dispatchEvent(n)}function keyUp(e){Podium={};var n=document.createEvent("KeyboardEvent");Object.defineProperty(n,"keyCode",{get:function(){return this.keyCodeVal}}),n.initKeyboardEvent?n.initKeyboardEvent("keyup",!0,!0,document.defaultView,e,e,"","",!1,""):n.initKeyEvent("keyup",!0,!0,document.defaultView,!1,!1,!1,!1,e,0),n.keyCodeVal=e,document.body.dispatchEvent(n)}setInterval(function(){Runner.instance_.horizon.obstacles.length&gt;0&amp;&amp;(Runner.instance_.horizon.obstacles[0].xPos&lt;25*Runner.instance_.currentSpeed-Runner.instance_.horizon.obstacles[0].width/2&amp;&amp;Runner.instance_.horizon.obstacles[0].yPos&gt;75&amp;&amp;(keyUp(40),keyDown(38)),Runner.instance_.horizon.obstacles[0].xPos&lt;30*Runner.instance_.currentSpeed-Runner.instance_.horizon.obstacles[0].width/2&amp;&amp;Runner.instance_.horizon.obstacles[0].yPos&lt;=75&amp;&amp;keyDown(40))},5);

Runner.instance_.setSpeed(1000)

var original = Runner.prototype.gameOver
Runner.prototype.gameOver = function(){}

//Runner.prototype.gameOver = original

Runner.instance_.distanceRan = 12345 / Runner.instance_.distanceMeter.config.COEFFICIENT

Runner.instance_.tRex.setJumpVelocity(10)
```
<!-- /wp:syntaxhighlighter/code -->

<!-- wp:paragraph -->
<p>⠀⠀▶︎ <strong>This hack works better if you do a game <em>without</em> any hacks, die, <em>and then</em> paste this command on the "Game over" screen. </strong><br>⠀⠀⠀⠀▶︎<strong> This will make the dinosaur avoid obstacles automatically.</strong> Otherwise, it will activate another kind of completely different, very crazy, hack that sends the dinosaur flying while your score goes to 100 000 in a few seconds. They both do different things.</p>
<!-- /wp:paragraph -->

<!-- wp:heading -->
<h2>OTHER INFORMATION:</h2>
<!-- /wp:heading -->

<!-- wp:list -->
<ul><li>If you refresh the page, all the hacks will be reset. </li><li>If you use too many hacks at once, many undesirable things could happen (e.g. game completely breaking, score not saving to high score, etc.). </li><li>Commands are case-sensitive. </li><li>Chrome dino game is blocked on school, administrator-controlled, accounts.</li></ul>
<!-- /wp:list -->
