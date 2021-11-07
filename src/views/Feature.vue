<template>
  <div class="col-12 d-flex flex-row justify-content-evenly feature align-items-center">
      <div>
          <img src="./../assets/img/feature.png" alt="Feature Image">
      </div>
      <div class="feature-text-section col-4">
          <h2 class="feature-heading">We Provide Many Features You Can Use</h2>
          <p>You can explore the features that we provide with fun and have their own functions each feature.</p>
          <ul>
              <li>Powerfull online protection.</li>
              <li>Internet without borders.</li>
              <li>Supercharged VPN</li>
              <li>No specific time limits.</li>
          </ul>
      </div>
  </div>
</template>

<script>
export default {
    name: 'Feature'
}
</script>

<style scoped>
.feature{
    background: #ffffff;
    padding: 4.5rem 10rem 10rem 10rem;
}
.feature-heading{
    color:#0B132A;
    font-size: 2.188rem;
    font-weight: 600;
    line-height: 3.125rem;
}
.feature-text-section p{
    font-size: 1rem;
    line-height: 1.875rem;
    color: #4F5665;
}
.feature-text-section li{
    font-size: .9rem;
    line-height: 1.875rem;
    color: #4F5665;
    list-style-image:url('./../assets/img/check-icon.png') ;
}
</style>