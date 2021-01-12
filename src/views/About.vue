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
      <p>
        But that's business. I'm a lot more than that! My favorite hobby outside of the
        office is cycling. I've raced bicycles for years, and I enjoy it so much that
        I have a fairly populate podcast about it (The Slow Ride Podcast).
      </p>
      <p>
        I also have a 1988 VW Vanagon that I am trying to restore, I don't know a
        lot about cars but I'm trying to learn.
      </p>
      <p>
        Lastly, I'm still trying to get better at play guitar, but I'm only about as
        good as I was at 15. Still, I really enjoy it!
      </p>
      <p>
        Feel free to ask me about any of these interests, I love to talk about them!
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
