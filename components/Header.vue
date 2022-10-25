<template>
  <div>
    <div class="container">
      <header
        class="d-flex flex-wrap justify-content-center py-3 mb-4 border-bottom"
      >
        <a
          href=""
          class="
            d-flex
            align-items-center
            mb-3 mb-md-0
            me-md-auto
            text-dark text-decoration-none
          "
        >
          <img src="../src/assets/logo-prime.png" alt="Logo" />
          <span class="fs-1">Bar do João</span>
        </a>

        <ul class="nav nav-pills">
          <li class="nav-item">
            <a href="../" class="nav-link active" aria-current="page">Home</a>
          </li>
          <li class="nav-item">
            <a href="bebidas" class="nav-link">Bebidas</a>
          </li>
          <li class="nav-item">
            <a href="local" class="nav-link">Local</a>
          </li>
          <li class="nav-item">
            <a href="evento" class="nav-link">Evento</a>
          </li>
        </ul>
      </header>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style>
.container header img {
  margin-right: 25px;
  width: 72px;
  height: 72px;
}
.container header ul {
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;
}
.container header ul li .nav-link {
  color: #5b2a00;
  font: bold;
}
.container header ul li .nav-link.active {
  background-color: #ff9b2d;
}
</style>