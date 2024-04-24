<script>
   let name = 'Resumex';
   let src = 'https://picsum.photos/350/200';
   let src2 = 'https://picsum.photos/850/120';
   let pString = 'This is a <strong>paragraph</strong> string';
   let pImg = `This is a test image <img src='${src2}' />`;
</script>

<img {src} alt={`random image for ${name}`}>

<h1>Hello {name.toUpperCase()}!</h1>

<p>{@html pString}</p>

<p>{@html pImg}</p>

<style>
   h1 {
      color: #333;
      font-size: 2em;
      text-align: center;
   }
</style>
