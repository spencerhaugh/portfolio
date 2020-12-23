<template>
  <div class="about">
    <h1>// HELLO</h1>
    <div class="about-text">
      <p>
        As a software engineer with a background in Business Development and Project
        Management, I build elegant solutions to common and uncommon problems with a
        focus on intuitive, user-friendly resolutions.
      </p>
      <p>
        I specialize in bringing a calm to the storm of business with my years of
        experience in process improvement, problem-solving, and client-first solutions.
      </p>
    </div>
    <div class="about-container">
      <div class="profile-pic">
        <ProfileImage />
      </div>
      <div class="about-skills">
        <Skills />
      </div>
    </div>
  </div>
</template>

<script>
import Skills from '@/components/Skills.vue';
import ProfileImage from '@/components/ProfileImage.vue';

export default {
  name: 'About',
  components: {
    Skills,
    ProfileImage,
  },
};
</script>

<style scoped>
  .about-text {
    width: 50%;
    padding: 10px;
    margin: 0 auto;
  }
  h1 {
    padding: 10px;
  }
  .about-container {
    display: flex;
    flex-direction: row;
    justify-content: center;
    margin-top: 5%;
  }
  @media (max-width: 650px) {
    .about-container {
      flex-direction: column;
      align-items: center;
    }
  }
</style>
