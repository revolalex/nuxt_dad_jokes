<template>
  <div>
    <h1>About DadJokes</h1>
    <p>This is an app that displays corny dad jokes.</p>
    <br/>
    <p>I made this app because i wanted to learn Nuxt.js.</p>
    <br />
    <div class="alignCenter">
      <img
        class="nuxtLogo"
        src="https://upload.wikimedia.org/wikipedia/commons/4/45/NuxtJS_Logo.png"
      />
      <h2>Advantage of Nuxt.js :</h2>
    </div>

    <ul class="myUl">
      <li>SEO optimization</li>
      <li>Universal apps : server side rendering</li>
      <li>Control of head, title, meta etc.</li>
      <li>Simple page routing</li>
    </ul>
  </div>
</template>

<script>
export default {
  head() {
    return {
      title: "About The App",
      meta: [
        {
          hid: "description",
          name: "description",
          content: "Best place for corny dad jokes",
        },
      ],
    };
  },
};
</script>

<style>
.myUl li {
  list-style: square inside;
}
.nuxtLogo {
  width: 40px;
  height: auto;
}
.alignCenter {
  display: flex;
  align-items: center;
}
</style>