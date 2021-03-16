<template>
    <div class="contact">
        <h1>// LET'S TALK</h1>
        <h3>
            <ul>
                <li><i class="fas fa-envelope-square fa-2x"></i> <span> spencer.haugh@gmail.com
                    </span></li>
                <li><i class="fab fa-linkedin fa-2x"></i> <span><a href="https://linkedin.com/in/spencerhaugh" target="_blank">linkedin.com/in/spencerhaugh</a></span></li>
                <li><i class="fab fa-github-square fa-2x"></i> <span><a href="https://github.com/spencerhaugh" target="_blank">github.com/spencerhaugh</a></span></li>
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
        margin: 6% auto;
        padding: 0;
    }
    li {
        display: flex;
        justify-content: space-between;
        align-items: center;
        margin-top: 5px;
        transition: all 0.5s ease-in-out;
    }
    li i {
        transition: color 0.5s ease-in-out;
    }
    span {
        color: #f5af19;
    }
    li:hover {
        transform: translateX(10px);
    }
    li:hover i {
        color: #f5af19;
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
