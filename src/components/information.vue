<template>
  <div class="cards">
    <div class="content">
      <h1 class="primary_heading">{{ title }}</h1>
      <p>{{ description }}</p>
    </div>
    <img :src="img" alt="" srcset="" />
  </div>
</template>

<script>
export default {
  name: "Information",
  props: {
    title: String,
    description: String,
    img: String
  }
};
</script>

<style scoped>
.card-section {
  padding: 1rem;
  background: var(--third-color);
  display: flex;
  flex-direction: column;
}

.card-section hr {
  width: 90%;
  margin: 0 auto;
  padding: 0.1rem;
}

.card-section .cards {
  height: 500px;
  display: flex;
  justify-content: center;
  align-items: center;
}

.card-section .cards .content {
  width: 50%;
  margin-right: 2rem;
}

.card-section .cards .content h1,
p {
  color: var(--secondary-color);
}

.card-section .cards .content h1 {
  margin-bottom: 2rem;
}

.card-section .cards .content p {
  font-size: 1.5rem;
  font-weight: 400;
}

.card-section .cards img {
  width: 600px;
}
</style>
