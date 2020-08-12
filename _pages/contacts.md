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


```html
<!DOCTYPE html>
<html>
<link href='https://fonts.googleapis.com/css?family=Oswald' rel='stylesheet' type='text/css'> 

<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.11.1/jquery.min.js"></script>

<p style="color:wheat;font-size:55px;text-align:center;">How to copy a TEXT to Clipboard on a Button-Click</p>

<center>
<p id="p1">Hello, I'm TEXT 1</p>
<p id="p2">Hi, I'm the 2nd TEXT</p><br/>

<button onclick="copyToClipboard('#p1')">Copy TEXT 1</button>
<button onclick="copyToClipboard('#p2')">Copy TEXT 2</button>
  
<br/><br/><input class="textBox" type="text" id="" placeholder="Dont belive me?..TEST it here..;)" />
</center>
</html>
```

```css
body {
              background-color:#999999;
              font-family: 'Oswald', sans-serif;
      }
p
{
  color:#000000;
  font-size:20px;
}

.textBox
{
  height:30px;
  width:300px;
}

button
{
  height:30px;
  width:150px;
  border-radius:8px;
  padding:10px;
  font-size:20px;
  font-family: 'Oswald', sans-serif;
  height:52px;
  cursor:pointer;
  background-color:wheat;
}
```

```javascript
function copyToClipboard(element) {
  var $temp = $("<input>");
  $("body").append($temp);
  $temp.val($(element).text()).select();
  document.execCommand("copy");
  $temp.remove();
}
```
