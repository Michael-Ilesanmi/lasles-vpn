<template>
<div class="col-12 m-auto d-flex flex-row justify-content-between align-items-center nav-bar">
    <div>
        <img src="./../assets/img/logo.png" alt="Logo">
    </div>
    <div class="col-5">
        <ul class="nav-links d-flex justify-content-between">
            <li>About</li>
            <li>Features</li>
            <li>Pricing</li>
            <li>Testimonials</li>
            <li>Help</li>
        </ul>
    </div>
    <div class="">
        <button class="custom-btn">Sign In</button>
        <button class="custom-btn custom-btn-outline">Sign Up</button>
    </div>
</div>
</template>

<script>
export default {
    name: 'NavBar',
}
</script>

<style scoped>
.nav-bar{
    background: #ffffff;
    font-size: 1rem;
    padding: 1.5rem 10rem;
    line-height: 1rem;
}
.nav-links{
    list-style: none;
    cursor: pointer;
    color: #4F5665;
    padding: 0;
    margin: 0;
}
.nav-links li{
    position: relative;
    padding: 0 6px;
}
.nav-links li::after{
    content: '';
    position: absolute;
    background-color: #F53855;
    width:0%;
    height: 4px;
    left: 0;
    bottom: -10px;
    transition: 500ms ease;
}
.nav-links li:hover::after{
    width: 100%;
}
.custom-btn{
    color: #0B132A;
    background:transparent;
    border: none;
    font-weight: 600;
    transition: 300ms ease-in-out;
    padding:10px 2rem;
}
.custom-btn:hover{
    color: #F53855;
}
.custom-btn-outline{
    border: 1px #F53855 solid;
    border-radius: 50px;
    color: #F53855;
}
.custom-btn-outline:hover{
    background: #F53855;
    color: #ffffff;
}
</style>