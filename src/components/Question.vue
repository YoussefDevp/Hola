<template>
  <section class="Questions">
    <h1 class="primary_heading">Frequently Asked Questions</h1>
    <h3>What is HOLA?</h3>
    <!-- <p>HOLA is a streaming service that offers a wide variety of award-winning TV shows, movies, anime, documentaries, and more on thousands of internet-connected devices.

        <p>You can watch as much as you want, whenever you want without a single commercial – all for one low monthly price. There's always something new to discover and new TV shows and movies are added every week!</p> -->
    <h3>How much does HOLA cost?</h3>
    <!-- <p>Watch HOLA on your smartphone, tablet, Smart TV, laptop, or streaming device, all for one fixed monthly fee. Plans range from EUR7.99 to EUR15.99 a month. No extra costs, no contracts.</p> -->

    <h3>Where can I watch?</h3>
    <!-- <p>Watch anywhere, anytime, on an unlimited number of devices. Sign in with your HOLA account to watch instantly on the web at HOLA.com from your personal computer or on any internet-connected device that offers the HOLA app, including smart TVs, smartphones, tablets, streaming media players and game consoles. -->

    <!-- <p>You can also download your favorite shows with the iOS, Android, or Windows 10 app. Use downloads to watch while you're on the go and without an internet connection. Take HOLA with you anywhere.</p> -->
    <h3>How do I cancel?</h3>
    <!-- <p>HOLA is flexible. There are no pesky contracts and no commitments. You can easily cancel your account online in two clicks. There are no cancellation fees – start or stop your account anytime.</p> -->

    <h3>What can i watch on HOLA</h3>
    <!-- <p>HOLA has an extensive library of feature films, documentaries, TV shows, anime, award-winning HOLA originals, and more. Watch as much as you want, anytime you want.</p> -->

    <p>
      Ready to watch? Enter your email to create or restart your membership.
    </p>

    <form>
      <input class="email input" type="email" placeholder="Email address" />
      <button class="btn" type="submit">GET STARTED</button>
    </form>
  </section>
</template>

<script>
export default {
  name: "Question"
};
</script>

<style scoped>
.Questions {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  background: var(--third-color);
  padding: 3rem;
}

.Questions h1 {
  margin-bottom: 2rem;
}

.Questions h3 {
  background: #e7e7de;
  color: var(--third-color);
  padding: 1rem 2rem;
  width: 500px;
  margin: 0 auto;
  margin-bottom: 1rem;
  border-radius: 5px;
  box-shadow: 10px 10px 28px -19px rgba(0, 0, 0, 0.75);
}
</style>
