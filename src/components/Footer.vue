<template>
  <footer class="footer">
    <div class="footer-container">
      <p>Monte seu hamburger &copy; 2022</p>
    </div>
  </footer>
</template>
<script>
export default {
  name: "Footer",
};
</script>
<style scooped>
.footer {
  width: 100%;
  height: 33vh;
  position: relative;
}
.footer-container {
  width: 100%;
  height: 150px;
  background: #222;
  color: #fcba03;
  position: absolute;
  bottom: 0;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}
</style>
