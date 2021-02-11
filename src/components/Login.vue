<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
     Never share your username or password with anyone.
    </p>
    <h3 class="row1">      
      Username:
      <form>
        <input type="text" name="username" class="row1">
      </form>    
    </h3>
    <h3 class="row2">      
      Password:
      <form>
        <input type="password" name="password" class="row2">
      </form>    
    </h3>
    <h3 class="row3">      
      <form>
        <input type="button" name="login" class="row3" value="Login" id="button">
      </form>    
    </h3>
  </div>
</template>

<script>

export default {
  name: 'Login',
  props: {
    msg: String
  },  
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 80px 100px;
}
div{
  border:10px solid #fff ;
  margin: 100px 400px;
}
.row1, .row2{
  align-self: center;
  display: flex;
}
input{
  margin-left:15px;
}
#button {
  margin: 0px;
}
</style>
