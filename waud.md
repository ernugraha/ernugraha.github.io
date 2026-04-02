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
How u know?
</div>

<script>
function checkAuth() {
    const user = document.getElementById('username').value;
    const pass = document.getElementById('password').value;
    
    if (user === "ernugraha" && pass === "95421") {
        document.getElementById('lock-screen').style.display = 'none';
        document.getElementById('secret-content').style.display = 'block';
    } else {
        document.getElementById('message').innerText = "ぱすわーどがちがいます！あどみんにきいてください。";
    }
}
</script>