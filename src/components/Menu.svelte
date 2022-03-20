<script lang="ts">
  let expanded = false

  const toggle = (): void => {
    expanded = !expanded
  }

</script>

<div class="menubar">
  <svg viewBox="0 0 100 80" width="40" height="40" class="menubutton" on:click={toggle}>
    <rect class="menu_rect" y="0" width="100" height="20" rx="10"></rect>
    <rect y="30" width="100" height="20" rx="10"></rect>
    <rect y="60" width="100" height="20" rx="10"></rect>
  </svg>
</div>
<div class="menu {expanded ? 'menuexpanded': 'menucollapsed'}">
  <slot></slot>
</div>

<style>



</style>

