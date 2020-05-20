<template>
    <div class="wrapper">
        <h1 class="title">SPA fallback Page</h1>
        <p class="subtitle">This is generated as a SPA fallback</p>
        <p>View the source code to see that it wasn't generated. It acts as if it was a SPA page so content is not pre-rendered. This can be done by adding generate.excludes in your nuxt.config.</p>
        <NuxtLink to="/">Back to Home</NuxtLink>
    </div>
</template>
<style scoped>
.wrapper{
    max-width: 800px;
}
</style>