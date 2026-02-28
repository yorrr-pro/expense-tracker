
<script>
  export let variant = "solid";
  export let type = "button";
  export let className = "";
</script>

<button
  type={type}
  class={`px-4 py-2 rounded-md text-sm focus:outline-none focus:ring ${
    variant === "outline" ? "border" : "shadow"
  } ${className}`}
>
  <slot />
</button>

<style>
  /* fallback styles if Tailwind isn't present */
  :global(button) {
    font-family: system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial;
  }
</style>