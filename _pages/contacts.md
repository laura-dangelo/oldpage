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

<p>Email me at <a class="js-emaillink" href="mailto:matt@example.co.uk">matt@example.co.uk</a></p>
<p><button class="js-emailcopybtn">ddd</button></p>

<script>
  var copyEmailBtn = document.querySelector('.js-emailcopybtn');
copyEmailBtn.addEventListener('click', function(event) {
  // Select the email link anchor text
  var emailLink = document.querySelector('.js-emaillink');
  var range = document.createRange();
  range.selectNode(emailLink);
  window.getSelection().addRange(range);

  try {
    // Now that we've selected the anchor text, execute the copy command
    var successful = document.execCommand('copy');
    var msg = successful ? 'successful' : 'unsuccessful';
    console.log('Copy email command was ' + msg);
  } catch(err) {
    console.log('Oops, unable to copy');
  }

  // Remove the selections - NOTE: Should use
  // removeRange(range) when it is supported
  window.getSelection().removeAllRanges();
});
</script>
