<template>
  <div class="nav-content">
    <div class="nav-element disHighlight">
      supernatural.net
    </div>
    <div class="nav-element disHighlight">
      merchendise
    </div>
    <div class="nav-element disHighlight">
      about
    </div>
    <div class="nav-element disHighlight">
      sign up
    </div>
  </div>
</template>

<script>
export default {
  name: 'Navbar'
}
</script>

<style scoped>
.nav-content {
  z-index: 9999;
  position: fixed;
  top: 0;
  width: 100%;
  color: white;
  display: flex;

}

.nav-element {
  padding: 15px 25px;
  flex: 1;
  text-align: center;
}

.nav-element:hover {
  text-decoration: underline;
  cursor: pointer;
  background-color: rgba(255,255,255,0.5);
}

</style>
