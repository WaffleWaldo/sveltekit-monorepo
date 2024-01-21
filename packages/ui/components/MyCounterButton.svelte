<script lang="ts">
  let count = 0;

  function handleClick() {
    count += 1;
  }
</script>

<button class="btn btn-sm variant-filled" on:click={handleClick}>
  clicks: {count}
</button>
