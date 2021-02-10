<template>
    <article>
        <h2>{{ title }}</h2>
            <h3>{{ subtitle }}</h3>
            <img src= alt= {{ imgAlt }}>
            <div class="buttons">
              {{ liveLinkURL }}<button class='live-site'>LIVE SITE</button></a>
              {{ githubLinkURL }}<button class='github-code'>GITHUB</button></a>
            </div>
            <div class="description">
                {{ description }}
              </div>
            <div class="tech">
                {{ tech }}
              </div>
    </article>
</template>


<script>
export default {
    name: Project,
    props: {
        title: String,
        subtitle: String,
        img: String,
        imgAlt: String,
        liveLink: String,
        githubLink: String,
        description: String,
        tech: String,
        },
    computed: {
        createLiveLinkURL: function() {
            let liveLinkURL = `<a href=${this.liveLink} target='_blank'>`
            return liveLinkURL
        },
        createGithubLinkURL: function() {
            let githubLinkURL = `<a href=${this.githubLink} target='_blank'`
        },
        createImgSrc: function() {
            let imgSrc = `${this.img}`
        }
    }
}
</script>



<style scoped>

</style>