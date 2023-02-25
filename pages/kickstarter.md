---
layout: page
title: Kickstarter
permalink: /kickstarter/
---
<style>
.post {
    background: #F0F0F0;
    z-index: 0;
}
.sidebar {
    position: sticky;
    border: 2px solid lightgray;
    min-width: 15vw;
    max-width: 25vw;
    background: white;
    overflow-y: auto;
    overflow-x: clip;
    top: 15vh;
    max-height: 75vh;
}
.sidebar button {
    background-color: #4CAF50;
    border: none;
    border-radius: 1em;
    color: white;
    padding: 15px 15px;
    text-align: left;
    text-decoration: none;
    display: inline-block;
    font-size: 16px;
    box-shadow: 0px 8px 24px;
    transition: all 100ms;
    width: 100%;
}
.sidebar button:hover {
    cursor: pointer;
    transform: scale(1.03);
}
.sidebar button h4 {
    text-align: center;
}
.kickstarter-gradient {
    background-image: linear-gradient(rgb(219, 231, 255), rgb(255, 242, 236));
    border: 1px solid rgb(219, 231, 255);
}
.page-content .wrapper {
    display: flex;
    justify-content: space-evenly;
    max-width: none;
}
.page-content .wrapper:after {
    content: none;
}
.page-content .wrapper .post {
    max-width: calc(800px - (30px * 2))
}
.goal {
    background: green;
    border-radius: 30px;
    padding-left: 20px;
    padding-right: 20px;
    line-height: 40px;
    text-align: center;
    width: 30vw;
    margin-left: auto;
    margin-right: auto;
    margin-bottom: 20px;
    outline: 2px solid lightgreen;
    color: white;
    display: flex;
}
.price {
    color: lightgray;
    flex-grow: 0;
}
.goal-name {
    flex-grow: 1;
}
.piechart {
  width: 300px;
  height: 300px;
  background-image: conic-gradient(red 0turn 0.3turn, yellow 0.3turn 0.65turn, green 0.65turn 0.75turn, blue 0.75turn 0.95turn, purple 0.95turn 1turn);
  border-radius: 50%;
  margin: auto;
}
.legend {
    width: 200px;
    border: 1px solid gray
}
.legend-color {
    width: 1em;
    height: 1em;
    border: 1px solid black;
    display: inline-block;
}
th {
    padding: 0px;
}
.slider-container {
    border: 3px solid gray;
    height: 3em;
    border-radius: 1.5em;
    width: 30vw;
    margin-left: auto;
    margin-right: auto;
    margin-bottom: 20px;
    display: flex;
    position: relative;
    padding-left: 20px;
    padding-right: 20px;
    line-height: 3em;
    text-align: center;
}
.slider {
    background-color: red;
    width: 17%;
    height: 100%;
    border-radius: 1.5em 0 0 1.5em;
    flex-basis: 0;
    position: absolute;
    left: 0;
    z-index: -1;
}
</style>

<div id="kickstarter-sidebar" class="sidebar">
    <h4><b>Support</b></h4>
    <button>
        <h4>Pledge without a reward</h4>
        <label>$</label><input placeholder="enter a value"/>
        <div class="kickstarter-gradient">
            <b>Back it because you beleive in it.</b>
            <p>Support the project for no reward, just because it speats to you.</p>
        </div>
    </button><br />
    <h4>Backer tiers:</h4>
    <button>
        <h4>Pledge $2 or more</h4>
        <b>Supporter</b>
        <h5>Includes:</h5>
        <ul>
            <li>🎮 early access</li>
        </ul>
    </button><br /><br />
    <button>
        <h4>Pledge $5 or more</h4>
        <b>Contributor</b>
        <h5>Includes:</h5>
        <ul>
            <li>🚲 promotional sticker with our logo</li>
            <li>🎮 early access</li>
        </ul>
    </button><br /><br />
    <button>
        <h4>Pledge $15 or more</h4>
        <b>Generous Donor</b>
        <h5>Includes:</h5>
        <ul>
            <li>👕 T-shirt with our logo</li>
            <li>🚲 promotional sticker with our logo</li>
            <li>🎮 early access</li>
        </ul>
    </button><br /><br />
    <button>
        <h4>Pledge $45 or more</h4>
        <b>Team Member</b>
        <h5>Includes:</h5>
        <ul>
            <li>👕 T-shirt with our logo</li>
            <li>🚲 promotional sticker with our logo</li>
            <li>🎮 early access</li>
        </ul>
    </button><br /><br />
</div>



#### this is our mock kickstarter page. It's not actually real. Please don't donate to us. We don't want your money.
--------
## Doordash Academy
![Key Visial](/assets/img/KeyVisual.png)
<!-- maybe replace this with trailer video once we have it -->

Doordash Academy is a food delivery simulator with some additional twists. The goal of the game is to deliver the food as quickly as possible while dodging obstacles and selectively breaking traffic laws. Faster deliveries means more money for better, faster vehicles, and accessories. Crashing or getting caught speeding results in monetary fines.

The project has been in active development since January 2023, when it started as a capstone project for a group of students at the University of Washington.

## Goals
<p style="text-align: center;"><b> 17% of $5k funding goal reached! </b></p>
<div class="slider-container">
    <div class="slider"></div>
    <label class="price">$5000</label>
    <label class="goal-name">Project funding</label>
</div>
<div class="goal">
    <label class="price">$7000</label>
    <label class="goal-name">Add police AI</label>
</div>
<div class="goal">
    <label class="price">$10000</label>
    <label class="goal-name">Create maps based on real locations</label>
</div>
<div class="goal">
    <label class="price">$15000</label>
    <label class="goal-name">Mobile support and publish to Google Play</label>
</div>
<div class="goal">
    <label class="price">$17000</label>
    <label class="goal-name">iOS support and publish to App Store</label>
</div>


### kickstarter donations distribution:
<div class="piechart"></div>
<div class="legend">
    <div class="legend-color" style="background-color: red;"></div> <label>Developer fees</label><br />
    <div class="legend-color" style="background-color: yellow;"></div> <label>Assets</label><br />
    <div class="legend-color" style="background-color: green;"></div> <label>Software</label><br />
    <div class="legend-color" style="background-color: blue;"></div> <label>Music</label><br />
    <div class="legend-color" style="background-color: purple;"></div> <label>Kickstarter fees</label><br />
</div>



### backer rewards:
<table>
    <tr>
        <th width="25%"></th>
        <th>$2</th>
        <th>$5</th>
        <th>$15</th>
        <th>$45</th>
    </tr>
    <tr>
        <th>early access</th>
        <td>X</td>
        <td>X</td>
        <td>X</td>
        <td>X</td>
    </tr>
    <tr>
        <th>sticker with logo</th>
        <td></td>
        <td>X</td>
        <td>X</td>
        <td>X</td>
    </tr>
    <tr>
        <th>tshirt with logo</th>
        <td></td>
        <td></td>
        <td>X</td>
        <td>X</td>
    </tr>
</table>

## Details about the game
In Doordash Academy, your goal is to become the world's best delivery driver, and earn lots of money along the way!
In the game, you start by driving to a restaurant to pick up food, and then you deliver it to a certain location on the map. To complicate things, there are many obstabcles like cars on the roads, and pedestrians on the sidewalks, that you must avoid hitting. Also, if you don't deliver the food quickly enough, it will get cold and you won't earn a good tip from the customer!

![Gameplay screenshot](/assets/img/zoom-driving.png)

![Main Menu screenshot](/assets/img/main-menu.png)

The different levels in the game come in the form of different maps. So far, we have a tutorial and a simple city map, but development is already in progress for adding a rural map and a suburb map.

![Map Menu screen](/assets/img/maps-menu.png)

In addition to unlocking new maps, players can also unlock upgrades for their vehicle using the money they earn. There are upgrades for keeping food warmer longer, driving faster, having more health, etc.

## About the team
 * Riya Dheer
 * Connor Espig
 * Cole Hahn
 * Ashwin Naresh
 * Brett Saiki

We are a group of students at the University of Washington, studying computer science/computer engineering. We are super excited to be working on this game, and with your contributions, we will be able to continue development and make this game even more fun!

For more information about the game or our team, feel free to check out our website [https://doordashacademy-cse481d-wi23.github.io/](https://doordashacademy-cse481d-wi23.github.io/), and follow us on [Instagram](https://instagram.com/doordashacademygame) and [Tiktok](https://tiktok.com/@doordash_academy_game) for the latest updates!


<script>
var wrapper = document.getElementsByClassName("wrapper")[1];
var sidebar = document.getElementById("kickstarter-sidebar");
wrapper.append(sidebar);
var copy = sidebar.cloneNode(true);
copy.style.visibility = "hidden";
wrapper.prepend(copy);
</script>