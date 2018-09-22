<template>
  <section class="container">
    <div id="content">
      Hello
    </div>
  </section>
</template>

<script>
export default {}
</script>

<style>
.container {
  margin: 16px;
}

#content {
  width: 512px;
  height: 512px;
  display: flex;
  align-items: center;
  justify-content: center;
  color: #fff;
  position: relative;
  background: url('~/assets/background.jpg')
}

#content::after {
  width: 100%;
  height: 100%;
  content: '';
  display: block;
  position: absolute;
  background: rgba(0,0,0,0.2);
}
</style>
