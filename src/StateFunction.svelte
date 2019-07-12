<script>
  let count = 0;

  function increase() {
    count += 1;
  }

  function decrease() {
    count += 1;
  }
</script>

<button on:click={increase}>increase</button>
<button on:click={decrease}>decrease</button>
{count}
