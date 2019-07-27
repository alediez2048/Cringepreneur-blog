<template>
  <transition appear name="v--mask">
    <footer v-once class="blog__footer">
      <div class="signature cosmicjs">
        Proudly powered by <a href="https://www.latindigital.io" target="_blank">Latin Digital</a>
      </div>
    </footer>
  </transition>
</template>

<script>
export default { name: 'blog-footer' }
</script>
