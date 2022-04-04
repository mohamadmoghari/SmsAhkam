<template>
  <section>
    <img src="../assets/logo.png" alt="" />
    <div class="info">
      <div>
        <p>shamsi date</p>
        <p>arabic date</p>
      </div>
      <base-button class="login" title="ورود"></base-button>
    </div>
  </section>
</template>
<style scoped>
section {
  display: flex;
  flex-flow: row-reverse;
  justify-content: space-between;
  padding: 3rem 5rem;
  background-color: #115740;
  color: white;
  align-items: center;
}
.info {
  display: flex;
  flex-flow: row-reverse;
  justify-content: space-between;
}
.login {
  align-self: center;
  margin-right: 1rem;
  padding: 1rem;
}
</style>