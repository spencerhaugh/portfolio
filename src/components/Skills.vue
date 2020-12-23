<template>
    <div class="about-skills-inner">
        <h2>// SKILLS</h2>
        <div class="skills-container">
            <div class="skills-list">
                <ul>
                    <li><i class="fab fa-js"></i>Javascript</li>
                    <li>CSS</li>
                    <li>HTML</li>
                    <li>Node.js</li>
                    <li>Express</li>
                    <li>MongoDB</li>
                    <li>React.js</li>
                </ul>
            </div>
            <div class="skills-list">
                <ul>
                    <li>Vue.js</li>
                    <li>Python</li>
                    <li>Flask</li>
                    <li>jQuery</li>
                    <li>Git/Github</li>
                    <li>Bootstrap</li>
                    <li>Flask</li>
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
        text-align: center;
        font-size: 1.2rem;
    }
</style>
