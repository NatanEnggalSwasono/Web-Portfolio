<template>
  <h2><span>About</span> Me</h2>
  <div class="about-content">
    <img src="../assets/Obito.png" alt="">
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Est quis consectetur optio quia eaque quam. Possimus, ducimus. Quam reprehenderit suscipit aspernatur tempora odit temporibus quidem commodi delectus sapiente quo. Ipsam possimus ratione dolorem fugit, quod blanditiis doloremque quo tempore eum tenetur consequatur, hic voluptates deserunt fugiat molestias commodi aliquam iusto error labore maxime asperiores quam neque ex quae. A eos odit obcaecati quis explicabo soluta esse incidunt, minima laudantium, nisi reiciendis itaque nulla ratione. Rem delectus similique, id, sequi unde asperiores vitae error fugiat numquam alias minima vel autem atque, tempora quasi inventore iusto temporibus adipisci reiciendis quia! Magnam dolores hic at repudiandae, minima molestiae aut laborum dignissimos harum maxime, facere tempora suscipit aliquam similique nobis ut nesciunt iure. Dolorem, alias temporibus vel tempore eum consequatur inventore neque, aliquam accusamus, fugit dolores odit non necessitatibus voluptatum similique porro. Harum in, eos sint ad inventore cumque. Ut optio sit quibusdam. Perspiciatis necessitatibus harum fuga error id iure quae molestiae expedita nobis sit consequuntur esse enim culpa optio doloribus accusantium, recusandae quam unde officiis, voluptates deserunt. Unde doloribus inventore deleniti rerum delectus dolore nemo nam dicta perferendis enim.</p>
  </div>
</template>

<script>
export default {
  name: "AboutMe"
}
</script>

<style scoped>
h2 {
  text-align: center;
  font-size: 2em;
  margin-top: 60px;
}
h2 span {
  color: #42b983;
}
.about-content {
  display: flex;
  padding: 0 100px;
}
.about-content img {
  flex: 1;
  margin: auto;
  padding: 30px;
  max-width: 350px;
}
.about-content p {
  font-size: 1.2em;
  flex: 1.5;
  text-align: right;
}
</style>