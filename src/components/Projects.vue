<template>
    <h2>Projects</h2>
    <div class="content">
      <img src="../assets/obito.jpg" alt="">
      <div class="content-project">
        <h3>Lorem Ipsum</h3>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Tenetur repellendus ratione eos laborum accusamus sint est nemo, sit ab qui expedita asperiores excepturi praesentium, minima, sunt dolorem ullam reiciendis vitae!</p>
        <ul class="technologies">
          <li>Vue Js</li>
          <li>JavaScript</li>
          <li>HTML</li>
          <li>CSS</li>
        </ul>
        <a href="">View Project</a>
      </div>
    </div>
    <div class="content">
      <img src="../assets/obito.jpg" alt="">
      <div class="content-project">
        <h3>Lorem Ipsum</h3>
        <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Perferendis quasi ex quos, perspiciatis quidem sit minus nulla, harum eos, saepe accusantium corporis mollitia vero? Sapiente exercitationem impedit inventore dolorum quas?</p>
        <ul class="technologies">
          <li>Vue Js</li>
          <li>JavaScript</li>
          <li>HTML</li>
          <li>CSS</li>
        </ul>
        <a href="">View Project</a>
      </div>
    </div>
    <div class="content">
      <img src="../assets/obito.jpg" alt="">
      <div class="content-project">
        <h3>Lorem Ipsum</h3>
        <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Atque eum qui totam eveniet corrupti eius consequuntur, delectus deserunt nostrum voluptate iure dolore perspiciatis magni nisi commodi pariatur culpa aliquam rerum!</p>
        <ul class="technologies">
          <li>Vue Js</li>
          <li>JavaScript</li>
          <li>HTML</li>
          <li>CSS</li>
        </ul>
        <a href="">View Project</a>
      </div>
    </div>
</template>

<script>
export default {
  name: "Projects"
}
</script>

<style scoped>
h2 {
  text-align: center;
  font-size: 2em;
  margin-top: 60px;
}
.content {
  display: flex;
  gap: 10px;
  height: 250px;
  margin: 10px 100px 30px;
  border: 1px solid #42b983;
  
}
.content:hover {
  box-shadow: rgba(14, 223, 94, 0.12) 0px 2px 4px 0px, rgba(6, 241, 104, 0.32) 0px 2px 16px 4px;
}
img {
  height: auto;
  object-fit: cover;
  flex: 1;
}
.content-project {
 flex: 3;
 padding: 5px 10px;
}
.content-project .technologies {
  list-style-type: nonee;
  padding: 0;
  margin: 20px 0;
}
.content-project .technologies li {
  display: inline;
  margin-right: 10px;
  padding: 5px 10px;
  color: #fff;
  background: #42b983;
  border-radius: 3px;
}

.content-project a {
  text-decoration: none;
  color: #42b983;
  font-weight: bold;
}
</style>