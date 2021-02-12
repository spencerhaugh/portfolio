<template>
    <div class="contact">
        <h1>// LET'S TALK</h1>
        <h3>
            <ul>
                <li><i class="fas fa-envelope-square fa-2x"></i> <span> spencer.haugh@gmail.com
                    </span></li>
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
        width: 25%;
        margin: 8% auto;
        padding: 0;
    }
    li {
        display: flex;
        justify-content: space-between;
        align-items: center;
    }
    @media (max-width: 1224px) {
        ul {
            width: 40%;
        }
    @media (max-width: 768px) {
        .contact {
            font-size: 0.75rem;
        }
        ul {
            width: 50%;
        }
    }
    @media (max-width: 400px) {
        ul {
            width: 90%;
        }
    }
    }
</style>
