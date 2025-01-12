<template>
  <div id="app">
    <div class="container">
      <Icons />
      <ProfilePicture />
      <Biography />
    </div>
  </div>
</template>

<script>
import Icons from './components/Icons.vue';
import ProfilePicture from './components/ProfilePicture.vue';
import Biography from './components/Biography.vue';

export default {
  components: {
    Icons,
    ProfilePicture,
    Biography
  }
};
</script>

<style>
#app {
  background-color: #fff;
  display: flex;
  flex-direction: row;
  height: 100vh;
  justify-content: space-around;
  align-items: center;
  flex-direction: column;
}
.container {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-items: center;
  width: 100%;
  padding: 20px;
  gap: 20px;
  flex-wrap: wrap;
}

/* Responsividade */
@media (max-width: 1024px) {
  .container {
    flex-direction: column;
    align-items: center;
  }
}
</style>
