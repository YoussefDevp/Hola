<template>
  <div class="home">
    <header id="header">
      <nav id="nav">
        <logo> </logo>
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
      <information
        title="Enjoy on your Computer Screen"
        description="You can watch on your computer screen by an easy cliking."
        img="/image/undraw_Devices_re_dxae.svg"
      >
      </information>
      <hr />
      <information
        title="Download your shows to watch offline."
        description="Watch on Smart TVs , smartphone, tablet and more."
        img="/image/undraw_Mobile_app_p3ts.svg"
      >
      </information>
      <hr />
      <information
        title="Save your favorites easily and always have something to watch."
        description="Stream unlimited movies and TV shows on your phone, tablet, laptop,
            and TV without paying more..."
        img="/image/undraw_Devices_re_dxae.svg"
      >
      </information>
    </section>
    <hr />
    <question></question>
    <hr />
    <footers class="footer"></footers>
  </div>
</template>

<script>
import Information from "../components/Information";
import Logo from "../components/Logo";
import Footers from "../components/Footers";
import Question from "../components/Question";

export default {
  name: "Home",
  components: {
    Information,
    Logo,
    Footers,
    Question
  }
};
</script>

<style>
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
    url("../assets/header_img.jpg") top center/cover;
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

header h1 {
  animation: MoveLeft 1s ease-out;
}

header h2,
p {
  animation: MoveRight 1s ease-out;
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
