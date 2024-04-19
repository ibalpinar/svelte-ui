<script>
   let countDemo = 0
   const increment = () => {
     countDemo += 1
   }
 </script>

 <button on:click={increment}>
   countDemo is {countDemo}
 </button>

   <style>
      button {
         background-color: #ff3e00;
         color: white;
         padding: 0.5em 1em;
         border: none;
         border-radius: 0.5em;
         cursor: pointer;
         font-size: 1em;
         margin: 1em;
      }
   </style>
