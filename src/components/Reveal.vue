<template>
  <div class="row">
    <div class="medium-10 medium-offset-1 columns">
      <h1>{{ msg }}</h1>
      <div class="reveal" id="exampleModal1" data-reveal>
        <h1>Awesome. I Have It.</h1>
        <p class="lead">Your couch. It is mine.</p>
        <p>I'm a cool paragraph that lives inside of an even cooler modal. Wins!</p>
        <button class="close-button" data-close aria-label="Close modal" type="button">
          <span aria-hidden="true">&times;</span>
        </button>
      </div>
      <p><a data-open="exampleModal1">Click me for a modal</a></p>
    </div>
  </div>
</template>

<script>
export default {
  mixins: [
    // eslint-disable-next-line
    require('@/mixins/foundation'),
  ],
  name: 'reveal',
  data() {
    return {
      msg: 'Reveal',
    };
  },
};
</script>

<style lang="scss" scoped>
</style>
