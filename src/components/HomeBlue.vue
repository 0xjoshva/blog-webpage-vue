<template>
  <section>
    <div class="container">
      <img src="../assets/illustration-phones.svg" alt="" id="phones" />
    </div>
    <div class="container">
      <h1>State of the Art Infrastructure</h1>
      <p>
        With reliability and speed in mind, worldwide data centers provide
        the backbone for ultra-fast connectivity. This ensures your site will
        load instantly, no matter where your readers are, keeping your site
        competitive.
      </p>
    </div>
  </section>
</template>
<script>
export default {};
</script>
<style scoped>
section {
  width: 100%;
  height: 90vh;
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;
}
.container:nth-child(1) {
  width: 50%;
  height: 50vh;
  background: url(../assets/bg-pattern-circles.svg),
    linear-gradient(90deg, hsl(237, 17%, 21%), hsl(237, 18%, 21%));
  background-repeat: no-repeat;
  background-position-x: -60%;
  background-position-y: 90%;
  background-size: 100%;
  border-bottom-left-radius: 150px;
  display: flex;
  justify-content: center;
  align-items: center;
}
#phones {
  scale: 1.4;
  filter: drop-shadow(-5px 0px 10px rgba(34, 34, 34, 0.39));
}
.container:nth-child(2) {
  width: 50%;
  height: 50vh;
  background: linear-gradient(90deg, hsl(237, 18%, 21%), hsl(237, 23%, 32%));
  background-repeat: no-repeat;
  background-position-x: -60%;
  background-position-y: 90%;
  background-size: 100%;
  border-top-right-radius: 150px;
  display: flex;
  flex-direction: column;
  justify-content: center;
}
.container:nth-child(2) h1 {
    font-size: 3rem;
font-family: 'Overpass', sans-serif;
font-weight: 600;
color: var(--text);
text-align: left;
}
.container:nth-child(2) p {
    color: var(--ftext);
    font-size: 1.2rem;
    font-family: 'Overpass', sans-serif;
    text-align: left;
    width: 70%;
    line-height: 2.2rem;
}
</style>
