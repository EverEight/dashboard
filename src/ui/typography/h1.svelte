<script lang="ts">
  import { cn } from "$lib/utils";
  import type { HTMLAttributes } from "svelte/elements";
  type $$Props = HTMLAttributes<HTMLDivElement>;

  let className: $$Props["class"] = undefined;
  export { className as class };
</script>

<h1 class={cn("scroll-m-20 text-4xl font-extrabold tracking-tight lg:text-5xl", className)}>
  <slot />
</h1>
