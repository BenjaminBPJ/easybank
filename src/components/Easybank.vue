<template>
  <div>
    <header class="bannier">
      <img
        src="../assets/images/logo.svg"
        alt="Easybank's logo"
        class="logo-header"
      />
      <nav class="nav-header">
        <ul class="ul-header">
          <li>Home</li>
          <li>About</li>
          <li>Contact</li>
          <li>Blog</li>
          <li>Careers</li>
        </ul>
      </nav>
      <Button />
    </header>
    <main>
      <section class="next-generation-section">
        <article class="next-generation-article">
          <h1>Next generation digital banking</h1>
          <p class="next-generation-text">
            Take your financial life online. Your Easybank account will be a
            one-stop-shop for spending, saving, budgeting, investing, and much
            more.
          </p>
          <Button />
        </article>
        <div class="next-generation-phones">
          <img src="../assets/images/image-mockups.png" alt="Phones with easybank app" class="next-generation-image"/>
        </div>
      </section>
      <section>
        <h2>Why choose Easybank?</h2>
        <p>
          We leverage Open Banking to turn your bank account into your financial
          hub. Control your finances like never before.
        </p>
        <div>
          <img src="../assets/images/icon-online.svg" alt="" />
          <h3>Online Banking</h3>
          <p>
            Our modern web and mobile applications allow you to keep track of
            your finances wherever you are in the world.
          </p>
        </div>
        <div>
          <img src="../assets/images/icon-budgeting.svg" alt="" />
          <h3>Simple Budgeting</h3>
          <p>
            See exactly where your money goes each month. Receive notifications
            when you’re close to hitting your limits.
          </p>
        </div>
        <div>
          <img src="../assets/images/icon-onboarding.svg" alt="" />
          <h3>Fast Onboarding</h3>
          <p>
            We don’t do branches. Open your account in minutes online and start
            taking control of your finances right away.
          </p>
        </div>
        <div>
          <img src="../assets/images/icon-api.svg" alt="" />
          <h3>Open API</h3>
          <p>
            Manage your savings, investments, pension, and much more from one
            account. Tracking your money has never been easier.
          </p>
        </div>
      </section>
      <section>
        <h2>Latest Articles</h2>
        <div>
          <article>
            <img src="../assets/images/image-currency.jpg" alt="" />
            <p>By Claire Robinson</p>
            <h3>Receive money in any currency with no fees</h3>
            <p>
              The world is getting smaller and we’re becoming more mobile. So
              why should you be forced to only receive money in a single …
            </p>
          </article>
          <article>
            <img src="../assets/images/image-restaurant.jpg" alt="" />
            <p>By Wilson Hutton</p>
            <h3>Treat yourself without worrying about money</h3>
            <p>
              Our simple budgeting feature allows you to separate out your
              spending and set realistic limits each month. That means you …
            </p>
          </article>
          <article>
            <img src="../assets/images/image-plane.jpg" alt="" />
            <p>By Wilson Hutton</p>
            <h3>Take your Easybank card wherever you go</h3>
            <p>
              We want you to enjoy your travels. This is why we don’t charge any
              fees on purchases while you’re abroad. We’ll even show you …
            </p>
          </article>
          <article>
            <img src="../assets/images/image-confetti.jpg" alt="" />
            <p>By Claire Robinson</p>
            <h3>Our invite-only Beta accounts are now live!</h3>
            <p>
              After a lot of hard work by the whole team, we’re excited to
              launch our closed beta. It’s easy to request an invite through the
              site ...
            </p>
          </article>
        </div>
      </section>
    </main>
    <footer>
      <div>
        <div>
          <img src="../assets/images/logo.svg" alt="" />
          <div>
            <img src="../assets/images/icon-facebook.svg" alt="" />
            <img src="../assets/images/icon-youtube.svg" alt="" />
            <img src="../assets/images/icon-twitter.svg" alt="" />
            <img src="../assets/images/icon-pinterest.svg" alt="" />
            <img src="../assets/images/icon-instagram.svg" alt="" />
          </div>
        </div>
        <nav>
          <ul>
            <li>About us</li>
            <li>Contact</li>
            <li>Blog</li>
            <li>Careers</li>
            <li>Support</li>
            <li>Privacy policy</li>
          </ul>
        </nav>
      </div>
      <div>
        <Button />
        <p>© Easybank. All Rights Reserved</p>
      </div>
    </footer>
  </div>
</template>

<script>
import Button from "../components/Button.vue";

export default {
  name: "Easybank",
  components: {
    Button,
  },
};
</script>

<style scoped>
/* -- Header -- */
.bannier {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 1rem;
  margin-right: 10rem;
}

.logo-header{
  height: 1.5rem;
}

.ul-header > li {
  padding: 1rem;
}

/*next-generation */
.next-generation-section {
  display: flex;
  overflow: hidden;
}

.next-generation-article{
  display: flex;
  flex-direction: column;
  padding-top: 10rem;
  padding-left: 1rem;
}

h1{
  font-size: 4rem;
  font-weight: 50;
  margin-bottom: 1rem;
}

.next-generation-text{
  margin-bottom: 1rem;
}

.next-generation-phones{
  width: 65%;
  background-image: url(../assets/images/bg-intro-desktop.svg);
  background-size: cover;
  background-repeat: no-repeat;
  margin-top: -8rem;
  padding-left: 19rem;
}

</style>
