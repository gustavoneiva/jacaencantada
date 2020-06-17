<template>
  <div>
    <nav class="navbar">
      <div class="container">
        <div class="navbar-brand">
            <a class="navbar-item" href="../">
                JACA ENCANTADA
            </a>
            <span class="navbar-burger burger" data-target="navbarMenu">
                <span></span>
                <span></span>
                <span></span>
            </span>
        </div>
        <div id="navbarMenu" class="navbar-menu">
            <div class="navbar-end">
                <span class="navbar-item">
                </span>
            </div>
        </div>
      </div>
    </nav>
  </div>
</template>

<script>
export default {
  name: 'Navbar'
}
</script>

<style scoped>
.navbar{
  background-color: #004F2D;

}
.navbar-item {
  color: #EAD637;
}
</style>
