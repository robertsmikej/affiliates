<template>
    <section class="container">
        <div>
            <logo/>
            <h1 class="title">
            affiliates
            </h1>
            <h2 class="subtitle">
            My super-duper Nuxt.js project
            </h2>
            <div class="links">
            <a
                href="https://nuxtjs.org/"
                target="_blank"
                class="button--green">Documentation</a>
            <a
                href="https://github.com/nuxt/nuxt.js"
                target="_blank"
                class="button--grey">GitHub</a>
            </div>
        </div>
    </section>
</template>

<script>
import Logo from '~/components/Logo.vue'

export default {
    components: {
        Logo
    },
    head() {
        return {
            script: [{ src: 'https://identity.netlify.com/v1/netlify-identity-widget.js' }],
        };
    },
}
</script>

<style>

.container {
    min-height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
}

</style>
