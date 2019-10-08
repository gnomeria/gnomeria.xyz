<template>
  <div class="main stack">
    <header class="hero">
      <nav class="demo stack">
        <a href="/" class="brand">
          <button class="border--maroon">ROOT</button>
        </a>

        <div class="menu">
          <a href="/article" class="pseudo button icon-picture">Article</a>
        </div>
      </nav>
    </header>
    <nuxt class="visual flex one-800 pseudo nuxt-content" />
  </div>
</template>

<script>
export default {
  data() {
    return {}
  }
}
</script>
