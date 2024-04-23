<script>
   let name = 'Resumex';
   let src = 'https://picsum.photos/350/200';
   let pString = 'This is a <strong>paragraph</strong> string';
</script>

<img {src} alt={`random image for ${name}`}>

<h1>Hello {name.toUpperCase()}!</h1>

<p>{@html pString}</p>

<style>
   h1 {
      color: #333;
      font-size: 2em;
      text-align: center;
   }
</style>
