<template>
  <div class="col-12 d-flex flex-row justify-content-between hero align-items-center">
      <div class="hero-text-section col-5">
          <h2 class="hero-heading">Want anything to be easy with <span>LaslesVPN.</span></h2>
          <p>Provide a network for all your needs with ease and fun using LaslesVPN discover interesting features from us.</p>
          <button class="hero-btn">Get Started</button>
      </div>
      <div>
          <img src="./../assets/img/hero.png" alt="Hero Image">
      </div>
  </div>
</template>

<script>
export default {
    name: 'Hero',
}
</script>

<style scoped>
.hero{
    background: #ffffff;
    padding: 1.5rem 10rem 10rem 10rem;
}
.hero-heading{
    color:#0B132A;
    font-size: 3.125rem;
    font-weight: 600;
    line-height: 4.375rem;
}
.hero-heading span {
    font-weight: 700;
}
.hero-text-section p{
    font-size: 1rem;
    line-height: 1.875rem;
    color: #4F5665;
}
.hero-btn{
    background: #F53838;
    color: #ffffff;
    padding: .8rem 3rem;
    border-radius: 10px;
    border: none;
    margin-top: 2rem;
    filter: drop-shadow(0px 15px 15px #F53838);
    font-weight: 600;
}
</style>