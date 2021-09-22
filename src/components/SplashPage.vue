<template>
  <div class="splash">
    <div class="central">
      <h1>Evan Hood Benton</h1>
      <div class="links">
        <a target="_blank" href="https://www.youtube.com/user/CrystalSkillet/featured">
          <img id="youtube" alt="youtube" src="../assets/youtube.png"/>
        </a>
        <a target="_blank" href="https://www.instagram.com/evanhoodbenton/">
          <img id="instagram" alt="instagram" src="../assets/instagram.png"/>
        </a>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.splash {
  width: 100vw;
  height: 100vh;
  display: flex;
  flex-flow: column nowrap;
  justify-content: center;
  align-items: center;
}

.central {
  width: 25vw;
  min-width: 300px;
}

.links {
  display: flex;
  justify-content: space-around;
  align-items: center;
  width: 100%;
}

#youtube {
  height: 50px;
}

#instagram {
  height: 35px;
}
</style>
