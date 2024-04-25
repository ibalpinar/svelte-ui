<script>
   let count = 0
   function increment() {
      count += 1
   }
</script>
<button on:click={increment}>Clicks {count}</button>

<style>
   button {
      background-color: rgb(149, 255, 0);
      color: #000000;
      padding: 1rem;
      border: none;
      border-radius: 0.5rem;
      cursor: pointer;
   }
</style>