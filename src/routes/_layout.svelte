<script lang="ts">
  import Nav from '../components/Nav.svelte';

  export let segment: any;
</script>

<Nav segment="{segment}" />

<main>
  <slot />
</main>

<style lang="scss" global>
  @import '../styles/global.scss';
  main {
    position: relative;
    max-width: 56em;
    background-color: white;
    padding: 2em;
    margin: 0 auto;
    box-sizing: border-box;
  }
</style>
