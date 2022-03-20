<script lang="ts">
export let url : string
</script>

<div on:click={() => window.location.href = url}>
  <slot></slot>
</div>