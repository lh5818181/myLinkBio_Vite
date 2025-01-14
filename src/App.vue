<template>
  <div id="app">
    <div class="container">
      <Icons />
      <ProfilePicture />
      <Biography />
    </div>
    <footer class="footer">
      <p>© Todos os direitos reservados</p>
    </footer>
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
  flex-direction: column;
  height: 100vh;
  justify-content: space-between;
  align-items: center;
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

.footer {
    text-align: center;
    width: 30%;
    background-color: #bdc3c7;
    border-radius: 10px;
    color: #000000;
}
</style>
