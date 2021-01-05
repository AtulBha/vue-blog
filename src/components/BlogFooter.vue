<template>
  <transition appear name="v--mask">
    <footer v-once class="blog__footer">
      <div class="signature cosmicjs">
        Checkout<a href="https://github.com/AtulBha" target="_blank">my GitHub</a>
      </div>
    </footer>
  </transition>
</template>

<script>
export default { name: 'blog-footer' }
</script>
