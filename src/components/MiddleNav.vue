<template>
  <div class="col-8 m-auto middle-nav">
      <div class="stats d-flex flex-row justify-content-evenly">
          <div>
            <i class="fas fa-user"></i>
            <div><span style="font-size:1.563rem;font-weight:700">90+</span> <br> Users</div>
          </div>
          <div>
            <i class="fas fa-map-marker-alt"></i>
            <div><span style="font-size:1.563rem;font-weight:700">30+</span> <br> Locations</div>
          </div>
          <div>
            <i class="fas fa-server"></i>
            <div><span style="font-size:1.563rem;font-weight:700">50+</span> <br> Servers</div>
          </div>
      </div>
  </div>
</template>

<script>
export default {
        name: 'MiddleNav',
}
</script>

<style scoped>
.middle-nav{
    background: #ffffff;
    border-radius: 10px;
    padding: 1.5rem 0;
    filter:drop-shadow(44px 50px 100px #0d102558);
    transform: translateY(-2rem);
}
.stats > div{
    border-right: 3px solid #EEEFF2;
    width: 30%;
    display: flex;
    padding: .8rem 0;
    justify-content: center;
    align-items: center;
}
.stats > div i{
    color: #F53838;
    background: #FFECEC;
    border-radius: 50%;
    padding: .8rem;
    margin-right: 2rem;
}
.stats > div:last-child {
    border-right: none;
}
</style>