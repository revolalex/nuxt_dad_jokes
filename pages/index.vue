<template>
  <div>
    <h2>Welcome to the best dad jokes app on the web</h2>
    <img class="responsive" src="https://raw.githubusercontent.com/yesinteractive/dad-jokes_microservice/master/public/dadjokes-microservice.png"/>
  </div>
</template>

<script>
export default {
  head() {
    return {
      title: "Welcome To Dad Jokes",
      meta: [
        {
          hid: "description",
          name: "description",
          content: "Best place for amazing dad jokes, you can search a joke by keyword"
        }
      ]
    };
  }
};
</script>
<style >
.responsive {
  width: 100%;
  max-width: 800px;
  height: auto;
}
body{
  background-color: rgb(245, 231, 214);
}

</style>