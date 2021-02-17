<template>
    <div class="resume-link">
        <a class=“btn-download” href="https://drive.google.com/file/d/1YKQjIuS1CmZHoW3dl2JBivNAk3nIg2fS/view?usp=sharing" target="_blank" rel="noreferrer noopener">
            <button class="button resume">Download Resume</button>
        </a>
    </div>
</template>

<script>
export default {
  name: 'Resume',
};
</script>

<style scoped>
    .resume {
        padding: 15px;
        width: 220px;
        color: cornsilk;
        background-color: orange;
        border: 1px solid transparent;
        font-size: 1.2rem;
        font-weight: bold;
        margin-top: 5%;
    }
    .resume:hover {
        background-color: steelblue;
        cursor: pointer;
    }
    .resume:focus {
        outline: solid 4px transparent;
        /* Added accessibility */
    }
</style>
