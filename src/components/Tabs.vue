<template>
  <div class="row">
    <div class="medium-10 medium-offset-1 columns">
      <h1>{{ msg }}</h1>
      <ul class="tabs" data-tabs id="deeplinked-tabs">
        <li class="tabs-title is-active"><a href="#panel1d" aria-selected="true">Tab 1</a></li>
        <li class="tabs-title"><a href="#panel2d">Tab 2</a></li>
        <li class="tabs-title"><a href="#panel3d">Tab 3</a></li>
      </ul>
    
      <div class="tabs-content" data-tabs-content="deeplinked-tabs">
        <div class="tabs-panel is-active" id="panel1d">
          <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
        </div>
        <div class="tabs-panel" id="panel2d">
          <p>Vivamus hendrerit arcu sed erat molestie vehicula. Sed auctor neque eu tellus rhoncus ut eleifend nibh porttitor. Ut in nulla enim. Phasellus molestie magna non est bibendum non venenatis nisl tempor. Suspendisse dictum feugiat nisl ut dapibus.</p>
        </div>
        <div class="tabs-panel" id="panel3d">
          <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  mixins: [
    // eslint-disable-next-line
    require('@/mixins/foundation'),
  ],
  name: 'tabs',
  data() {
    return {
      msg: 'Tabs',
    };
  },
};
</script>

<style lang="scss" scoped>
</style>
