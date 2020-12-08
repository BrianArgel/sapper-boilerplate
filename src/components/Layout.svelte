<script lang="ts">
</script>
<style>
  :global(*){
    box-sizing: border-box;
  }
  :global(:root){
    --color-background:  #f0f2f5;
  }

  .layout{
    width: 100%;
    min-height: 100vh;
    background-color: var(--color-background);
    display: flex;
  }
</style>



<svelte:head>
  <!-- Aquí va el título y las fuentes -->
</svelte:head>

<main class="layout">
  <slot></slot>
</main>