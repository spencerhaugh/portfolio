<template>
  <h1>// HELLO</h1>
  <div class="about">

    <div class="about-container">
      <div class="profile-pic">
        <ProfileImage />
      </div>
      <div class="about-skills">
        <Skills />
      </div>
    </div>

    <article class="about-text">
      <section id="professional">
        <h3>About Me</h3>
        <p>
          I am a full stack software developer with a background in Business Development and
          Marketing. I strive to build elegant solutions to common and uncommon problems with a
          focus on intuitive, user-friendly resolutions. I excel in Javascript, and have experience
          with React and Vue, as well as Node and Express for the backend.
          (I dabble in Python too!)
        </p>
        <p>
          I am one of those rare
          developers that loves working with CSS and styling, and I am loving Sass.
          I love building in that interaction with users, and creating great experiences.
        </p>
        <p>
          As a patient soul, I excel in bringing a calm to the storm of business with my years of
          experience in process improvement, problem-solving, and client-first solutions.
          My background in marketing and my interst in design lend to my strength
          in front end development, but my analytical side also loves backend work.
          (My love of Excel spreadsheets is a dead giveaway).
        </p>
        <p>
          I fell in love with programming because of the endless learning! I am a person
          who loves adding new skills to my knowledge base, and with code there is no end to
          knowledge! I am excited to learn from great companies and great mentors!
          Next on my personal agenda to learn is: Docker, Typescript, and Next.
        </p>
      </section>

      <section id="personal">
        <h3>Ok, Really About Me</h3>
        <p>
          But that's business, and I'm a lot more than that! My favorite hobby outside of the
          office is cycling. I've raced bicycles for years, and I enjoy it so much that
          I have a fairly popular podcast about it, (The Slow Ride Podcast). I really
          enjoy creating #content.
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
          (Feel free to ask me about any of these interests, I love to talk about them!)
        </p>
      </section>

      <section id="important">
        <h3>Also:</h3>
        <p>I also <strong>*strongly*</strong> believe in equality and dismantling problematic
          systemic infrastructure such as racism, sexism, homophobia, and the toxic enviroments
          that enable them. I think that this is necessary and important information to put
          here on the site, as any company I agree to work for will absolutely
          need to share those beliefs.
        </p>
      </section>
    </article>
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
  .about {
    display: flex;
    width: 90%;
    justify-content: center;
    align-items: flex-start;
    margin: 0 auto;
  }
  .about-text {
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    width: 50%;
    padding: 3%;
    margin: 1% auto;
    background-color: rgb(247, 242, 242);
    border-radius: 10px;
    -webkit-box-shadow: 2px 2px 8px 0px rgba(70, 70, 70, 0.69);
    -moz-box-shadow:    2px 2px 8px 0px rgba(70, 70, 70, 0.69);
    box-shadow:         2px 2px 8px 0px rgba(70, 70, 70, 0.69);
  }
  h1 {
    padding: 10px;
  }
  .about-container {
    display: flex;
    flex-direction: column;
    justify-content: flex-start;
    align-items: center;
    padding: 0 3%;
  }
  .profile-pic {
    margin-bottom: 20%;
  }
  #personal {
    background-color: #f5af19;
    color: #fff;
    padding: 1% 3%;
    border-radius: 10px;
    width: 80%;
    margin: 10px 0;
    -webkit-box-shadow: 2px 2px 8px 0px rgba(70, 70, 70, 0.69);
    -moz-box-shadow:    2px 2px 8px 0px rgba(70, 70, 70, 0.69);
    box-shadow:         2px 2px 8px 0px rgba(70, 70, 70, 0.69);
  }
  @media (max-width: 850px) {
    .about {
      flex-direction: column;
      align-items: center;
    }
    .about-text {
      width: 90%;
      margin-top: 5%;
      margin-bottom: 5%;
    }
  }
</style>
