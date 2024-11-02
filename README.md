# 👋 Hi, I’m Emily Huang

![Welcome](https://img.shields.io/badge/Always-Learning-ff69b4?style=flat-square&logo=GitHub)

<p align="center">
  <img src="https://github.com/<YourUsername>/<YourRepo>/blob/main/header.gif" alt="Welcome animation" width="400"/>
</p>

```html
<!-- Animated text for "Always Learning" -->
<div align="center">
  <h2>Always Learning</h2>
  <p><span id="learn-text"></span></p>
</div>

<script>
let text = "Always Learning";
let i = 0;
function typeEffect() {
    if (i < text.length) {
        document.getElementById("learn-text").innerHTML += text.charAt(i);
        i++;
        setTimeout(typeEffect, 150);
    }
}
typeEffect();
</script>
