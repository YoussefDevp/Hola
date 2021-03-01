<template>
  <div class="about">
    <div class="container">
      <nav id="nav-bar">
        <a class="logo" href="./">HOLA</a>
      </nav>

      <form>
        <h1>Sign In</h1>
        <input type="email" name="" id="" placeholder="Email or phone number" />
        <input type="password" placeholder="Password" />
        <button type="submit">
          Sign In
        </button>
        <div class="checkbox">
          <input type="checkbox" name="" id="" />
          <span>Remember me</span>
        </div>

        <a href="#">Need help?</a>
        <a href="#"> I forgot my password</a>
      </form>
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
      </footer>
    </div>
  </div>
</template>

<style lang="css" scoped>
.container {
  background: linear-gradient(
      180deg,
      rgba(0, 0, 0, 0.568),
      rgba(0, 0, 0, 0.568)
    ),
    url("../assets/header_img.jpg") center center/cover;
  display: flex;
  justify-content: space-between;
  align-items: center;
  flex-direction: column;
  padding: 1rem;
  height: 100%;
}

.container nav {
  width: 100%;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.container form {
  width: 450px;
  display: flex;
  flex-direction: column;
  padding: 4rem;
  border-radius: 5px;
  backdrop-filter: blur(2.5px);
  box-shadow: 0 8px 32px 0 rgb(0, 0, 0);
}

.container form h1 {
  margin-bottom: 1rem;
  text-align: center;
}

.container form #text {
  color: var(--secondary-color);
}

.container form input,
button {
  padding: 0.7rem 0.5rem;
  border: none;
  margin-bottom: 1rem;
  border-radius: 5px;
}
.checkbox span {
  color: #e7e7dec0;
  font-style: italic;
}
/* .container form input,button {

} */

.container form button {
  background-color: var(--primary-color);
  color: var(--secondary-color);
  font-weight: 700;
}

.container form button:hover {
  background-color: var(--secondary-color);
  color: var(--primary-color);
  transition: 0.3s ease-out;
  cursor: pointer;
}

.container form a {
  /* text-decoration:none; */
  color: var(--secondary-color);
}

.container footer {
  width: 100%;
  opacity: 0.7;
  border-radius: 15px;
}
</style>
