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
          focus on intuitive, user-friendly resolutions. I excel in Javascript, and have significant
          eperience with React. I also have built with Vue, as well as Node and Express for
          the backend. (I even dabble in Python too!)
        </p>
        <p>
          I am one of those rare software
          developers that really loves working with CSS and styling, and am experienced with
          CSS compiliers like Sass, and using CSS-in-JS. I love making sites responsive!
          I also really love building interactive features for users and creating great experiences.
        </p>
        <p>
          I excel in bringing a calm to the storm of business with my years of
          experience in process improvement, problem-solving, and client-first solutions.
          I've put out a lot of "fires" in my time, and am quite good under pressure.
          My background in marketing and my interest in design lend to my strengths
          in front end development, but my analytical side also loves backend work as well.
          (My love of Excel spreadsheets is probably a dead giveaway).
        </p>
        <p>
          I fell in love with programming because of the endless learning! I am a person
          who loves adding new skills to my knowledge base, and with code there is no end to
          knowledge! I am excited to learn from great companies and great mentors!
          Next on my personal agenda to learn is: GraphQL, Typescript, and Next.
        </p>
      </section>

      <section id="personal">
        <h3>Ok, Really About Me</h3>
        <p>
          But that's all business, and I'm a lot more than that! My favorite hobby outside of the
          office is cycling. I've raced bicycles for years, and I enjoy it so much that
          I have a fairly popular podcast about it, (The Slow Ride Podcast). I really
          enjoy creating #content.
        </p>
        <p>I think the years of dedication to training and racing bikes, helps me tremendously
          as a developer. As a bike racer I spend a lot of time training solo, putting in the work
          to be my best. But, cycling is a team sport, and on race day it's knowing how to
          work effectively with the whole team that allows us to achieve our goals.
          Communication is critical.
          Showing up prepared is critical.
          Being willing to help the team is critical.
        </p>
        <p>
          I also have a 1988 VW Vanagon that I am trying to restore, I don't know a
          lot about cars but I'm trying to learn. This process also reflects in my
          devoper life; there are always new and interesting problems with a vintage van,
          and knowing what my resources are, and analysing the issue to break it down
          into managable pieces is the best way to get yourself through it
          and back on the road!
        </p>
        <p>
          Lastly, I'm still trying to get better at play guitar, but I'm only about as
          good as I was at 15. Still, I really enjoy it! Dedication, and not giving
          up on goals, even if they are challenging is a trait I cherish.
        </p>
        <p>
          Feel free to ask me about any of these interests, I love to talk about them!
        </p>
      </section>

      <section id="important">
        <h3>Also:</h3>
        <p>I also <strong>*strongly*</strong> believe in equality and dismantling problematic
          systemic infrastructure such as racism, sexism, homophobia, transphobia, and the
          toxic enviroments that enable them.
          I think that this is necessary and important information to put
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
    background-color: rgb(253, 253, 253);
    border-radius: 10px;
    -webkit-box-shadow: 4px 4px 8px 0px rgba(70, 70, 70, 0.6);
    -moz-box-shadow:    4px 4px 8px 0px rgba(70, 70, 70, 0.6);
    box-shadow:        4px 4px 8px 0px rgba(70, 70, 70, 0.6);
  }
  section p {
    -webkit-animation: text-focus-in 1s cubic-bezier(0.550, 0.085, 0.680, 0.530) both;
    animation: text-focus-in 1s cubic-bezier(0.550, 0.085, 0.680, 0.530) both;
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
    animation: slide-in-blurred-right 3s cubic-bezier(0.165, 0.84, 0.44, 1) 1.75s both;
    overflow: hidden;
  }
  /* ----------------------------------------------
 * Generated by Animista on 2021-9-6 12:3:56
 * Licensed under FreeBSD License.
 * See http://animista.net/license for more info.
 * w: http://animista.net, t: @cssanimista
 * ---------------------------------------------- */

/**
 * ----------------------------------------
 * animation text-focus-in
 * ----------------------------------------
 */
@-webkit-keyframes text-focus-in {
  0% {
    -webkit-filter: blur(12px);
            filter: blur(12px);
    opacity: 0;
  }
  100% {
    -webkit-filter: blur(0px);
            filter: blur(0px);
    opacity: 1;
  }
}
@keyframes text-focus-in {
  0% {
    -webkit-filter: blur(12px);
            filter: blur(12px);
    opacity: 0;
  }
  100% {
    -webkit-filter: blur(0px);
            filter: blur(0px);
    opacity: 1;
  }
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
/**
 * ----------------------------------------
 * animation slide-in-blurred-left
 * ----------------------------------------
 */
@keyframes slide-in-blurred-left {
0% {
    -webkit-transform: translateX(-1000px) scaleX(2.5) scaleY(0.2);
            transform: translateX(-1000px) scaleX(2.5) scaleY(0.2);
    -webkit-transform-origin: 100% 50%;
            transform-origin: 100% 50%;
    -webkit-filter: blur(40px);
            filter: blur(40px);
    opacity: 0;
  }
  100% {
    -webkit-transform: translateX(0) scaleY(1) scaleX(1);
            transform: translateX(0) scaleY(1) scaleX(1);
    -webkit-transform-origin: 50% 50%;
            transform-origin: 50% 50%;
    -webkit-filter: blur(0);
            filter: blur(0);
    opacity: 1;
  }
}
/**
 * ----------------------------------------
 * animation slide-in-blurred-right
 * ----------------------------------------
 */
@keyframes slide-in-blurred-right {
  0% {
    -webkit-transform: translateX(1000px) scaleX(2.5) scaleY(0.2);
            transform: translateX(1000px) scaleX(2.5) scaleY(0.2);
    -webkit-transform-origin: 100% 50%;
            transform-origin: 100% 50%;
    -webkit-filter: blur(20px);
            filter: blur(20px);
    opacity: 0;
  }
  100% {
    -webkit-transform: translateX(0) scaleY(1) scaleX(1);
            transform: translateX(0) scaleY(1) scaleX(1);
    -webkit-transform-origin: 50% 50%;
            transform-origin: 50% 50%;
    -webkit-filter: blur(0);
            filter: blur(0);
    opacity: 1;
  }
}
</style>
