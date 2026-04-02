---
layout: page
title: なにをしていますか?
search_exclude: true
---

## restricted access
このページはほごされています。にんしょうじょうほうをにゅうりょくしてください。

<div id="lock-screen">
  <input type="text" id="username" placeholder="Username" style="display:block; margin: 10px auto; padding: 8px; border-radius: 5px; border: 1px solid #ccc;">
  <input type="password" id="password" placeholder="Password" style="display:block; margin: 10px auto; padding: 8px; border-radius: 5px; border: 1px solid #ccc;">
  <button onclick="checkAuth()" style="background: #222; color: #fff; padding: 8px 20px; border: none; border-radius: 5px; cursor: pointer;">Login</button>
  <p id="message" style="color:red; margin-top: 10px;"></p>
</div>

<div id="secret-content" style="display:none;">








### Detective Conan OPENING
Opening 01 (MuneGaDokiDoki) 1996 vs 2016 vs 2026
<iframe src="https://drive.google.com/file/d/1vtmXZR-wi--qbgXOSf2N4LdC3DX0DTTe/preview" width="640" height="480"></iframe>


Conan sus Moment.
<iframe src="https://drive.google.com/file/d/1d1lm1SUs3XwSQmlTMhn9pGI1pZeTxo3r/preview" width="640" height="480"></iframe>
</div>

<script>
function checkAuth() {
    const user = document.getElementById('username').value;
    const pass = document.getElementById('password').value;
    
    if (user === "ernugraha" && pass === "abc") {
        document.getElementById('lock-screen').style.display = 'none';
        document.getElementById('secret-content').style.display = 'block';
    } else {
        document.getElementById('message').innerText = "ぱすわーどがちがいます！あどみんにきいてください。";
    }
}
</script>