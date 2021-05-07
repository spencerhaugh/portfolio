<template>
    <div class="about-skills-inner">
        <h2>// SKILLS</h2>
        <div class="skills-container">
            <div class="skills-list">
                <ul>
                    <li><i class="fab fa-js"></i> Javascript</li>
                    <li><i class="fab fa-css3-alt"></i> CSS</li>
                    <li><i class="fab fa-html5"></i> HTML</li>
                    <li><i class="fab fa-node-js"></i> Node.js</li>
                    <li><i class="fab fa-node"></i> Express</li>
                    <li><i class="fas fa-universal-access"></i> A11y</li>
                </ul>
            </div>
            <div class="skills-list">
                <ul>
                    <li><i class="fab fa-react"></i> React</li>
                    <li><i class="fab fa-github-square"></i> Git/Github</li>
                    <li><i class="fab fa-vuejs"></i> Vue.js</li>
                    <li><i class="fab fa-python"></i> Python</li>
                    <li><i class="fab fa-bootstrap"></i> Bootstrap</li>
                    <li><i class="far fa-question-circle"></i> jQuery</li>

                </ul>
            </div>
        </div>
    </div>

</template>

<script>
export default {
  name: 'Skills',
};
</script>

<style scoped>
    ul {
        list-style: none;
    }
    li {
        transition: all .5s ease-in-out;
    }
    .skills-container {
        border: 1px solid #555;
        display: flex;
        justify-content: center;
        border-radius: 10px;
    }
    .skills-list {
        padding-left: 5px;
        padding-right: 40px;
        text-align: left;
        font-size: 1.2rem;
    }
    h2 {
    color: #f5af19;
    }
    li:hover {
        color: #f5af19;
        transform: translateX(-10px)
    }
    @media (max-width: 600px) {
      .skills-list {
          font-size: 0.7rem;
          padding-top: 10px;
      }
  }
</style>
