<template>
  <section>
    <h1>Designed for future</h1>
    <div class="container">
      <div class="left">
        <div class="paragraph">
          <h3>Introducing an extensible editor</h3>
          <p>
            Blogr features an exceedingly intuitive interface which lets you
            focus on one thing: creating content. The editor supports management
            of multiple blogs and allows easy manipulation of embeds such as
            images, videos, and Markdown. Extensibility with plugins and themes
            provide easy ways to add functionality or change the looks of a
            blog.
          </p>
        </div>
        <div class="paragraph">
          <h3>Robust content management</h3>

          <p>
            Flexible content management enables users to easily move through
            posts. Increase the usability of your blog by adding customized
            catefories, sections, format, or flow. With this functionality,
            you're in full control.
          </p>
        </div>
      </div>
      <div class="right"></div>
    </div>
  </section>
</template>
<script>
export default {};
</script>
<style scoped>
section {
  width: 100%;
  height: 100vh;
  background-image: url(../assets/illustration-editor-desktop.svg);
  background-size: 55%;
  background-repeat: no-repeat;
  background-position: 135% -100%;
  display: flex;
  flex-direction: column;
  justify-content: flex-start;
  align-items: center;
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
  width: 30%;
  height: 100%;
}
.paragraph{
    width: 60%;
    display: flex;
    flex-direction: column;
    row-gap: 1rem;
}
.paragraph p{
    color: var(--vdgblue);
    font-family: 'Ubuntu', sans-serif;
    font-weight: 300;
    font-size: 1.1rem;
    opacity: .8;
}
</style>
