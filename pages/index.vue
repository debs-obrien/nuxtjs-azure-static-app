<template>
  <div>
    <div>
      <h1 class="title">
        Nuxt.js & Azure
      </h1>
      <h2 class="subtitle">
        Deploying your static site to Azure Static Web Apps
      </h2>
      <div class="links">
          <ul>
            <li>
              <NuxtLink to="/about" class="button--green">about</NuxtLink>
            </li>
            <li>
              <NuxtLink to="/spa-fallback" class="button--green">Spa Fallback</NuxtLink>
            </li>
            <li>
              <NuxtLink to="/404" class="button--green">Custom error page</NuxtLink>
            </li>
          </ul>
          <a
          href="https://github.com/debs-obrien/nuxtjs-azure-static-app"
          target="_blank"
          class="button--grey"
        >
          GitHub
        </a>
        <a href="https://nuxtjs.org/faq/deployment-azure-static-web-apps" target="_blank" class="button--green">
          Documentation
        </a>
        
      </div>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style scoped>
.links {
  padding-top: 15px;
}
</style>
