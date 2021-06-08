<template>
    <div class="resume-link">
        <a class=“btn-download” href="https://drive.google.com/file/d/1baZgV-xa1vv9O49bZSzyn0kotlY8R0f1/view?usp=sharing" target="_blank" rel="noreferrer noopener">
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
