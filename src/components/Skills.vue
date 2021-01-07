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
                    <li>MongoDB</li>
                    <li>React.js</li>
                </ul>
            </div>
            <div class="skills-list">
                <ul>
                    <li><i class="fab fa-vuejs"></i> Vue.js</li>
                    <li><i class="fab fa-python"></i> Python</li>
                    <li><i class="fab fa-github-square"></i> Git/Github</li>
                    <li><i class="fab fa-bootstrap"></i> Bootstrap</li>
                    <li>Flask</li>
                    <li>jQuery</li>

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
    .skills-container {
        display: flex;
        justify-content: center;
    }
    .skills-list {
        background-color: palegoldenrod;
        padding-left: 5px;
        padding-right: 40px;
        text-align: left;
        font-size: 1.2rem;
    }
</style>
