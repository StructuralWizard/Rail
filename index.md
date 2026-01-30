---
layout: home
title: Redirecting...
nav_exclude: true
---
<script>
  var userLang = navigator.language || navigator.userLanguage; 
  if (userLang.startsWith('es')) {
    window.location.href = "{{ '/es/' | relative_url }}";
  } else {
    window.location.href = "{{ '/en/' | relative_url }}";
  }
</script>

<p>Redirecting... <a href="{{ '/en/' | relative_url }}">Click here if nothing happens.</a></p>