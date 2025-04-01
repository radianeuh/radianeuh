<p align="center">
  <img id="dynamic-theme-image" src="" />
</p>

<script>
  const themes = [
    "https://count.getloli.com/@radianeuh?name=radianeuh&theme=booru-lisu&padding=7&offset=0&align=bottom&scale=2&pixelated=1&darkmode=1",
    "https://count.getloli.com/@radianeuh?name=radianeuh&theme=booru-qualityhentais&padding=7&offset=0&align=bottom&scale=2&pixelated=1&darkmode=1",
    "https://count.getloli.com/@radianeuh?name=radianeuh&theme=booru-jaypee&padding=7&offset=0&align=bottom&scale=2&pixelated=1&darkmode=1"
  ];

  const randomTheme = themes[Math.floor(Math.random() * themes.length)];
  document.getElementById('dynamic-theme-image').src = randomTheme;
</script>
