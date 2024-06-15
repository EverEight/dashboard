<script lang="ts">
  import { cn } from "$lib/utils";
  import type { HTMLAttributes } from "svelte/elements";
  type $$Props = HTMLAttributes<HTMLDivElement>;

  let className: $$Props["class"] = undefined;
  export { className as class };
</script>

<h2
  class={cn(
    "scroll-m-20 pb-2 text-3xl font-semibold tracking-tight transition-colors first:mt-0",
    className,
  )}>
  <slot />
</h2>
