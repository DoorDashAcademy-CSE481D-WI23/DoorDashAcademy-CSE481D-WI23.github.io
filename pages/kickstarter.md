---
layout: page
title: Kickstarter
permalink: /kickstarter/
---
<style>
.post {
    background: #F0F0F0;
}
.sidebar {
    position: sticky;
    border: 2px solid lightgray;
    min-width: max-content;
    background: white;
    overflow-y: auto;
    top: 15vh;
    max-height: 75vh;
}
.sidebar button {
    background-color: #4CAF50;
    border: none;
    border-radius: 1em;
    color: white;
    padding: 15px 32px;
    text-align: center;
    text-decoration: none;
    display: inline-block;
    font-size: 16px;
    box-shadow: 0px 8px 24px;
    transition: all 100ms;
}
.sidebar button:hover {
    cursor: pointer;
    transform: scale(1.03);

}
.page-content .wrapper {
    display: flex;
    justify-content: space-between;
    max-width: none;
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
.goal .price {
    color: lightgray;
    flex-grow: 0;
}
.goal .goal-name {
    flex-grow: 1;
}
.piechart {
  width: 300px;
  height: 300px;
  background-image: conic-gradient(orange 64%, blue 37%);
  border-radius: 50%;
  margin: auto;
}
th {
    padding: 0px;
}
</style>

<div id="kickstarter-sidebar" class="sidebar">
    <h4><b>Support</b></h4>
    <button><h4>Donate without a reward</h4><label>$</label><input placeholder="enter a value"/></button><br />
    <h4>Backer tiers:</h4>
    <button><h4>Donate $2 or more</h4></button><br /><br />
    <button><h4>Donate $5 or more</h4></button><br /><br />
    <button><h4>Donate $15 or more</h4></button><br /><br />
    <button><h4>Donate $45 or more</h4></button><br />
</div>



#### this is our mock kickstarter page
--------
## Doordash Academy
![Key Visial](/assets/img/KeyVisual.png)
<!-- maybe replace this with trailer video once we have it -->

Doordash Academy is a food delivery simulator with some additional twists. The goal of the game is to deliver the food as quickly as possible while dodging obstacles and selectively breaking traffic laws. Faster deliveries means more money for better, faster vehicles, and accessories. Crashing or getting caught speeding results in monetary fines.

The project has been in active development since January 2023, when it started as a capstone project for a group of students at the University of Washington.

## Goals
<div class="goal">
    <label class="price">$200</label>
    <label class="goal-name">Add police AI</label>
</div>
<div class="goal">
    <label class="price">$500</label>
    <label class="goal-name">Create maps based on real locations</label>
</div>
<div class="goal">
    <label class="price">$1200</label>
    <label class="goal-name">Mobile support and publish to Google Play</label>
</div>
<div class="goal">
    <label class="price">$1400</label>
    <label class="goal-name">iOS support and publish to App Store</label>
</div>

### kickstarter donations distribution:
<div class="piechart"></div>
*this is just a random pie chart*


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

![Key Visial](/assets/img/maps-menu.png)

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