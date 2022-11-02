<template>
  <section>
    <div class="container">
      <div class="right"></div>
      <div class="left">
        <div class="paragraph">
          <h3>Free, open, simple</h3>
          <p>
            Blogr is a free and open source application backed by a large
            community of helpful developers. It supports features such as code
            syntax highlighting, RSS feeds, social media integration,
            third-party commenting tools, and works seamlessly with Google
            Analytics. The architecture is clean and is relatively easy to
            learn.
          </p>
        </div>
        <div class="paragraph">
          <h3>Powerful tooling</h3>

          <p>
            Batteries included. We built a simple adn straightforward CLI tool
            that makes customization and deployment a breeze, but capable of
            producing even the most complicated sites.
          </p>
        </div>
      </div>
    </div>
  </section>
</template>
<script>
export default {};
</script>
<style scoped>
section {
  width: 100%;
  height: 120vh;
  background-image: url(../assets/illustration-laptop-desktop.svg);
  background-size: 70%;
  background-repeat: no-repeat;
  background-position: -70% 60%;
  display: flex;
  flex-direction: column;
  justify-content: flex-start;
  align-items: center;
  justify-content: center;
  row-gap: 6rem;
}
h1 {
  text-align: center;
  color: var(--vdblue);
  font-size: 3rem;
  font-family: "Overpass";
  margin-top: 10rem;
}
h3 {
  text-align: left;
  color: var(--vdblue);
  font-size: 2rem;
  font-family: "Overpass";
}

.container {
  display: flex;
  justify-content: center;
  width: 65%;
  height: fit-content;
}
.left {
  width: 100%;
  height: 100%;
  display: flex;
  flex-direction: column;
  row-gap: 4rem;
}
.right {
  width: 100%;
  height: 100%;
}
.paragraph {
  width: 100%;
  display: flex;
  flex-direction: column;
  row-gap: 1rem;
}
.paragraph p {
  color: var(--vdgblue);
  font-family: "Ubuntu", sans-serif;
  font-weight: 300;
  font-size: 1.1rem;
  opacity: 0.8;
}
</style>
