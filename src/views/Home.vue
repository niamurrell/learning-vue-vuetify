<template>
  <div class="home">
    <h1>Home Page</h1>

    <div class="demolinks indigo darken-3 white--text font-weight-bold">
      <ul>
        <li>
          <a href="https://vuetifyjs.com/en/styles/colors/">Docs &mdash; Color Classes</a>
        </li>
        <li>
          <a href="https://vuetifyjs.com/en/styles/text/">Docs &mdash; Text Manipulation Classes</a>
        </li>
      </ul>
    </div>

    <p class="red white--text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Eaque totam corrupti sint veritatis. Voluptas, voluptatum necessitatibus debitis ad, illo obcaecati nisi ipsam accusantium reprehenderit culpa porro, molestias perspiciatis possimus recusandae!</p>
    <p class="pink lighten-4 red--text text--darken-4">Lorem ipsum dolor sit amet consectetur adipisicing elit. Eaque totam corrupti sint veritatis. Voluptas, voluptatum necessitatibus debitis ad, illo obcaecati nisi ipsam accusantium reprehenderit culpa porro, molestias perspiciatis possimus recusandae!</p>
    <h1 class="display-4">Massive Display</h1>
    <h1 class="display-1">Smaller Massive Display</h1>
    <h1>Normal Display</h1>
    <p class="headline">This is a headline.</p>
    <p class="subheading">This is a subheading.</p>
    <p class="caption">This is a caption.</p>

    <v-btn class="pink white--text">Button</v-btn>
    <v-btn depressed color="pink">Button</v-btn>
    <v-btn text color="pink">Button</v-btn>
    <v-btn depressed class="pink white--text">
      <v-icon left>mdi-email</v-icon>
      <span>Email Me</span>
    </v-btn>
    <v-btn depressed small class="pink white--text">
      <v-icon small left>mdi-email</v-icon>
      <span>Email Me</span>
    </v-btn>
    <v-btn depressed large class="primary white--text">
      <span>Email Me</span>
      <v-icon large right>mdi-email</v-icon>
    </v-btn>
    <v-btn fab depressed small dark color="teal">
      <v-icon left>mdi-heart</v-icon>
    </v-btn>
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: 'Home',
  components: {},
};
</script>
