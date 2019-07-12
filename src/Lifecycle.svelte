<script>
  import { onMount } from "svelte";
  let time = 0;

  onMount(() => {
    setInterval(() => {
      time += 1;
    }, 1000);
  });
</script>

{time}s
