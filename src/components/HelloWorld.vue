<template>
  <div>
    <h1>hello</h1>
    <h2>{{ msg }}</h2>
    <h3>{{ test }}</h3>
    <ul class="list">
      <li v-for="item in ax" :key="item">
        <a href="#">
          {{ item}}
        </a>
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String,
    test: Number,
    ax: Array,
  },
};
</script>

<style scoped>
h1 {
  margin: 40px 0 0;
  text-transform: uppercase;
  font-weight: 300;
  letter-spacing: 1.1px;
  color: #42b983;
  font-style: italic;
}

a {
  color: white;
  text-decoration: none;
  font-size: 18px;
  width:200px ;
  background-color: #42b983;
  padding: 10px 15px;
  margin: 10px;
}

ul{
  list-style: none;
}

.list {
  display: flex;
  flex-direction: column;
  gap: 20px;


}

li{
  margin: 10px;
}


</style>
