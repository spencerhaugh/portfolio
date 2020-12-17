<template>
    <div class="profile-pic-inner">
        <h2>// SPENCER</h2>
        <img src="../assets/new_profile_pic.png" alt="Image of Spencer Haugh">
      </div>
</template>

<script>
export default {
  name: 'ProfileImage',
};
</script>

<style scoped>
  img {
    border-radius: 50%;
    width: 45%;
    margin-top: -7%;
  }
  .profile-pic-inner {
      max-width: 400px;
  }
</style>
