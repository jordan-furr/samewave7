<template>
  <main>
      <div class = "container">
        <p><NuxtLink to="/about"><img src="~/public/stitch_logo.png" alt="Samewave7 stitch logo" class="logo" /></NuxtLink></p>
      </div>
  </main>
</template>

<style>
 @import '/style.css';
.container{
  height: 100vh;
  width: 100vw;
  background: #5ea06c;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
}
h1{
  text-align: center;
  font-family: helvetica, arial, sans-serif;
  font-weight: 800;
}
main {
    background-color: orange;
}
.logo{
    height: 40vh;
}
.logo:hover{
    height: 41vh;
}
</style>