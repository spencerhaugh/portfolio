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
    width: 65%;
    margin-top: -4%;
    box-shadow: 10px 10px 20px -8px rgba(255, 140, 40, 0.641);
    animation: floating 2.5s infinite ease-in-out;
  }
  .profile-pic-inner {
      max-width: 350px;
  }
  h2 {
    color: #f5af19;
  }
  @keyframes floating {
    0% {transform: translate(0, 0px);}
    50% {transform: translate(0, 15px);}
    100% {transform: translate(0, -0px);}
  }
</style>
