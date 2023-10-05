---
title: home
layout: default
# permalink: home/
---

<p class="info" style="font-family: 'Poppins'; font-size: 20px; padding: 50px 300px; text-align: justify;">
<b>Le-v-el Platform provides standardized <a href="./dataset" class="hyperlink">benchmark datasets</a> for computational visualization understanding or Chart Question Answering. You can participate by <a href="./submit" class="hyperlink">submitting</a> the results of your algorithm.</b>
</p> 

<header>
    <img src="img/leaderboard_logo.png" alt="pic_of_leaderboard" width="80" height="80"/>
    <h1 style="font-family: 'Poppins'; font-size: 35px;">Current Leaderboard</h1>
    <div class="selection">
      <select name="dataset" id="dataset" style="font-size: 18px; border: 2px solid black;">
        <option value="All_Datasets">All Datasets</option>
        <option value="LEVEL1">LEVEL 1</option>
        <option value="LEVEL2">LEVEL 2</option>
        <option value="LEVEL3">LEVEL 3</option>
      </select>
    </div>
  </header>
<main>
    <table>
      <thead>
        <tr>
          <th>Team</th>
          <th>LEVEL 1 mean RMSE</th>
          <th>LEVEL 2 mean RMSE</th>
          <th>LEVEL 3 mean ERROR</th>
        </tr>
      </thead>
      <tbody>
      </tbody>
    </table>
  </main>
<script src="js/scripts.js"></script>
