<template>
  <footer>
    <p>Questions? Call xxx xxx xxx</p>
    <section class="links">
      <ul class="links-list">
        <li><a href="">FAQ</a></li>
        <li><a href="">Investor Relations</a></li>
        <li><a href="">Ways to Watch</a></li>
        <li><a href="">Corporate Information</a></li>
        <li><a href=""> Originals</a></li>
      </ul>
      <ul class="links-list">
        <li>Account</li>
        <li>Redeem Gift Cards</li>
        <li>Privacy</li>
        <li>Speed Test</li>
      </ul>
      <ul class="links-list">
        <li>Help Center</li>
        <li>Jobs</li>
        <li>Terms of Use</li>
        <li>Contact Us</li>
        <li>Buy Gift Cards</li>
      </ul>
      <ul class="links-list">
        <li>Media Center</li>
        <li>Privacy</li>
        <li>Cookie Preferences</li>
        <li>Legal Notices</li>
      </ul>
    </section>
    <p>&copy; CopyRight Hola 2020 All Rights Reserved.</p>
  </footer>
</template>

<script>
export default {
  name: "Footers"
};
</script>

<style>
footer {
  width: 100%;
  opacity: 1;
  /* border-radius: 15px; */
  padding: 3rem;
  background: var(--third-color);
  color: var(--secondary-color);
}

footer p {
  text-align: center;
}

footer .links {
  display: flex;
  justify-content: space-around;
}

footer .links .links-list {
  list-style: none;
  line-height: 2;
}

footer .links .links-list a {
  text-decoration: none;
  color: var(--secondary-color);
}

footer p:nth-of-type(2) {
  margin-top: 2rem;
  font-weight: 400;
}
</style>
