<template>
  <div class="result">
      <p id="score">Time is {{ score }} milliseconds </p>
  </div>
</template>

<script>
export default {

    props: ['score']

}
</script>

<style>
.result{
    border-radius: 20px;
    background: blueviolet;
    text-align: center;
    padding: 100px 0;
    margin: 40px auto;
    color: white;
    width: 400px;
    height: 40px;
    
}
#score{
    font-size: 20px;
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    
}

</style>