<template>
  <div class="flex-container">
    <div class="image-container">
      <img
        src="https://upload.wikimedia.org/wikipedia/commons/thumb/2/2a/Early_Hardcore_symbol.svg/800px-Early_Hardcore_symbol.svg.png"
        alt="Imagen"
      />
      <img
        src="https://www.allfest.es/wp-content/uploads/2023/02/Defqon-1-3.jpg"
        alt="Imagen"
      />
      <img
        src="https://www.laguiago.com/wp-content/uploads/2021/03/A-Summer-History-e1615812023786.jpg"
        alt="Imagen"
      />
    </div>
  </div>
</template>

<script setup></script>

<style scoped>
.flex-container {
  display: flex;
  justify-content: center;
}

.image-container {
  margin-bottom: 20px;
  max-width: 100%;
  display: flex;
  flex-direction: row;
  justify-content: space-between;
}

img {
  max-width: 30%; /* Cambié el valor para que haya espacio entre las imágenes */
  height: auto;
  border-radius: 5px;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}
</style>
