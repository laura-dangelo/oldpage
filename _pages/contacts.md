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
laura.dangelo.1@phd.unipd.it <br/>
dangelo@stat.unipd.it
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
  cursor: pointer;
}
</style>

<script>
var copyTextareaBtn = document.querySelector('.js-textareacopybtn');

copyTextareaBtn.addEventListener('click', function(event) {
  var copyTextarea = document.querySelector('.js-copytextarea');
  copyTextarea.focus();
  copyTextarea.select();

  try {
    var successful = document.execCommand('copy');
    var msg = successful ? 'successful' : 'unsuccessful';
    console.log('Copying text command was ' + msg);
  } catch (err) {
    console.log('Oops, unable to copy');
  }
});
</script>

<p>
  <button class="js-textareacopybtn" style="vertical-align:top;">Copy Textarea</button>
  <textarea class="js-copytextarea">Hello I'm some text</textarea>
</p>
