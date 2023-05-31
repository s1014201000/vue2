<template>
  <body class="body">
  <img src="" alt="">
  <h1 class="h1">巴哈姆特</h1>
  <form class="form">
    <p class="p">巴哈姆特 </p>
    <p>最棒的社群網站</p>
    <input class="ll" type="text" id="username" name="帳號"><br>
    <input class="ll" type="password" id="password" name="密碼"><br>

    <input class="submit" type="submit" value="登入" style="color: white">
  </form>

  </body>
</template>

<script>
export default {

};
</script>


<style scoped>
.body{
  background: #cccccc;
}
.h1{
  font-size: 34px;
  font-style: italic;
  font-weight: bold;
  color: white;
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  background: darkcyan;
}
.form {
  width: 300px;
  height: 300px;
  margin: 100px auto 0;
  border: 1px solid black;
  text-align: center; /* 水平置中 */
  display: flex;
  flex-direction: column;
  justify-content: center; /* 垂直置中 */
  align-items: center; /* 垂直置中 */
  background-color: white; /* 添加底色 */
  padding: 20px;
}
.p{
  font-size: 32px;
  font-style: italic;
  font-weight: bold;
  color: gray;
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
.submit{
  background: rgba(17,128,130,0.93) ;
  border: 2px solid #ccc;
  padding: 15px;
  border-radius: 10px;
  width: 280px;
  margin: 0 auto;
}

.ll{
  margin-top: -10px;
  border: 2px solid #ccc;
  padding: 5px;
  border-radius: 300px;
  width: 280px;
}
.ss{

}
</style>