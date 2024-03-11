<template>
  <div class="audio-container">
    <audio controls>
      <source src="./audio.mp3" type="audio/mp3" />
      Tu navegador no admite el elemento de audio.
    </audio>
  </div>
</template>

<script setup></script>

<style scoped>
.audio-container {
  margin-bottom: 20px;
}


audio {
  width: 100%; 
  background-color: #f5f5f5; 
  border-radius: 5px; 
  padding: 10px; 
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1); 
}


audio::-webkit-media-controls-panel {
  background-color: #333; 
  color: #fff; 
  border-radius: 5px; 
}


audio::-webkit-media-controls-current-time-display,
audio::-webkit-media-controls-time-remaining-display {
  color: #fff; 
}
</style>
