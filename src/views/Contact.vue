<template>
    <div class="contact">
        <h1>// LET'S TALK</h1>
        <h3>
            <ul>
                <li><i class="fas fa-envelope-square fa-2x"></i> spencer.haugh@gmail.com</li>
                <li><i class="fab fa-linkedin fa-2x"></i> <a href="https://linkedin.com/in/spencerhaugh" target="_blank">linkedin.com/in/spencerhaugh</a></li>
                <li><i class="fab fa-github-square fa-2x"></i> <a href="https://github.com/spencerhaugh" target="_blank">github.com/spencerhaugh</a></li>
            </ul>
        </h3>
    </div>
</template>

<script>
export default {
  name: 'Contact',
};
</script>

<style scoped>
    ul {
        list-style: none;
        margin-top: 10%;
        padding: 0;
    }
    @media (max-width: 650px) {
        .contact {
            font-size: 0.75rem;
        }
    }
</style>
