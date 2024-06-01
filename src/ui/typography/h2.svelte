<script lang="ts">
  export let underline: boolean = false
</script>

<h2
class:border-b={underline}
  class="scroll-m-20 pb-2 text-3xl font-semibold tracking-tight transition-colors first:mt-0">
  <slot />
</h2>
