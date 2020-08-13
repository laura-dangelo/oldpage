---
layout: archive
title: "Contacts"
permalink: /contacts/
author_profile: true
---

{% include base_path %}
<font style="font-size:17px">
Department of Statistical Sciences <br/>
University of Padova<br/>
Via Cesare Battisti 241 <br>
35121 Padova, Italy<br/>

<br>


<b>Email:</b> <br>
<textarea id="clip" style="position: absolute; left: 100px; top: -100px;">Test</textarea>
<div class="tooltip">
<button id="copyButton">laura.dangelo.1@phd.unipd.it</button>
<span class="tooltiptext"> Copy to clipboard </span>
</div> 
<br/>
<textarea id="clip" style="position: absolute; left: 100px; top: -100px;">Test</textarea>
<div class="tooltip">
<button id="copyButton2">dangelo@stat.unipd.it</button>
<span class="tooltiptext"> Copy to clipboard </span>
</div> 
</font>

<br/>

[<img src="../images/github_gray.png" width="35">](https://github.com/laura-dangelo)
[<img src="../images/linkedin_gray.png" width="35">](https://www.linkedin.com/in/laura-dangelo/)
[<img src="../images/rg_gray.png" width="35">](https://www.researchgate.net/profile/Laura_Dangelo)
[<img src="../images/orcid_gray.png" width="35">](https://orcid.org/0000-0001-5034-7414)

<style>
button {
  background: none!important;
  border: none;
  padding: 0!important;
  /*optional*/
  font-family: arial, sans-serif;
  /*input has OS specific font-family*/
  color: #44494d;
  cursor: pointer;
}
button:onlick{
  color: #fff;
}
</style>


<script>
document.getElementById('copyButton').addEventListener('click', function() {
  var ta = document.getElementById('clip');
  ta.innerHTML = "laura.dangelo.1@phd.unipd.it";
  ta.focus();
  ta.select();
  console.log(document.execCommand('copy'));
});
</script>

<script>
document.getElementById('copyButton2').addEventListener('click', function() {
  var ta = document.getElementById('clip');
  ta.innerHTML = "dangelo@stat.unipd.it";
  ta.focus();
  ta.select();
  console.log(document.execCommand('copy'));
});
</script>

 <style>
/* Tooltip container */
.tooltip {
  position: relative;
  display: inline-block;
  border-bottom: 1px dotted #44494d; /* If you want dots under the hoverable text */
}

/* Tooltip text */
.tooltip .tooltiptext {
  visibility: hidden;
  width: 120px;
  bottom: 100%;
  left: 50%;
  margin-left: -60px;
  position: absolute;
  z-index: 1;

  background-color: #44494d;
  color: #fff;
  text-align: center;
  padding: 5px 0;
  border-radius: 6px;
  font-size: 15px;
}

.tooltip .tooltiptext::after {
  content: " ";
  position: absolute;
  top: 100%; /* At the bottom of the tooltip */
  left: 50%;
  margin-left: -5px;
  border-width: 5px;
  border-style: solid;
  border-color: #44494d transparent transparent transparent;
}
.tooltip.right  { margin-left: 15px; }
.tooltip.left   { margin-left: -15px; }

/* Show the tooltip text when you mouse over the tooltip container */
.tooltip:hover .tooltiptext {
  visibility: visible;
}
</style>
