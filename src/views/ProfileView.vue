<template>
  <main class="h-full">
    <ProfileComponent></ProfileComponent>
  </main>
</template>

<script>
  import ProfileComponent from "../components/ProfileComponent.vue";
  export default {
    name: "ProfileView",
    components: {ProfileComponent},
  }
</script>
