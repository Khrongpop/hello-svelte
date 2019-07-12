<script>
  let input = "";
</script>

<input bind:value={input} />
{#if input >= 80}A{:else if input >= 70}B{:else}C{/if}
