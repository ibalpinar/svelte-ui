<script>
   let count1 = 0
   let count2 = 0
   function increment() {
      count1 += 1
   }
   function increment2() {
      count2 += 1
   }
</script>
<button on:click={increment}>Clicks {count1}</button>
<button on:click={increment2}>Clicks {count2}</button>

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