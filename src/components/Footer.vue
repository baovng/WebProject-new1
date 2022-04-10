<template>
  <footer>
    <div>
    <span>&copy;</span> 2023 by Web Project Group
    </div>
  </footer>
</template>

<script>
export default {

}
</script>

<style>
footer{
  position: relative;
  height: 20vh;
  background-color: white;
}
footer>div{
  color:#2f2e2e;
  position: absolute;
  bottom:0;
  top:50%;
  left:50%;
  transform: translate(-50%,-50%);
}
</style>