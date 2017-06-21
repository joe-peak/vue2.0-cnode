<template>
  <header id="catogory">
    <mt-navbar v-model="selected" >
      <mt-tab-item style='font-size:60px;' id="1">全部</mt-tab-item>
      <mt-tab-item id="2">精华</mt-tab-item>
      <mt-tab-item id="3">分享</mt-tab-item>
      <mt-tab-item id="4">问答</mt-tab-item>
      <mt-tab-item id="5">招聘</mt-tab-item>
    </mt-navbar>
  </header>
</template>

<script>
export default {
  name: 'hello',
  data () {
    return {
      selected: 3
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

a {
  color: #42b983;
}

#catogory{
  border:1px solid red;
}
#catogory .mint-tab-item-label
{
  font-size: 66px;
}
</style>
