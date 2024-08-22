<template>
    <h2>My <span>Projects</span></h2>
    <div class="wrapper">
      <div class="box-area">
        <div class="box-content">
          <img src="../assets/obito.jpg" alt="" />
            <div class="overlay">
              <h3>lorem ipsum</h3>
              <p>
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Quod
                consectetur totam enim. Perspiciatis dolore odit labore,
                voluptate placeat perferendis repellat rerum ipsum repudiandae
                assumenda molestiae aspernatur odio suscipit id officia?
              </p>
              <a href="#">More</a>
            </div>
        </div>
        <div class="box-content">
          <img src="../assets/obito.jpg" alt="" />
            <div class="overlay">
              <h3>lorem ipsum</h3>
              <p>
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Quod
                consectetur totam enim. Perspiciatis dolore odit labore,
                voluptate placeat perferendis repellat rerum ipsum repudiandae
                assumenda molestiae aspernatur odio suscipit id officia?
              </p>
              <a href="#">More</a>
            </div>
        </div>
        <div class="box-content">
          <img src="../assets/obito.jpg" alt="" />
            <div class="overlay">
              <h3>lorem ipsum</h3>
              <p>
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Quod
                consectetur totam enim. Perspiciatis dolore odit labore,
                voluptate placeat perferendis repellat rerum ipsum repudiandae
                assumenda molestiae aspernatur odio suscipit id officia?
              </p>
              <a href="#">More</a>
            </div>
        </div>
      </div>
    </div>
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
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
h2 {
  text-align: center;
  font-size: 2em;
  margin-top: 60px;
}
span {
  color: #42b983;
}
.wrapper {
  padding: 10px 10%;
}
.box-area {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  grid-gap: 40px;
  margin-top: 50px;
}
.box-content {
  border-radius: 10px;
  position: relative;
  overflow: hidden;
  box-shadow: 5px 5px 15px rgba(0, 0, 0, 0.5);
  cursor: pointer;
}
.box-content img {
  width: 100%;
  border-radius: 10px;
  display: block;
  transition: 0.5s;
}
.overlay {
    height: 0;
    width: 100%;
    background: linear-gradient(transparent, #1c1c1c 58%);
    border-radius: 10px;
    position: absolute;
    left: 0;
    bottom: 0;
    overflow: hidden;
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
    padding: 0 40px;
    text-align: center;
    font-size: 14px;
    transition: height 0.5s;
}
.overlay h3 {
    font-weight: 500;
    margin-bottom: 5px;
    margin-top: 80%;
    font-size: 30px;
    letter-spacing: 2px;
}
.overlay a {
    margin-top: 10px;
    color: #262626;
    text-decoration: none;
    font-size: 14px;
    background: #fff;
    border-radius: 50px;
    text-align: center;
    padding: 5px 15px;
}

.box-contentLhover img {
    transform: scale(1.2);
}

.box-content:hover .overlay {
    height: 100%;
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