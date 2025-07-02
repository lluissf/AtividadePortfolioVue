<script setup>
import TheWelcome from '../components/TheWelcome.vue'
</script>

<template>
  <main>
    <section class="banner">
      <div class="imagem">
        <img src="/images/iudi.jpg" style="width: 200px;" alt="Foto do John" />
      </div>
      <div class="texto">
        <h1>Contact</h1>
        <p>
          Aaaaaaaaaaaalô
          Você tá me escutando?
          Você quer ganhar o quê?
          Playstation 2

          4002-8922


          É o funk do Yudi que vai dar playstation 2
          O 4002-8922 é o funk do Yudi que vai dar playstation 2

          O vem curtindo o som no talo, vem curtindo o batidão
          Novo som do japonês,que arrasta multidão
          Mas esse som é pra criança, pro adulto ou pro
          velhinho.
          Me diz, você ta dançando é o funk do Yudinho.

        </p>
        <p><button class="whatsapp"><span class="fa-brands fa-whatsapp"></span> +55 11 4002 8922</button></p>
      </div>
    </section>
  </main>
</template>
<style scoped>
section.banner {
  text-align: center;
  padding: 0 5% 0 5%;
}

section.banner h1 {
  font-weight: bold;
  font-size: 2rem;
  margin: 10px 0 10px 0;
}

section.banner p button {
  background: #ff6464;
  border: none;
  color: #ffffff;
  display: inline-block;
  margin: 10px 0 50px;
  padding: 5px 10px 5px 10px;
  font-size: 1.5rem;
}

section.posts {
  background: #edf7fa;
  padding: 10px;
}

section.posts ul li {
  background: white;
  padding: 15px;
  margin: 12px 0px 12px 0px;
}

section.posts ul li h3 {
  font-weight: bold;
  font-size: 1.3rem;
  margin: 0 0 15px;
}

section.posts ul li p {
  font-size: 1rem;
  margin: 15px 0px 15px 0px;
}

section.works {
  padding: 20px 10px 20px 10px;
}

section.works ul li {
  margin: 10px 0px 10px 0px;
}

section.works ul li h3 {
  font-weight: bold;
  font-size: 1.4rem;
  line-height: 130%;
}

section.works ul li p.info {
  color: #8695a4;
}

section.works ul li p {
  margin: 10px 0;
}

section.works ul li p.info span {
  color: white;
  background: #142850;
  font-weight: bold;
  padding: 5px 10px;
  border-radius: 16px;
}

section.works ul {
  border-bottom: 1px solid #e0e0e0;
}
 
</style>