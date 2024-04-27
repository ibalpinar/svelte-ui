<script>
   let count1 = 0
   let count2 = 0
   let warningStr = `Warning: You are about to exceed the limit of 10 clicks`;
   function increment() {
      if (count1 >= 10)
         return;
      count1 += 1;
   }
   function increment2() {
      count2 += 1;
   }
</script>
<button on:click={increment}>Clicks {count1}</button>
<h2>{count1}</h2>
<h3>{count1 > 10 ? warningStr : ''}</h3>
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