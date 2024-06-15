<script lang="ts">
  import { cn } from "$lib/utils";
  import type { HTMLAttributes } from "svelte/elements";
  type $$Props = HTMLAttributes<HTMLDivElement>;

  let className: $$Props["class"] = undefined;
  export { className as class };
</script>

<ul class={cn("my-6 ml-6 list-disc [&>li]:mt-2", className)}>
  <slot />
</ul>
