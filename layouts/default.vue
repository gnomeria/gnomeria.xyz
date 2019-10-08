<template>
  <div>
    <nav class="demo">
      <a href="#" class="brand"></a>
      <span>ROOT</span>

      <div class="menu">
        <a href="#" class="pseudo button icon-picture">Demo</a>
        <a href="#" class="button icon-puzzle">Plugins</a>
      </div>
    </nav>
  </div>
</template>

<script>
export default {
  data() {
    return {
      clipped: false,
      drawer: true,
      fixed: false,
      items: [
        { icon: 'apps', title: 'Welcome', to: '/' },
        { icon: 'bubble_chart', title: 'Inspire', to: '/inspire' }
      ],
      miniVariant: false,
      right: true,
      rightDrawer: false,
      title: 'Vuetify.js'
    }
  }
}
</script>
