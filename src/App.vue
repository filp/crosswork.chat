<template>
  <div class="root">
    <div class="banner text-center">
      We're still building this page. More details coming soon!
    </div>
    <div class="app container">
      <div class="row">
        <header class="text-center">
          <h1 class="branding">
            crosswork
          </h1>
          <p class="branding-subtext">
            Remote workers community
          </p>
        </header>
      </div>
    </div>
    <div class="container">
      <router-view/>
    </div>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style lang="scss">
// Vars & bootstrap overrides
@import "~styles/_vars";

// Include the bits of bootstrap we care about
@import "~bootstrap-sass/assets/stylesheets/bootstrap/_variables";
@import "~bootstrap-sass/assets/stylesheets/bootstrap/_mixins";
@import "~bootstrap-sass/assets/stylesheets/bootstrap/_normalize";
@import "~bootstrap-sass/assets/stylesheets/bootstrap/_print";
@import "~bootstrap-sass/assets/stylesheets/bootstrap/_scaffolding";
@import "~bootstrap-sass/assets/stylesheets/bootstrap/_type";
@import "~bootstrap-sass/assets/stylesheets/bootstrap/_grid";
@import "~bootstrap-sass/assets/stylesheets/bootstrap/_responsive-utilities";

// Global styles
@import "~styles/global"
</style>
