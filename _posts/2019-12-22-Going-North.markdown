---
layout: post
title:  "Going North"
date:   2019-12-22 07:00:00
---

## Instructions
Arrow keys to move. Refresh page to restart. Please keep the sound on!

## Game
<canvas id="canvas" oncontextmenu="event.preventDefault()" height="600px" width="960px"></canvas>

## Fullscreen
<div class="fullscreen"><a href="" onclick="SetFullscreen(1); return false;">Play in Fullscreen</a></div>
<script type='text/javascript'>
  var Module = {
    TOTAL_MEMORY: 268435456,
    errorhandler: null,         // arguments: err, url, line. This function must return 'true' if the error is handled, otherwise 'false'
    compatibilitycheck: null,
    backgroundColor: "#222C36",
    splashStyle: "Light",
    dataUrl: "../../../../static/Games/advice/Release/web.data",
    codeUrl: "../../../../static/Games/advice/Release/web.js",
    asmUrl: "../../../../static/Games/advice/Release/web.asm.js",
    memUrl: "../../../../static/Games/advice/Release/web.mem",
  };
</script>
<script src="../../../../static/Games/advice/TemplateData/UnityProgress.js"></script>
<script src="../../../../static/Games/advice/Release/UnityLoader.js"></script>

