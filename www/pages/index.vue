<template>
  <div
    :style="image"
    class="h-screen flex flex-col bg-cover justify-center items-center"
  >
    <img :src="logo" alt="Polar Bear Logo" class="h-32" />
    <br />
    <h1 class="text-4xl text-white">
      Dev Environment
    </h1>
  </div>
</template>

<script>
import bg from "static/bg.png";
import logo from "static/bear.svg";

export default {
  name: "IndexPage",
  data() {
    return {
      image: {
        background: `url(${bg}) no-repeat center center fixed`,
        backgroundSize: "cover",
      },
      logo: logo,
    };
  },
};
</script>
