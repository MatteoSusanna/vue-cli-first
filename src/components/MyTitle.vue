<template>
  <div class="box">
    <h1>La mia prima app con Vue CLI!</h1>
  </div>
</template>

<script>
export default {
  name: 'MyTitle',
}
</script>

<style scoped>

.box{
    background-color: #0f0e17;
    width: 600px;
    margin: auto;
    border-radius: 25px;
    padding: 5px
}

.box:hover{
    background-color: #ff8906;
}

h1{
    color:#ff8906;
}

h1:hover{
    color:#0f0e17
}

</style>



