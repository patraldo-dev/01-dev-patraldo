<script>
     let name = 'Christophe';
</script>


<h1>Welcome, {name.toUpperCase()}, to Patraldo Dot Dev</h1>
<p>A staging ground for web app development</p>


<video src="https://sveltejs.github.io/assets/caminandes-llamigos.mp4" alt='{name} dances up a storm' muted="false" loop controls />
<video src="https://storage.googleapis.com/patraldo/patraldo-dev/bg-paris300x400-x-out.mp4" alt='{name} dances up a storm' muted autoplay loop controls width="620" />

<div id="video-controls" class="controls" data-state="hidden">
  <button id="playpause" type="button" data-state="play">Play/Pause</button>
  <button id="stop" type="button" data-state="stop">Stop</button>
  <div class="progress">
    <progress id="progress" value="0" min="0">
      <span id="progress-bar"></span>
    </progress>
  </div>
  <button id="mute" type="button" data-state="mute">Mute/Unmute</button>
  <button id="volinc" type="button" data-state="volup">Vol+</button>
  <button id="voldec" type="button" data-state="voldown">Vol-</button>
  <button id="fs" type="button" data-state="go-fullscreen">Fullscreen</button>
</div>

