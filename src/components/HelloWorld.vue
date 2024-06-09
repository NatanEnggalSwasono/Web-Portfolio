<template>
  <div class="hello">
    <h1>Hi, I'm Natan Swasono</h1>
    <h3>Website Developer</h3>
    <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Dolores sapiente sint ullam cum maiores iusto consequatur atque soluta illum enim assumenda dolorem quaerat perferendis, minima eaque mollitia, maxime accusamus sed.</p>
    <div class="hire">
      <a href="">Hire Me</a>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.hello {
  padding-top: 80px;
  flex: 1.3;
}
h1 {
  font-size: 3em;
  margin-bottom: 10px;
}
h3 {
  font-size: 1.6em;
  color: #42b983;
  margin-top: 0;
}
p {
  font-size: 20px;
  line-height: 1.3em;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
.hire {
  padding: 30px 0;
}
a {
  font-size: 16px;
  font-weight: bold;
  text-decoration: none;
  color: #fff;
  padding: 12px 32px;
  border: 1px solid #42b983;
  border-radius: 7px;
}
a:hover {
  background: #42b983;
}
</style>
