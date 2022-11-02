<template>
  <router-view />
  <TheFooter/>
</template>
<script>
import TheFooter from '@/components/TheFooter.vue';

export default {
  components: {
    TheFooter
  }
}
</script>
<style>
@import url("https://fonts.googleapis.com/css2?family=Overpass:wght@300;600&family=Ubuntu:wght@400;500;700&display=swap");
/* 
font-family: 'Overpass', sans-serif;
font-family: 'Ubuntu', sans-serif;
 */

*,
*::before,
*::after {
  box-sizing: border-box;
}
* {
  margin: 0;
}
html,
body {
  height: 100%;
}
body {
  line-height: 1.5;
  -webkit-font-smoothing: antialiased;
}
img,
picture,
video,
canvas,
svg {
  display: block;
  max-width: 100%;
}
input,
button,
textarea,
select {
  font: inherit;
}
p,
h1,
h2,
h3,
h4,
h5,
h6 {
  overflow-wrap: break-word;
}
#root,
#__next {
  isolation: isolate;
}
:root {
  /* primary */
  --lred: hsl(356, 100%, 66%); /* CTA Text */
  --vlred: hsl(355, 100%, 74%); /* CTA Hover Background */
  --vdblue: hsl(208, 49%, 24%); /* Headings */

  /* neutral */
  --text: hsl(0, 0%, 100%); /* Text */
  --ftext: hsl(240, 2%, 79%); /* Footer Text */
  --vdgblue: hsl(207, 13%, 34%); /* body copy */
  --footerbg: hsl(240, 10%, 16%); /* Footer background */
}
</style>
