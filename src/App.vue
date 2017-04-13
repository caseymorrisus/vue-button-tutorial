<template>
  <div id="app">
    <v-header></v-header>
    <!-- TODO: Add Button component(s) -->
  </div>
</template>

<script>
import Header from 'Components/Header'

export default {
  name: 'app',
  components: {
    'v-header': Header
    // TODO: Register Button component locally
  },
  methods: {
    // TODO: Create methods that will be sent into Button component
  }
}
</script>

<style lang="scss">
@import url('https://fonts.googleapis.com/css?family=Roboto+Slab');
@import url('https://fonts.googleapis.com/css?family=Questrial');

/* http://meyerweb.com/eric/tools/css/reset/ 
   v2.0 | 20110126
   License: none (public domain)
*/

html, body, div, span, applet, object, iframe,
h1, h2, h3, h4, h5, h6, p, blockquote, pre,
a, abbr, acronym, address, big, cite, code,
del, dfn, em, img, ins, kbd, q, s, samp,
small, strike, strong, sub, sup, tt, var,
b, u, i, center,
dl, dt, dd, ol, ul, li,
fieldset, form, label, legend,
table, caption, tbody, tfoot, thead, tr, th, td,
article, aside, canvas, details, embed, 
figure, figcaption, footer, header, hgroup, 
menu, nav, output, ruby, section, summary,
time, mark, audio, video {
  margin: 0;
  padding: 0;
  border: 0;
  font-size: 100%;
  font: inherit;
  vertical-align: baseline;
}
/* HTML5 display-role reset for older browsers */
article, aside, details, figcaption, figure, 
footer, header, hgroup, menu, nav, section {
  display: block;
}
body {
  line-height: 1.4;
}
ol, ul {
  list-style: none;
}
blockquote, q {
  quotes: none;
}
blockquote:before, blockquote:after,
q:before, q:after {
  content: '';
  content: none;
}
table {
  border-collapse: collapse;
  border-spacing: 0;
}

/* apply a natural box layout model to all elements, but allowing components to change */
/* https://www.paulirish.com/2012/box-sizing-border-box-ftw/ */
html {
  box-sizing: border-box;
}

*, *:before, *:after {
  box-sizing: inherit;
  outline: none;
}

#app {
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #fff;
  margin-top: 60px;
}

body {
  background: #22264b;
  font-family: 'Roboto Slab', serif;
}

h1, h2, h3, h4, h5, h6 {
  color: #e6cf8b;
  font-weight: bold;
  font-family: 'Questrial', sans-serif;
}

h1 {
  font-size: 3em;
}

h2 {
  font-size: 2.25em;
}

h3 {
  font-size: 1.75em;
}

button, input, textarea {
  font-family: 'Roboto Slab', serif;
}
</style>
