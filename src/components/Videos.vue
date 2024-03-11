<template>
  <div class="flex-container">
    <div class="video-container">
      <video controls>
        <source src="./video.mp4" type="video/mp4">
        Tu navegador no admite el elemento video.
      </video>
    </div>
  </div>
</template>

<script setup>
</script>

<style scoped>
.flex-container {
  display: flex;
  justify-content: center;
}

.video-container {
  margin-bottom: 20px;
  max-width: 50%;
}

video {
  width: 100%; 
  height: auto; 
}
</style>
