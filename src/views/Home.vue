<template>
  <div class="home">
    <header id="header">
      <nav id="nav">
        <a class="logo" href="./home">HOLA</a>
        <a href="./login">Sign in</a>
      </nav>
      <h1 class="primary_heading">Unlimited movies, TV shows, and more.</h1>

      <h2>Watch anywhere. Cancel anytime.</h2>

      <p class="paragraph">
        Ready to watch? Enter your email to create or restart your membership.
      </p>

      <form>
        <input class="email input" type="email" placeholder="Email address" />
        <button onclick="login()" class="btn" type="submit">GET STARTED</button>
      </form>
    </header>

    <hr />

    <section class="card-section">
      <div class="cards">
        <div class="content">
          <h1 class="primary_heading">Enjoy on your Computer Screen</h1>
          <p>You can watch on your computer screen by an easy cliking.</p>
        </div>
        <img src="../assets/undraw_monitor_iqpq.svg" alt="" srcset="" />
      </div>
      <hr />
      <div class="cards">
        <div class="content">
          <h1 class="primary_heading">Download your shows to watch offline.</h1>
          <p>Watch on Smart TVs , smartphone, tablet and more.</p>
        </div>
        <img src="../assets/undraw_Mobile_app_p3ts.svg" alt="" srcset="" />
      </div>
      <hr />
      <div class="cards">
        <div class="content">
          <h1 class="primary_heading">
            Save your favorites easily and always have something to watch.
          </h1>
          <p>
            Stream unlimited movies and TV shows on your phone, tablet, laptop,
            and TV without paying more...
          </p>
        </div>
        <img src="../assets/undraw_Devices_re_dxae.svg" alt="" srcset="" />
      </div>
    </section>

    <hr />

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
    <hr />

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
  </div>
</template>

<script></script>

<style lang="scss">
:root {
  --primary-color: #008891;
  --secondary-color: #ffffff;
  --third-color: #0c1216;
}

input:focus,
button:focus {
  outline: none;
}

.login {
  text-decoration: none;
  background: var(--primary-color);
  color: var(--secondary-color);
  padding: 0.5rem 2rem;
  border-radius: 15px;
  font-weight: 600;
}

.primary_heading {
  width: 700px;
  font-size: 3rem;
  color: var(--secondary-color);
  font-weight: 600;
}

/*.paragraph {

}
*/

.email {
  width: 250px;
  padding: 1rem;
  border-top-left-radius: 25px;
  border-bottom-left-radius: 25px;
  border: none;
}

.btn {
  width: 150px;
  padding: 1rem 0.5rem;
  border-top-right-radius: 25px;
  border-bottom-right-radius: 25px;
  border-top-left-radius: 0px;
  border-bottom-left-radius: 0px;
  border: none;
  background-color: var(--primary-color);
  color: var(--secondary-color);
  font-weight: 600;
  position: relative;
  left: -5px;
}

.input::placeholder {
  color: var(--primary-color);
  font-style: italic;
}

.btn:hover {
  background: var(--secondary-color);
  color: var(--primary-color);
  transition: 0.3s ease-out;
  cursor: pointer;
}

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-size: 14px;
  font-family: Arial, Helvetica, sans-serif;
  color: white;
}

/** HEADER SECTION */

header {
  background: linear-gradient(
      180deg,
      rgba(0, 0, 0, 0.568),
      rgba(0, 0, 0, 0.568)
    ),
    url("../assets/header_img.jpg") center center/cover;
  height: 80vh;
  display: flex;
  flex-direction: column;
  align-items: center;
  padding: 1rem;
}

header nav {
  width: 100%;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.logo {
  font-size: 3rem;
  color: var(--primary-color);
  text-shadow: 2px 2px 6px rgba(0, 0, 0, 0.5);
  text-decoration: none;
  font-weight: 600;
}

header nav a:nth-of-type(2) {
  text-decoration: none;
  background: var(--primary-color);
  color: var(--secondary-color);
  padding: 0.5rem 2rem;
  border-radius: 15px;
  font-weight: 600;
}

header nav a:hover:nth-of-type(2) {
  background: var(--secondary-color);
  color: var(--primary-color);
  transition: 0.3s ease-out;
}

header > h1 {
  margin-top: 10rem;
  font-size: 3rem;
  width: 30%;
  text-align: center;
}

header h1,
h2,
p {
  color: var(--secondary-color);
}

header h2,
p {
  line-height: 2.3;
  font-weight: 600;
}

header p {
  margin-bottom: 1rem;
}

/** INFORMATION SECTION  **/

hr {
  padding: 0.2rem;
  border: none;
  background: var(--primary-color);
}

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

/** QUESTION SESCTION  **/

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

/** FOOTER **/

footer {
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

header h1 {
  animation: MoveLeft 1s ease-out;
}

header h2,
p {
  animation: MoveRight 1s ease-out;
}

@keyframes MoveLeft {
  0% {
    opacity: 0;
    transform: translateX(-200px);
  }

  80% {
    opacity: 0.6;
    transform: translateX(10px);
  }

  100% {
    opacity: 1;
    transform: translateX(0px);
  }
}
@keyframes MoveRight {
  0% {
    opacity: 0;
    transform: translateX(200px);
  }

  80% {
    opacity: 0.6;
    transform: translateX(10px);
  }

  100% {
    opacity: 1;
    transform: translateX(0px);
  }
}

form {
  animation: moveTop 1s ease-out 1s;
  animation-fill-mode: backwards;
}

@keyframes moveTop {
  0% {
    opacity: 0;
    transform: translateY(50px);
  }

  100% {
    opacity: 1;
    transform: translateX(0px);
  }
}
</style>
