<template>
  <main>
      <div class = "container">
          <div class="title">
              <h1>SAMEWAVE7</h1>
          </div>
          <div class="entry-button">
              <p><NuxtLink to="/about">about</NuxtLink></p>
          </div>
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
.title h1{
    font-family: 'Courier Prime', monospace;
    font-size: 5vh;
}
</style>