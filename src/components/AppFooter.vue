<template>
  <footer class="footer">
    <div class="footer__copyright">KSA Izegem © 2021</div>

    <div class="footer__socials">
      <a href="https://www.facebook.com/ksaizegem" rel="noopener" target="_blank">
        <img src="/img/facebook.webp" alt="Facebook icoontje" />
      </a>

      <a href="https://www.instagram.com/ksaizegem" rel="noopener" target="_blank">
        <img src="/img/instagram.webp" alt="Instagram icoontje" />
      </a>
    </div>
  </footer>
</template>

<style lang="scss" scoped>
.footer {
  @include width-container;
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 1rem;

  &__socials {
    img {
      height: 2rem;
      width: auto;
    }
  }
}
</style>